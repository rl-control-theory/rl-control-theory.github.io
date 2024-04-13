---
layout: about
title: About
permalink: /
subtitle: Workshop at the International Conference on Machine Learning (ICML) 2024 in Vienna, Austria

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

Despite rapid advances in machine learning, solving large-scale stochastic dynamic programming problems remains a significant challenge. The combination of neural networks with RL has opened new avenues for algorithm design, but the lack of theoretical guarantees of these approaches hinders their applicability to high-stake problems traditionally addressed using control theory, such as online supply chain optimization, industrial automation, and adaptive transportation systems. This workshop focuses on recent advances in developing a learning theory of decision (control) systems, that builds on techniques and concepts from two communities that have had limited interactions despite their shared target: reinforcement learning and control theory.
<br><br>

{% comment %}
{% if page.news and site.announcements.enabled %}
  <h2>
    <a href="{{ '/news/' | relative_url }}" style="color: inherit">News</a>
  </h2>
  {% include news.liquid limit=true %}
{% endif %}
<br>
{% endcomment %}

## Confirmed Speakers
{% assign sorted_speakers = site.speakers | sort: "importance" %}
<div style="margin-top: 20px; display: flex; gap: 20px; flex-wrap: wrap; justify-content: center">
  {% for speaker in sorted_speakers %}
    {% include speakers.liquid %}
  {% endfor %}
</div>
<br><br>

## Organizers
{% assign sorted_organizers = site.organizers | sort: "importance" %}
<div style="margin-top: 20px; display: flex; gap: 20px; flex-wrap: wrap; justify-content: center">
  {% for organizer in sorted_organizers %}
    {% include organizers.liquid %}
  {% endfor %}
</div>
<br><br>

## Contact
(coming soon)
