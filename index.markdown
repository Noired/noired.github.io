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
	<p>I am starting a research group at CISPA in January 2027, working on machine learning for structured data and on the internals of foundation models, towards safer and more reliable AI. Apply by 15 November for full consideration.</p>
	<a class="cta" href="{{ "/join" | relative_url }}">How to join &rarr;</a>
</div>

Hi, I am Fabrizio. My research interests revolve around the design and study of principled and effective learning methods over _structured data_. I am interested in domains with inherent symmetries or relational organisation (e.g., sets, graphs, complexes, sequences and combinations thereof), and in learning approaches designed to leverage this structure, for example through _equivariance_, while retaining _expressiveness_.

Recently, I have been particularly interested in how this research extends to Large Language Models (LLMs) and neural networks more generally. I treat the artefacts they produce, such as activations and attention maps, as structured data in their own right, and learn from them to understand these models and to detect and mitigate failure modes such as hallucinations. I am also exploring applications to biology, and nucleic acids in particular.

I am currently a Postdoctoral Fellow at [Technion](https://www.technion.ac.il/en/), working with [Prof. Haggai Maron](https://haggaim.github.io/), and in January 2027 I will join [CISPA](https://cispa.de/) as Faculty to start my research group. Previously, I obtained a PhD in Computing from [Imperial College London](https://www.imperial.ac.uk/) under the supervision of [Prof. Michael Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/), and I have been a Machine Learning Researcher at Twitter Cortex from 2019 – acquisition of [Fabula AI](https://en.wikipedia.org/wiki/Fabula_AI) – to early 2023. I am also one of the co-founders and co-organisers of the [GLOW (Graph Learning on Wednesdays)](https://sites.google.com/view/graph-learning-on-weds) reading group, and a co-organiser of the NeurIPS 2026 workshop on [Neural Network Artifacts as a New Data Modality](https://artifactsasdata.org/).

<hr>

### News

{% include timeline.html %}

<hr>

### Selected Publications

{% include work_list.html %}
