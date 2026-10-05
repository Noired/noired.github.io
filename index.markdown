---
layout: default
title: Home
---

# _{{ site.title | default: site.github.repository_name }}_

<p style="margin-top:-12px;margin-bottom:12px;color:#333">
	<span style="white-space:nowrap"><b>Postdoc</b> &middot; Technion</span>
	<span style="color:#bbb;margin:0 6px">|</span>
	<b>Incoming Faculty</b> &middot; CISPA Helmholtz Center for Information Security (Jan 2027)
</p>

<hr>

<div class="announce">
	<p class="announce-title">Hiring: two PhD students and a postdoc</p>
	<p>I am building a research group at CISPA on machine learning for structured data and reliable foundation models.</p>
	<a class="cta" href="{{ "/join" | relative_url }}">How to join &rarr;</a>
</div>

<!-- Hey! I am Fabrizio. I am a Postdoctoral Fellow at Technion, working with [Prof. Haggai Maron](https://haggaim.github.io/) on _Geometric Deep Learning_.

My interests revolve around _principled and effective learning over structured data_, with particular emphasis on the roles of _Equivariance_ and _Expressiveness_. Recently, I've been working on architectures to learn from (structured) computational traces of Large Language Models (LLMs) for the automated detection of problematic behavioral patterns such as hallucinations. I also extensively work on methods for learning on graphs, with a focus on designing efficient and expressive Graph Neural Networks (GNNs).

Speaking of graphs, I am also one of the co-founders and co-organisers of the [GLOW (Graph Learning on Wednesdays)](https://sites.google.com/view/graph-learning-on-weds) reading group.

Previously, I have obtained a PhD in Computing from Imperial College London under the supervision of Prof. Michael Bronstein, with my research focussing on overcoming the intrinsic representational limits of GNNs. I have explored extensions of message-passing schemes that can capture non-trivial meso-scale topological patterns in networks, and equivariance to symmetries as an overarching design principle to design provably expressive architectures.

In the past, I have conducted more applied research on Machine Learning approaches for problems in the realm of Computational Biology and Bioinformatics, specifically, drug repurposing and epigenetic gene expression regulation.

I have also been a Machine Learning Researcher at Twitter Cortex from 2019 – acquisition of [Fabula AI](https://en.wikipedia.org/wiki/Fabula_AI) – to early 2023. -->

Hi! I am Fabrizio. I develop principled machine learning methods for structured data: sets, graphs, sequences, and their combinations. I care about models that respect the symmetries of their data, are provably expressive, and scale. Increasingly, I apply these ideas to the computational traces of foundation models, such as activations and attention maps, which I treat as structured data in their own right. The goal is to make these systems more reliable, for example by detecting hallucinations from a model's internals.

I am a Postdoctoral Fellow at [Technion](https://www.technion.ac.il/en/) with [Prof. Haggai Maron](https://haggaim.github.io/), and will join [CISPA](https://cispa.de) as Faculty in January 2027. Before that, I obtained my PhD at [Imperial College London](https://www.imperial.ac.uk) with [Prof. Michael Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/), working on expressive Graph Neural Networks, and was a Machine Learning Researcher at Twitter Cortex (2019–2023), which I joined through the acquisition of Fabula AI. I also co-founded and co-organise [GLOW](https://sites.google.com/view/graph-learning-on-weds), a monthly reading group on graph learning.

<hr>

### News

{% include timeline.html %}

<hr>

### Selected Publications

{% include work_list.html %}
