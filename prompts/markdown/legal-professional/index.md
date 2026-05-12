---
layout: default
title: "Legal Professional AI Prompts"
description: "11 AI prompts for deposition summaries, case-file analysis, discovery prep, and contract review from recorded legal proceedings."
canonical_url: https://brasstranscripts.com/ai-prompt-guide#legal-professional
---

# Legal Professional AI Prompts

11 prompts for attorneys, paralegals, and legal-ops teams working with depositions, client interviews, hearings, and recorded calls.

These prompts assume a clean transcript with reliable speaker attribution — see [legal transcription with speaker identification](https://brasstranscripts.com/legal-transcription?utm_source=github-pages&utm_medium=referral&utm_campaign=prompts-legal) for the source material these prompts are designed to process.

## All Prompts in this Category

<ul>
{% assign prompts = site.pages | where_exp: "p", "p.path contains 'prompts/markdown/legal-professional/'" | where_exp: "p", "p.name != 'index.md'" %}
{% for prompt in prompts %}
  <li><a href="{{ prompt.url | relative_url }}">{{ prompt.name | replace: '.md', '' | replace: '-', ' ' | capitalize }}</a></li>
{% endfor %}
</ul>

[← Back to all categories]({{ '/' | relative_url }})
