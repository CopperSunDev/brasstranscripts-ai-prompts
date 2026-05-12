---
layout: default
title: "Content Marketing AI Prompts"
description: "25 AI prompts for turning podcasts, interviews, and recorded conversations into blog posts, social content, lead magnets, and newsletters."
canonical_url: https://brasstranscripts.com/ai-prompt-guide#content-marketing
---

# Content Marketing AI Prompts

25 prompts for podcasters, content marketers, and creators turning long-form audio into distribution-ready written content.

If you're producing a show, [podcast transcription with speaker labels](https://brasstranscripts.com/podcast-transcription-service?utm_source=github-pages&utm_medium=referral&utm_campaign=prompts-content-marketing) is the foundation — every prompt below expects a transcript with each speaker clearly identified.

## All Prompts in this Category

<ul>
{% assign prompts = site.pages | where_exp: "p", "p.path contains 'prompts/markdown/content-marketing/'" | where_exp: "p", "p.name != 'index.md'" %}
{% for prompt in prompts %}
  <li><a href="{{ prompt.url | relative_url }}">{{ prompt.name | replace: '.md', '' | replace: '-', ' ' | capitalize }}</a></li>
{% endfor %}
</ul>

[← Back to all categories]({{ '/' | relative_url }})
