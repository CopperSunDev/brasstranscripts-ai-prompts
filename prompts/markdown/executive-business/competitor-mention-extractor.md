# Competitor Mention Extractor

**Category**: Executive & Business
**Difficulty**: Beginner
**Estimated Tokens**: 350-500
**Version**: 1.0.0

## Description

Extract competitor-related information from sales call transcripts. Identifies competitor names, prospect perception, feature comparisons, pricing intel, and win/loss indicators. Simpler alternative to the comprehensive competitor intelligence prompt.

## The Prompt

```text
Analyze this sales call transcript and extract all competitor-related information.

For each competitor mentioned, provide:

1. **Competitor Name**: [Name]
   - Context: Why were they mentioned?
   - Prospect's perception: Positive, negative, or neutral?
   - Features/capabilities compared
   - Pricing information shared (if any)
   - Our positioning response (what did the rep say?)

2. **Competitive Themes**
   - Common objections tied to competitors
   - Features prospects wish we had
   - Pricing expectations based on competitor quotes
   - Switching costs or concerns mentioned

3. **Win/Loss Indicators**
   - Are we ahead or behind this competitor?
   - What would tip the decision in our favor?
   - What risks losing this deal to the competitor?

If no competitors are mentioned, state "No competitor mentions found" and analyze why the prospect may not be evaluating alternatives.

TRANSCRIPT:
[Paste your transcript here]
```

## Best Practices

**Capture exact quotes:** Verbatim competitor mentions are valuable for battlecard updates.

**Note the context:** Whether they're currently using, evaluating, or just aware of a competitor matters.

**Track pricing intel:** Any competitor pricing shared is valuable market intelligence.

## Use Cases

- **Battlecard updates** - Real competitive positioning from actual calls
- **Win/loss analysis** - Understand competitive dynamics in deals
- **Product feedback** - Features prospects compare to competitors
- **Sales training** - How to position against specific competitors

## Example Output

### Competitor Mentions

**Competitor: Gong**
- Context: Prospect currently evaluating
- Perception: Positive ("good dashboard")
- Features compared: Analytics, CRM integration
- Pricing: "They quoted around $150/seat/month"
- Our response: Rep highlighted pay-per-use vs subscription model

**Competitor: Otter.ai**
- Context: Currently using
- Perception: Neutral ("works but limited")
- Reason for evaluating alternatives: Needs speaker identification

### Win/Loss Indicators

**Position**: Ahead on pricing model, behind on enterprise features
**To win**: Emphasize cost savings on selective transcription
**Risk**: If prospect prioritizes built-in analytics over cost

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide#ai-prompt-competitor-mention-extractor)
