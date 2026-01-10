# Sales Call Analyzer

**Category**: Executive & Business
**Difficulty**: Beginner
**Estimated Tokens**: 400-600
**Version**: 1.0.0

## Description

Structured summary of sales call transcripts for sales managers. Extracts call overview, key discussion points, buying signals, competitor intelligence, action items, and coaching notes in a simple, scannable format.

## The Prompt

```text
Analyze this sales call transcript and provide a structured summary for the sales manager.

Extract the following:

1. **Call Overview**
   - Prospect company and contact name (if mentioned)
   - Call duration and type (discovery, demo, negotiation, follow-up)
   - Overall sentiment (positive, neutral, concerned, negative)

2. **Key Discussion Points**
   - Main pain points discussed
   - Solutions/features presented
   - Pricing or budget discussions
   - Timeline mentioned

3. **Buying Signals**
   - Positive indicators (questions about implementation, pricing, next steps)
   - Concerns or objections raised
   - Stakeholders mentioned who need to be involved

4. **Competitor Intelligence**
   - Any competitors mentioned by name
   - Comparisons made to other solutions
   - Reasons prospect is evaluating alternatives

5. **Action Items**
   - Commitments made by sales rep
   - Commitments made by prospect
   - Agreed next steps with dates

6. **Coaching Notes**
   - What the rep did well
   - Opportunities for improvement
   - Suggested follow-up approach

TRANSCRIPT:
[Paste your transcript here]
```

## Best Practices

**Keep it scannable:** This prompt is designed for quick manager review—use the structured format consistently.

**Focus on actionable insights:** Every section should help the manager understand deal health and next steps.

**Honest assessment:** Coaching notes should be constructive and specific, not generic praise.

## Use Cases

- **Weekly pipeline reviews** - Quick summary of key calls
- **Manager call coaching** - Structured feedback format
- **Deal handoffs** - Context transfer between reps
- **CRM documentation** - Paste summary into opportunity notes

## Example Output

### Call Overview

**Company**: Acme Corp
**Contact**: Sarah Johnson, VP Operations
**Type**: Discovery call
**Sentiment**: Positive, engaged

### Key Discussion Points

- Pain point: Manual transcription taking 6+ hours per meeting
- Solution discussed: AI transcription with speaker identification
- Budget: Has Q1 budget available
- Timeline: Decision by end of month

### Buying Signals

✅ Asked about implementation timeline
✅ Inquired about team pricing
⚠️ Needs to loop in IT for security review

### Action Items

| Owner | Action | Due |
|-------|--------|-----|
| Rep | Send security documentation | Tomorrow |
| Prospect | Schedule IT review call | Next week |

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide#ai-prompt-sales-call-analyzer)
