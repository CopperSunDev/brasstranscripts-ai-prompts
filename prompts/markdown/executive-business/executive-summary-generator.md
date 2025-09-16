# Executive Summary Generator

**Category**: Executive & Business
**Difficulty**: Intermediate
**Estimated Tokens**: 500-800
**Version**: 1.2.0

## Description

Transform any meeting recording into a boardroom-ready executive summary that captures decisions, implications, and next steps. Perfect for C-level executives who need strategic intelligence without conversation details.

## The Prompt

```text
Analyze this meeting transcript and create a concise executive summary formatted for C-level review:

## Executive Summary
Write 2-3 sentences that capture: the meeting's strategic purpose, key decisions reached, and primary outcomes achieved.

## Critical Decisions Made
List each major decision with:
- The specific decision
- Who made it (or voting outcome)
- Strategic rationale given
- Implementation timeline if mentioned

## Action Items & Accountability
For each action item identified:
- **Task:** [specific deliverable]
- **Owner:** [responsible person/team]
- **Deadline:** [specific date or timeframe]
- **Dependencies:** [what needs to happen first]

## Strategic Implications
Analyze how decisions impact:
- Business objectives and KPIs
- Resource allocation (budget, people, time)
- Risk profile and mitigation needs
- Competitive positioning

## Risk Assessment
Identify any concerns, challenges, or potential issues mentioned:
- **Risk:** [specific concern]
- **Impact:** [potential consequences]
- **Mitigation:** [proposed solutions or next steps]

## Immediate Leadership Actions Required
List any decisions or approvals needed from leadership within the next 30 days.

Please maintain strict factual accuracy and avoid interpretations not directly supported by the discussion.

Meeting transcript:
[PASTE YOUR BRASSTRANSCRIPTS OUTPUT HERE]
```

## Best Practices

**Customize for your organization:** Modify the format to match your company's reporting standards and executive preferences.

**Use speaker identification:** If you have JSON format with speaker labels, reference specific executives by name to add accountability and context.

**Include confidence indicators:** When the AI identifies unclear decisions or incomplete action items, flag them for clarification.

**Link to strategy:** Always connect meeting outcomes to broader business objectives executives care about.

## Use Cases

- **Board meeting preparation** - Distill department updates into strategic highlights
- **Cross-functional alignment** - Extract commitments and dependencies between teams
- **Investor update compilation** - Gather key metrics and decisions across multiple meetings
- **Crisis response documentation** - Capture critical decisions during emergency sessions

## Example Output

### Executive Summary
The Q4 planning meeting focused on budget reallocation and product launch timeline adjustments. Leadership approved a $200K shift from marketing to engineering and delayed the product launch by 6 weeks to ensure quality standards.

### Critical Decisions Made
- **Budget Reallocation**: Approved $200K transfer from marketing to engineering (CEO approval, based on quality concerns)
- **Launch Delay**: Product launch moved from Dec 15 to Jan 31 (unanimous vote, quality assurance priority)

### Action Items & Accountability
- **Task**: Revised engineering timeline with milestones
- **Owner**: Engineering Director (Sarah)
- **Deadline**: November 15
- **Dependencies**: Budget transfer completion

### Strategic Implications
- Risk mitigation prioritized over time-to-market
- Q4 revenue projections need revision
- Competitive launch window may be missed

## Resources

- 📖 **Detailed Guide**: [Meeting Transcripts & Executive Summaries](https://brasstranscripts.com/blog/meeting-transcripts-executive-summaries-ai-prompts#prompt-1-executive-summary-generator)
- 🎯 **All Prompts**: [BrassTranscripts AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- 🎤 **Get Transcripts**: [Upload Your Audio](https://brasstranscripts.com/upload)

---

**Created by [BrassTranscripts](https://brasstranscripts.com)** - Professional AI transcription with 95-98% accuracy