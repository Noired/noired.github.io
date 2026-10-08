---
layout: default
title: Home
---

# _{{ site.title | default: site.github.repository_name }}_

<p style="margin-top:-12px;margin-bottom:12px;color:#333">
	<span style="white-space:nowrap"><b>Postdoc</b> &middot; <a href="https://ece.technion.ac.il/">Technion</a></span>
	<span style="color:#bbb;margin:0 6px">|</span>
	<b>Incoming Faculty</b> &middot; <a href="https://cispa.de/en">CISPA</a> Helmholtz Center for Information Security (Jan 2027)
</p>

<hr>

<div class="announce">
	<p class="announce-title">Hiring a PhD student and a postdoc</p>
	<p>I am building a research group at CISPA on machine learning for structured data and reliable foundation models.</p>
	<a class="cta" href="{{ "/join" | relative_url }}">How to join &rarr;</a>
</div>
<!-- 
Hi! I am Fabrizio. I develop principled machine learning methods for structured data: sets, graphs, sequences, and their combinations. I care about models that respect the symmetries of their data, are provably expressive, and scale. Increasingly, I apply these ideas to the computational traces of foundation models, such as activations and attention maps, which I treat as structured data in their own right. The goal is to make these systems more reliable, for example by detecting hallucinations from a model’s internals.

I am a Postdoctoral Fellow at Technion with Prof. Haggai Maron, and will join CISPA as Faculty in January 2027. Before that, I obtained my PhD at Imperial College London with Prof. Michael Bronstein, working on expressive Graph Neural Networks, and was a Machine Learning Researcher at Twitter Cortex (2019–2023), which I joined through the acquisition of Fabula AI. I also co-founded and co-organise GLOW, a monthly reading group on graph learning. -->

Hi, I am Fabrizio. My research interests revolve around the design and study of principled and effective learning methods over _structured data_. I am interested in domains with inherent symmetries or relational organisation (e.g., sets, graphs, complexes, sequences and combinations thereof), and in learning approaches designed to leverage this structure, (for example through _equivariance_), while retaining _expressiveness_.

Recently, I have been particularly interested in how this research extends to the computational traces of Large Language Models (LLMs), such as activations and attention maps: I treat them as structured data in their own right, and learn from them to detect and mitigate failure modes such as hallucinations. I am also exploring applications to biology, and nucleic acids in particular.

I am currently a Postdoctoral Fellow at [Technion](https://www.technion.ac.il/en/), working with [Prof. Haggai Maron](https://haggaim.github.io/), and in January 2027 I will join [CISPA](https://cispa.de/) as Faculty to start my research group. Previously, I obtained a PhD in Computing from [Imperial College London](https://www.imperial.ac.uk/) under the supervision of [Prof. Michael Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/), and I have been a Machine Learning Researcher at Twitter Cortex from 2019 – acquisition of [Fabula AI](https://en.wikipedia.org/wiki/Fabula_AI) – to early 2023. I am also one of the co-founders and co-organisers of the [GLOW (Graph Learning on Wednesdays)](https://sites.google.com/view/graph-learning-on-weds) reading group.

<hr>

### News

{% include timeline.html %}

<hr>

### Selected Publications

{% include work_list.html %}
