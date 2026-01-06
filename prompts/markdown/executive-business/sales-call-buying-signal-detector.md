# Sales Call Buying Signal Detector

**Category**: Executive & Business
**Difficulty**: Intermediate
**Estimated Tokens**: 500-800
**Version**: 1.0.0

## Description

Identify verbal cues indicating purchase intent from sales call transcripts. Detects strong and moderate buying signals, highlights missed opportunities where reps didn't capitalize on signals, and recommends next steps based on signal strength.

## The Prompt

```text
Review this sales call transcript and identify all buying signals—verbal cues indicating the prospect is moving toward a purchase decision.

## STRONG BUYING SIGNALS
Statements indicating high purchase intent:
- Asking about implementation/onboarding
- Discussing specific use cases for their team
- Inquiring about pricing, contracts, or terms
- Mentioning timeline urgency
- Asking "what's next?"

Quote each signal and rate its strength.

## MODERATE BUYING SIGNALS
Statements indicating growing interest:
- Asking detailed technical questions
- Sharing internal challenges the solution addresses
- Requesting references or case studies
- Involving additional stakeholders

## MISSED OPPORTUNITIES
Moments where buying signals appeared but the rep didn't capitalize:
- Signal that was ignored
- What the rep said instead
- Better response that would have advanced the deal

## BUYING SIGNAL TIMELINE
Map when signals appeared during the call. Early signals indicate strong fit; late signals may indicate the rep successfully built value.

## RECOMMENDED NEXT STEPS
Based on the buying signals detected:
- Is this prospect ready for a proposal?
- What additional information would accelerate the decision?
- Who else needs to be involved?

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---

TRANSCRIPT:
[PASTE YOUR SALES CALL TRANSCRIPT HERE]
```

## Best Practices

**Distinguish signal strength:** Not all buying signals are equal—implementation questions are stronger than feature questions.

**Track timing:** Early signals suggest strong fit; signals appearing only after extensive pitching may be weaker.

**Identify misses:** The most valuable coaching insight is often where reps failed to capitalize on clear signals.

**Recommend action:** Every analysis should conclude with specific next steps.

## Use Cases

- **Deal acceleration** - Identify when to move to proposal stage
- **Rep coaching** - Train reps to recognize and respond to buying signals
- **Forecast validation** - Cross-check rep intuition with objective signal analysis
- **Call review** - Post-call debrief to improve follow-up strategy

## Example Output

### Strong Buying Signals (3 detected)

1. **"What does onboarding look like?"** (21:15)
   - Strength: Strong
   - Indicates: Implementation thinking, past objections resolved
   - Rep response: Good—walked through process

2. **"We need this solved before our Q2 launch"** (08:42)
   - Strength: Strong
   - Indicates: Timeline urgency, real deadline pressure
   - Rep response: Missed—didn't confirm Q2 as target close date

### Missed Opportunities

**At 08:42**: Prospect mentioned Q2 deadline but rep continued feature demo instead of confirming timeline and next steps. Better response: "Q2 is tight—let's map out what we'd need to do to have you live by then."

### Recommendation

**Ready for proposal**: Yes—multiple strong signals detected
**Next step**: Send proposal with Q2 implementation timeline
**Involve**: Ask who else needs to review before contract

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide-2026#ai-prompt-buying-signal-detector)
