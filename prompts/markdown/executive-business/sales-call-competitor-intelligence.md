# Sales Call Competitor Intelligence Extractor

**Category**: Executive & Business
**Difficulty**: Intermediate
**Estimated Tokens**: 500-800
**Version**: 1.0.0

## Description

Extract competitive intelligence from sales call transcripts including competitor mentions, prospect sentiment, evaluation criteria, and positioning opportunities. Essential for keeping battlecards current and understanding real competitive dynamics.

## The Prompt

```text
Analyze this sales call transcript for competitive intelligence. Extract all mentions of competitors, alternative solutions, and the prospect's evaluation criteria.

## DIRECT COMPETITOR MENTIONS
For each competitor named:
- Competitor name
- How they came up (prospect mentioned, rep asked, comparison requested)
- Prospect's current relationship (evaluating, using, used previously)
- Sentiment (positive, negative, neutral)
- Specific features or capabilities mentioned
- Pricing information shared

## INDIRECT COMPETITION
- Internal solutions or workarounds mentioned
- "Do nothing" indicators (status quo preference)
- Build vs buy considerations

## EVALUATION CRITERIA
What factors is the prospect using to compare options?
- Price sensitivity level
- Feature requirements (must-have vs nice-to-have)
- Integration requirements
- Timeline constraints
- Risk tolerance

## COMPETITIVE POSITIONING OPPORTUNITIES
Based on this call:
- Where we have clear advantage
- Where competitors have advantage
- Unaddressed needs our solution uniquely solves
- Messaging adjustments for this prospect

## WIN/LOSS INDICATORS
- Likelihood we win against mentioned competitors
- Key differentiators to emphasize in follow-up
- Competitive landmines to avoid

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---

TRANSCRIPT:
[PASTE YOUR SALES CALL TRANSCRIPT HERE]
```

## Best Practices

**Capture pricing intel:** Any pricing information shared about competitors is valuable market intelligence.

**Note sentiment:** How the prospect feels about competitors matters as much as what they say.

**Identify criteria:** Understanding evaluation factors helps tailor your positioning.

**Track patterns:** Aggregate intelligence across multiple calls reveals market trends.

## Use Cases

- **Battlecard updates** - Refresh competitive positioning with real conversation data
- **Win/loss analysis** - Understand why deals go to competitors
- **Product feedback** - Identify feature gaps mentioned in competitive contexts
- **Market intelligence** - Track competitor pricing and positioning changes

## Example Output

### Direct Competitor Mentions

**Competitor A** (mentioned at 12:30, 24:15)
- How raised: Prospect mentioned they're currently evaluating
- Relationship: Active evaluation
- Sentiment: Positive ("They have a good integration with our CRM")
- Features mentioned: CRM integration, reporting dashboard
- Pricing: "They quoted us around $X per user"

**Competitor B** (mentioned at 31:00)
- How raised: Rep asked about alternatives considered
- Relationship: Used previously, churned
- Sentiment: Negative ("Support was terrible")
- Reason for leaving: Response times, missing features

### Evaluation Criteria

| Criteria | Weight | Notes |
|----------|--------|-------|
| CRM integration | Must-have | Currently lacking with existing solution |
| Price | Medium | Budget-conscious but not cheapest option |
| Support quality | High | Burned by Competitor B |

### Positioning Opportunities

**Our advantage**: Support quality (address their Competitor B pain directly)
**Their advantage**: Competitor A's CRM integration
**Action**: Lead with support SLAs, prepare CRM integration roadmap

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide-2026#prompt-4-competitor-intelligence-extractor)
