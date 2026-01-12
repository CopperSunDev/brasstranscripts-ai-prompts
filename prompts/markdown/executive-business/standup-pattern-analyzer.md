# Standup Pattern Analyzer

**Category**: Executive & Business
**Source**: [Standup Meeting Transcription: Agile Teams Guide](https://brasstranscripts.com/blog/standup-meeting-transcription-agile-teams-guide)
**Format**: Markdown

## Purpose

Extract actionable insights from a week of daily standup transcripts. Identifies recurring blockers, tracks work progress patterns, highlights team collaboration signals, and generates recommended actions for sprint retrospectives.

## The Prompt

```text
Analyze these daily standup transcripts from an agile development team. Extract patterns and actionable insights.

STANDUP TRANSCRIPTS (paste multiple days):
[Paste your week of standup transcripts here]

Please provide:

## Blocker Analysis
- List all blockers mentioned across the week
- Identify recurring blockers (mentioned 2+ days)
- Categorize blockers by type (external dependency, technical, resource, unclear requirements)
- Flag blockers that appear unresolved by week's end

## Work Progress Patterns
- Track items mentioned as "in progress" across multiple days
- Identify work that may be stuck (mentioned repeatedly without completion)
- Note completed items and who delivered them

## Team Collaboration Signals
- Instances of team members helping each other
- Knowledge sharing or pairing mentions
- Cross-functional dependencies

## Recommended Actions
Based on patterns identified:
1. Blockers requiring escalation
2. Process improvements to suggest
3. Topics for sprint retrospective
4. Recognition for completed work

## Summary Statistics
- Total unique blockers mentioned: [count]
- Blockers resolved during week: [count]
- Items completed: [count]
- Recurring patterns: [list]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---
```

## Use Cases

- **Scrum Masters**: Identify systemic blockers for escalation
- **Engineering Managers**: Spot patterns affecting team velocity
- **Agile Coaches**: Prepare retrospective discussion topics
- **Distributed Teams**: Async visibility into team progress

## Best Practices

1. **Weekly cadence**: Run this analysis every Friday or Monday—daily is overkill
2. **Include context**: Add a brief glossary of project names or acronyms before the transcripts
3. **Share results**: Bring the AI analysis to your retrospective for team discussion
4. **Iterate**: Adjust categories and focus areas based on what's useful for your team

## Output Format

The prompt generates structured markdown with:
- Categorized blocker lists with recurrence tracking
- Progress patterns with team member attribution
- Collaboration highlights
- Prioritized action recommendations
- Quantified summary statistics

---

**Related Prompts**:
- [Meeting Action Items Extractor](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/executive-business/meeting-action-items-extractor.md)
- [Meeting Executive Summary](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/executive-business/meeting-executive-summary.md)

---

*Part of the [BrassTranscripts AI Prompts Collection](https://github.com/CopperSunDev/brasstranscripts-ai-prompts)*
