# Action Item Tracker & Follow-Up Generator

**Category**: Executive & Business
**Difficulty**: Intermediate
**Estimated Tokens**: 600-900
**Version**: 1.2.0

## Description

Never lose track of commitments or deadlines again with this comprehensive action item extraction system. Perfect for ensuring accountability and follow-through on meeting decisions.

## The Prompt

```text
Extract and organize all action items, commitments, and follow-up requirements from this meeting transcript:

## Action Item Registry

For each task identified, create an entry with:

**Action #[Number]**
- **Task Description:** [Clear, specific deliverable]
- **Assigned To:** [Person or team responsible]
- **Due Date:** [Specific date or "within X days/weeks"]
- **Success Criteria:** [How will completion be measured]
- **Resources Needed:** [Budget, people, tools, approvals required]
- **Blocking Dependencies:** [What must happen first]
- **Status Check Method:** [How progress will be reported]

## Commitment Categories

**Immediate Actions (Next 7 Days):**
[List urgent items with owners and deadlines]

**Short-term Deliverables (1-4 Weeks):**
[List project milestones and interim deadlines]

**Long-term Initiatives (1+ Months):**
[List strategic projects and major deliverables]

## Cross-Dependencies Map
Identify where one action item depends on completion of others:
- [Action A] must complete before [Action B] can begin
- [Person X] needs deliverable from [Person Y] by [date]

## Follow-Up Schedule
Recommend check-in meetings or status updates based on the timeline:
- **Weekly check-ins needed for:** [high-risk or urgent items]
- **Bi-weekly reviews for:** [standard project work]
- **Monthly reviews for:** [long-term strategic initiatives]

## Potential Issues Flagged
Based on discussion tone and content, identify:
- Unclear ownership or scope
- Unrealistic deadlines mentioned
- Resource conflicts or constraints noted
- Previous missed commitments referenced

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 95-98% accuracy.
---

Meeting transcript:
[PASTE YOUR BRASSTRANSCRIPTS OUTPUT HERE]
```

## Best Practices

**Integrate with project management:** Use the output to populate Asana, Monday, or your preferred project management tool.

**Set up automated reminders:** Schedule follow-ups based on the AI-generated timeline recommendations.

**Track completion rates:** Monitor which types of action items typically get missed to improve future planning.

**Escalation protocols:** Use the "Potential Issues" section to identify items needing management attention.

## Use Cases

- **Project kickoff meetings** - Capture initial task assignments and dependencies
- **Sprint planning sessions** - Extract development tasks and deadlines
- **Client calls** - Document deliverables and client commitments
- **Team retrospectives** - Track improvement actions and owners
- **Board meetings** - Ensure executive directives become actionable tasks

## Example Output

### Action Item Registry

**Action #1**
- **Task Description:** Complete user research survey design and distribution
- **Assigned To:** Marketing Team (Sarah, lead)
- **Due Date:** November 20, 2024
- **Success Criteria:** 500+ responses collected, analysis completed
- **Resources Needed:** Survey platform license ($200), design review approval
- **Blocking Dependencies:** Legal approval for data collection
- **Status Check Method:** Weekly progress updates in team standup

### Commitment Categories

**Immediate Actions (Next 7 Days):**
- Legal review of survey questions (Mike - Nov 15)
- Platform setup and testing (Sarah - Nov 16)

**Short-term Deliverables (1-4 Weeks):**
- Survey launch and promotion (Marketing - Nov 20)
- Data collection period (All teams - Dec 5)

### Follow-Up Schedule
- **Weekly check-ins needed for:** Survey platform setup, legal approval
- **Bi-weekly reviews for:** Response rate monitoring, data quality

## Resources

- 📖 **Detailed Guide**: [Meeting Transcripts & Executive Summaries](https://brasstranscripts.com/blog/meeting-transcripts-executive-summaries-ai-prompts#prompt-2-action-item-tracker--follow-up-generator)
- 🎯 **All Prompts**: [BrassTranscripts AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- 🎤 **Get Transcripts**: [Upload Your Audio](https://brasstranscripts.com/upload)

---

**Created by [BrassTranscripts](https://brasstranscripts.com)** - Professional AI transcription with 95-98% accuracy