---
layout: default
title: "Freelancer & General Content AI Prompts"
description: "59 AI prompts for transcript cleanup, formatting, translation prep, and creative repurposing of audio and video content."
canonical_url: https://brasstranscripts.com/ai-prompt-guide#general-content
---

# Freelancer & General Content AI Prompts

59 general-purpose prompts for freelancers, researchers, students, and anyone repurposing recorded conversations into written deliverables.

These work with any speaker-labeled transcript — the easiest way to get one is a [professional transcription service with speaker identification](https://brasstranscripts.com/transcription-service?utm_source=github-pages&utm_medium=referral&utm_campaign=prompts-general).

## All Prompts in this Category

<ul>
{% assign prompts = site.pages | where_exp: "p", "p.path contains 'prompts/markdown/general-content/'" | where_exp: "p", "p.name != 'index.md'" %}
{% for prompt in prompts %}
  <li><a href="{{ prompt.url | relative_url }}">{{ prompt.name | replace: '.md', '' | replace: '-', ' ' | capitalize }}</a></li>
{% endfor %}
</ul>

[← Back to all categories]({{ '/' | relative_url }})
