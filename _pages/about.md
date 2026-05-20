---
permalink: /
excerpt: "Charles Westphal — PhD candidate in computer science at UCL, working on multivariate information theory for machine learning."
author_profile: false
---

{% include hero.html %}

<section id="about" class="scroll-section" markdown="1">

I am a Ph.D. candidate in Computer Science at **University College London**, where my work is grounded in multivariate information theory and its applications to modern machine learning.

</section>

<section id="research" class="scroll-section" markdown="1">

## Research

My research is motivated by **multivariate information theory** — a framework for reasoning about how information is shared, decomposed, and transformed across complex systems. The methods I develop are theoretically rooted but broadly applicable, with applications in:

- Feature selection, engineering, and interpretation
- Reinforcement learning
- Neural network pruning and compression
- Variational inference and representation learning

Recent work has been published at **SIGKDD**, **AISTATS**, and **ICML**.

</section>

<section id="publications" class="scroll-section">

<h2>Publications</h2>

{% include publications-list.html %}

</section>

<section id="talks" class="scroll-section">

<h2>Talks</h2>

<ul class="talk-list">
{% assign sorted_talks = site.talks | sort: 'date' | reverse %}
{% for talk in sorted_talks %}
  <li>
    <strong>{{ talk.title }}</strong>
    <span class="talk-meta">{{ talk.venue }}{% if talk.location %} &middot; {{ talk.location }}{% endif %} &middot; {{ talk.date | date: "%b %Y" }}</span>
  </li>
{% endfor %}
</ul>

</section>

<section id="cv" class="scroll-section" markdown="1">

## CV

[Download my CV (PDF)]({{ site.baseurl }}/images/Charles_Westphal_CV.pdf)

</section>

<section id="contact" class="scroll-section" markdown="1">

## Contact

[charles.westphal.21@ucl.ac.uk](mailto:charles.westphal.21@ucl.ac.uk)

</section>
