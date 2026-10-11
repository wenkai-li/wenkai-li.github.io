---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I am a Research Scientist at Fujitsu Research of America. I received my M.S. from <a href="https://www.lti.cs.cmu.edu/"><span style="color: rgb(199, 46, 237);">LTI</span></a> at Carnegie Mellon University, where I was advised by Prof. <a href="https://www.lti.cs.cmu.edu/people/faculty/diab-mona.html"><span style="color: rgb(199, 46, 237);">Mona Diab</span></a>, Profs. <a href="https://maartensap.com/"><span style="color: rgb(199, 46, 237);">Maarten Sap</span></a> and <a href="https://dpfried.github.io/"><span style="color: rgb(199, 46, 237);">Daniel Fried</span></a>.

My research asks how increasingly autonomous AI systems can reason, learn, and remain reliable over long-horizon interaction. I work across agentic evaluation, post-training, AI safety, personalization, and model internals. A recurring theme in my work is to use external behavior as the primary evidence of what a system is doing, while using internal model signals when they help us understand where failures begin, which experience is worth learning from, or where intervention is most useful.

**I’m always enthusiastic about collaborating with researchers from diverse fields. If you’re interested in working together, please don’t hesitate to reach out to me.**

<h2 class="section-title">
  <span class="section-title__icon"><i class="fas fa-flask"></i></span>
  Research Interest
</h2>

**Agentic AI Safety and Evaluation:** I study how to evaluate AI systems once their behavior unfolds over long trajectories involving tools, memory, retrieval, other agents, and changing environments. I am interested in realistic evaluations that expose failures that may be delayed, contextual, or emerge from the interaction between a model and its surrounding system. I also study model-internal representations as complementary signals for locating failure onset, monitoring emerging misalignment, and selecting informative trajectories.

**Reasoning, Post-Training, and Self-Improving Agents:** I study how reasoning and exploration can be improved through process supervision, reward modeling, reinforcement learning, and trajectory-level credit assignment. One question that repeatedly comes up in my work is not simply whether a signal predicts success or failure, but where that signal should enter the learning loop. Longer term, I am interested in automated research systems that can form hypotheses, run experiments, learn from failed attempts, and gradually improve their own evaluation and training procedures.

**Human-Centered AI, Personalization, and Privacy:** I view human-centered AI fundamentally as a problem of behavioral alignment. My work began with persona modeling and personalization, where the goal was to represent users faithfully and adapt model behavior to individual preferences. This naturally led me to broader alignment questions, including contextual privacy and other human-value problems where the right behavior depends not only on what information is available, but on who is involved, why the information is being used, and the surrounding context. More broadly, I am interested in how AI systems can remain responsive to individual users while respecting the values and constraints that should govern their behavior.


# 🔥 News
- *2025.07*: &nbsp;Joined Fujitsu Research of America as a Research Scientist!