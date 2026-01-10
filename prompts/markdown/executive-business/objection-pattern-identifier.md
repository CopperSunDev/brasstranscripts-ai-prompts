# Objection Pattern Identifier

**Category**: Executive & Business
**Difficulty**: Beginner
**Estimated Tokens**: 400-550
**Version**: 1.0.0

## Description

Identify and categorize objections from sales call transcripts with effectiveness ratings and pattern analysis. Designed for sales managers reviewing calls to identify training opportunities. Simpler alternative to the comprehensive objection extractor.

## The Prompt

```text
Analyze this sales call transcript and identify all objections raised by the prospect.

For each objection:

1. **Objection Category**
   - Price/Budget
   - Timing/Urgency
   - Authority/Decision-maker
   - Need/Fit
   - Trust/Risk
   - Competition

2. **Exact Quote**: What the prospect said (verbatim from transcript)

3. **Rep's Response**: How did the sales rep handle it?

4. **Effectiveness Rating**:
   - Strong (objection resolved, conversation moved forward)
   - Adequate (addressed but not fully resolved)
   - Weak (deflected, ignored, or poorly handled)

5. **Recommended Response**: What would a better response sound like?

After listing all objections, provide:

**Pattern Analysis**:
- Most common objection type
- Objections that weren't addressed
- Overall objection handling score (1-10)
- Top 3 coaching priorities for this rep

TRANSCRIPT:
[Paste your transcript here]
```

## Best Practices

**Use exact quotes:** Verbatim prospect language makes training more realistic and actionable.

**Be honest on ratings:** Accurate effectiveness ratings help identify real coaching needs.

**Focus on patterns:** The summary analysis is often more valuable than individual objections.

## Use Cases

- **Sales coaching** - Targeted feedback on objection handling skills
- **Training development** - Build playbooks from real objection patterns
- **Team analysis** - Compare objection handling across reps
- **Deal reviews** - Understand why deals stall or progress

## Example Output

### Objections Found

**Objection #1**
- **Category**: Price/Budget
- **Quote**: "That's a bit more than we were planning to spend"
- **Rep Response**: "I understand. Let me show you how the ROI typically works out..."
- **Rating**: Adequate - addressed but didn't probe deeper on budget constraints
- **Better Response**: "Help me understand your budget situation—is this a timing issue or a total cost concern? That helps me see what options we have."

**Objection #2**
- **Category**: Authority/Decision-maker
- **Quote**: "I'd need to run this by my manager before committing"
- **Rep Response**: "Of course, would it help if I joined that conversation?"
- **Rating**: Strong - offered to help advance the deal

### Pattern Analysis

- **Most common**: Price/Budget (2 of 3 objections)
- **Unaddressed**: None
- **Overall score**: 7/10
- **Coaching priorities**:
  1. Deeper discovery on budget objections before jumping to ROI
  2. Earlier qualification on decision-making process
  3. More probing questions before presenting solutions

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/sales-call-transcription-ai-analysis-guide#ai-prompt-objection-pattern-identifier)
