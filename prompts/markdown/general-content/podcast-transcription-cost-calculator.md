# Podcast Transcription Cost Calculator

**Category**: General Content
**Difficulty**: Beginner
**Estimated Tokens**: 400-600
**Version**: 1.0.0

## Description

Calculate podcast transcription costs across multiple services based on episode frequency, average length, and feature requirements. Provides monthly and annual projections with effective per-hour rates to identify the best value option for your production schedule.

## The Prompt

```text
Calculate my podcast transcription costs across different services based on my production schedule.

MY PODCAST DETAILS:
- Episodes per month: [NUMBER]
- Average episode length: [MINUTES]
- Number of speakers per episode: [NUMBER]
- Do I need speaker labels? [YES/NO]
- Do I need timestamps? [YES/NO]
- Output format needed: [TXT/SRT/VTT/JSON]

CALCULATE FOR THESE SERVICES:

1. **BrassTranscripts** (Pay-per-use)
   - $2.50 flat for 0-15 min files
   - $6.00 flat for 16-120 min files
   - Includes speaker ID and all formats

2. **Otter.ai** (Subscription)
   - Free: 300 min/month
   - Pro: $16.99/month for 1,200 min
   - Business: $30/user/month for 6,000 min

3. **Temi** (Pay-per-use)
   - $0.25/minute
   - Speaker ID included

4. **Descript** (Subscription + Transcription)
   - Free: 1 hour/month
   - Creator: $15/month (10 hours)
   - Pro: $30/month (30 hours)

5. **Rev AI** (Pay-per-use)
   - $0.25/minute base
   - Speaker diarization included

FOR EACH SERVICE, PROVIDE:
- Monthly cost calculation with math shown
- Annual cost projection
- Cost per episode
- Cost per audio hour (effective rate)
- Whether my needs exceed plan limits
- Hidden costs I might miss (speaker ID add-ons, format charges, storage)

THEN RECOMMEND:
- Best option for my specific usage pattern
- Break-even point where switching services makes sense
- What would change my recommendation (more/fewer episodes, longer/shorter)

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## Best Practices

**Use actual numbers:** Input your real episode count and length, not aspirational production goals.

**Check subscription utilization:** Subscriptions only save money at 80%+ capacity utilization.

**Include all formats:** Some services charge extra for SRT/VTT—factor this into true cost.

**Plan for variability:** If your production varies month-to-month, pay-per-use may reduce risk.

## Use Cases

- **New podcast launch** - Budget planning before production starts
- **Service comparison** - Evaluate switching from current provider
- **Annual budgeting** - Project costs for fiscal planning
- **Production scaling** - Understand cost implications of increasing episode frequency

## Example Output

**Input**: 4 episodes/month, 45 minutes each, 2 speakers, need speaker labels

**BrassTranscripts**: 4 × $6.00 = **$24/month** ($288/year)
- $6/episode, $8/hour effective rate
- All formats included

**Otter Pro**: $16.99/month for 180 minutes used of 1,200 available
- **$16.99/month** ($204/year)
- Effective rate: $5.66/hour
- Warning: 85% of paid capacity unused

**Recommendation**: At 4 episodes/45 min, Otter Pro appears cheaper but wastes 85% of capacity. If production is consistent, Otter wins. If variable, BrassTranscripts reduces risk.

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/transcription-api-pricing-calculator-prompts-2026#the-podcaster-calculator)
