---
layout: default
title: "Executive & Business AI Prompts"
description: "27 AI prompts for meeting summaries, decision logs, action items, and strategic analysis from recorded business conversations."
canonical_url: https://brasstranscripts.com/ai-prompt-guide#executive-business
---

# Executive & Business AI Prompts

27 prompts for executives, project managers, and operators who need to turn meeting recordings into decisions, action items, and shareable summaries.

These work especially well with [meeting transcription that includes speaker identification](https://brasstranscripts.com/meeting-transcription-software?utm_source=github-pages&utm_medium=referral&utm_campaign=prompts-executive-business) — accurate speaker labels make every prompt in this category materially more useful.

## All Prompts in this Category

<ul>
{% assign prompts = site.pages | where_exp: "p", "p.path contains 'prompts/markdown/executive-business/'" | where_exp: "p", "p.name != 'index.md'" %}
{% for prompt in prompts %}
  <li><a href="{{ prompt.url | relative_url }}">{{ prompt.name | replace: '.md', '' | replace: '-', ' ' | capitalize }}</a></li>
{% endfor %}
</ul>

[← Back to all categories]({{ '/' | relative_url }})
