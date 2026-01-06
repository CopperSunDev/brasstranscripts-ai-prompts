# Content Creator Transcription Budget Planner

**Category**: General Content
**Difficulty**: Beginner
**Estimated Tokens**: 400-600
**Version**: 1.0.0

## Description

Plan transcription budgets for content creators with variable production schedules. Calculates costs across slow, average, and busy month scenarios to identify services that handle production variability without wasting money on unused subscription capacity.

## The Prompt

```text
Plan my transcription budget as a content creator with variable output.

MY CONTENT PRODUCTION:
- Primary platform: [YOUTUBE/PODCAST/COURSES/MIXED]
- Content pieces per month: [RANGE, e.g., "2-6"]
- Average content length: [MINUTES]
- Busiest month (last year): [PIECES] pieces, [TOTAL HOURS] audio
- Slowest month (last year): [PIECES] pieces, [TOTAL HOURS] audio

WHAT I USE TRANSCRIPTS FOR:
- [ ] YouTube captions/subtitles
- [ ] Blog post creation
- [ ] Social media quotes
- [ ] Show notes
- [ ] Course materials
- [ ] SEO optimization
- [ ] Accessibility compliance

CALCULATE THREE SCENARIOS:

**Scenario A: Slow Month**
- Minimum expected content
- Calculate costs across services

**Scenario B: Average Month**
- Typical content volume
- Calculate costs across services

**Scenario C: Busy Month**
- Maximum expected content
- Calculate costs across services

FOR EACH SCENARIO, COMPARE:
1. BrassTranscripts (pay-per-use): $6/file over 15 min
2. Otter Pro ($16.99/mo): 1,200 min included
3. Descript Creator ($15/mo): 10 hours included
4. Descript Pro ($30/mo): 30 hours included

ANALYSIS:
- Which service wins in each scenario?
- What's my expected annual cost with variable production?
- At what consistent volume does subscription beat pay-per-use?
- Hidden costs for my specific use cases (SRT export, speaker ID, etc.)

RECOMMENDATION:
- Best primary service for my variability pattern
- Backup option for overflow months
- Annual budget range to plan for

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## Best Practices

**Use historical data:** Input actual past production numbers, not optimistic projections.

**Test all scenarios:** Variable creators often waste money by planning only for busy months.

**Check format needs:** SRT/VTT for YouTube captions may have additional costs on some services.

**Annual perspective:** Monthly winner may differ from annual winner when variability is high.

## Use Cases

- **YouTube creators** - Budget for caption and repurposing workflows
- **Podcasters** - Plan for seasonal production variations
- **Course creators** - Project costs for course production bursts
- **Multi-platform creators** - Optimize across varied content types

## Example Output

**Input**: YouTube creator, 2-6 videos/month, 20 min average, busiest month 8 videos (160 min), slowest month 2 videos (40 min)

**Scenario A: Slow Month (2 videos, 40 min)**
- BrassTranscripts: 2 × $6 = $12
- Otter Pro: $16.99 (4% utilization)
- **Winner: BrassTranscripts**

**Scenario B: Average Month (4 videos, 80 min)**
- BrassTranscripts: 4 × $6 = $24
- Otter Pro: $16.99 (7% utilization)
- **Winner: Otter Pro** (but 93% waste)

**Scenario C: Busy Month (8 videos, 160 min)**
- BrassTranscripts: 8 × $6 = $48
- Otter Pro: $16.99 (13% utilization)
- **Winner: Otter Pro**

**Annual Analysis** (6 slow, 4 average, 2 busy months):
- BrassTranscripts: ~$264
- Otter Pro: $204 (but paying for unused capacity)

**Recommendation**: For highly variable production, BrassTranscripts reduces waste despite higher per-unit cost.

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/transcription-api-pricing-calculator-prompts-2026#the-content-creator-calculator)
