# Sales Call Objection Pattern Extractor

**Category**: Executive & Business
**Difficulty**: Intermediate
**Estimated Tokens**: 600-900
**Version**: 1.0.0

## Description

Extract and categorize all objections from sales call transcripts with detailed analysis of rep responses and suggested improvements. Ideal for sales managers analyzing patterns across multiple calls and developing objection-handling training.

## The Prompt

```text
Analyze this sales call transcript to extract and categorize all objections raised by the prospect.

For each objection found:

1. **Objection Category**:
   - Price/Budget
   - Timing/Urgency
   - Authority/Decision Process
   - Need/Fit
   - Trust/Risk
   - Competition
   - Status Quo/Inertia

2. **Exact Quote**: The prospect's words verbatim

3. **Context**: What prompted this objection

4. **Rep's Response**: How the salesperson addressed it

5. **Response Effectiveness**:
   - Score 1-5 (1=made it worse, 5=fully resolved)
   - What worked in the response
   - What could be improved

6. **Suggested Response Script**:
   A better way to handle this objection, using the prospect's own language and concerns

At the end, provide:
- **Objection Summary**: Count by category
- **Most Critical Objection**: The one most likely to kill this deal
- **Coaching Priority**: The objection type this rep needs most practice handling

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---

TRANSCRIPT:
[PASTE YOUR SALES CALL TRANSCRIPT HERE]
```

## Best Practices

**Categorize consistently:** Use the standard objection categories for cross-call pattern analysis.

**Quote exactly:** Verbatim quotes enable training with real prospect language.

**Rate honestly:** Accurate effectiveness ratings help identify coaching priorities.

**Provide alternatives:** Every objection analysis should include an improved response script.

## Use Cases

- **Sales training** - Build objection-handling playbooks from real calls
- **Pattern analysis** - Identify common objections across your pipeline
- **Rep coaching** - Targeted feedback on specific objection types
- **Battlecard updates** - Refresh competitive responses based on actual conversations

## Example Output

### Objection Analysis

**Objection #1**
- **Category**: Price/Budget
- **Quote**: "That's more than we budgeted for this quarter"
- **Context**: After pricing discussion at 18:45
- **Rep Response**: "I understand budget constraints. Let me show you the ROI calculation..."
- **Effectiveness**: 3/5 - Jumped to ROI too quickly without exploring budget timeline
- **Suggested Response**: "I hear you on budget. Help me understand—is this a 'not this quarter' situation or a 'not at this price point' situation? That'll help me see if there's a path forward."

### Summary
- Price/Budget: 2 objections
- Competition: 1 objection
- Timing: 1 objection

**Most Critical**: Budget objection—unresolved and blocking next steps
**Coaching Priority**: Price objection handling—rep tends to pitch ROI before understanding the real concern

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide-2026#prompt-2-objection-pattern-extractor)
