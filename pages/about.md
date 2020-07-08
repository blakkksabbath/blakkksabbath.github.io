---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi! My name is **{{ site.author.name }}** :wave:<br>
I will be starting a Ph.D. program in computer science at the University of Missouri - <a target='_blank' rel='noopener noreferrer' href='https://missouri.edu/'>Mizzou</a> - this fall. After finishing my graduate program, I am very interested in pursuing a career in machine learning, artificial intelligence, and data science research. Applications of these technologies that intrigue me the most are their innovative uses in bioinformatics, computational biology, medicine, health care, computer vision, natural language processing, and a host of other fields like computer graphics and simulations.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>