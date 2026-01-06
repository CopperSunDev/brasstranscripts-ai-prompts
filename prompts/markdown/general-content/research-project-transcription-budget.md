# Research Project Transcription Budget Calculator

**Category**: General Content
**Difficulty**: Beginner
**Estimated Tokens**: 500-700
**Version**: 1.0.0

## Description

Calculate total transcription budget for research projects with fixed interview counts. Compares AI transcription, human transcription, and hybrid approaches with timeline feasibility and risk assessment for academic and professional research.

## The Prompt

```text
Calculate total transcription budget for my research project.

PROJECT DETAILS:
- Total number of interviews: [NUMBER]
- Average interview length: [MINUTES]
- Interview format: [IN-PERSON / PHONE / VIDEO CALL]
- Number of participants per interview: [NUMBER]
- Do I need verbatim transcription? [YES/NO]
- Do I need speaker attribution? [YES/NO]
- Timeline: [DAYS/WEEKS to complete all transcription]
- Budget constraint: [AMOUNT or "flexible"]

SPECIAL REQUIREMENTS:
- Language(s): [LIST LANGUAGES]
- Technical terminology: [FIELD/DISCIPLINE]
- Confidentiality level: [STANDARD / IRB-COMPLIANT / HIPAA]

CALCULATE FOR:

1. **AI Transcription (BrassTranscripts)**
   - $2.50 (0-15 min) or $6.00 (16-120 min) per file
   - Include estimated review/correction time at $[HOURLY_RATE]/hour

2. **AI Transcription (Other services)**
   - Compare Otter, Temi, Rev AI at current rates

3. **Human Transcription (Rev)**
   - $1.50/minute for standard
   - $3.00/minute for verbatim
   - Include typical turnaround time

4. **Hybrid Approach**
   - AI transcription + professional review
   - Estimate total cost and time

FOR EACH OPTION, CALCULATE:
- Total transcription cost
- Estimated review/correction hours needed
- Total project cost (transcription + review time)
- Timeline feasibility
- Risk factors (accuracy for technical content, speaker attribution reliability)

PROVIDE:
- Recommended approach for my budget and timeline
- What I'd sacrifice by choosing the cheapest option
- What I'd gain by choosing the most expensive option
- Break-even analysis: at what volume does human transcription make sense?

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## Best Practices

**Include review time:** AI transcription cost is only part of the equation—factor in correction hours.

**Consider technical content:** Specialized terminology may require more review regardless of method.

**Plan for IRB requirements:** Some research protocols require specific transcription procedures.

**Budget for contingency:** Add 15-20% buffer for longer interviews or difficult audio.

## Use Cases

- **Dissertation research** - Budget planning for interview-based qualitative studies
- **Grant proposals** - Accurate transcription cost estimates for funding applications
- **Corporate research** - Market research and customer interview projects
- **Journalism** - Documentary or investigative interview transcription

## Example Output

**Input**: 25 interviews, 45 minutes each, video calls, 2 participants, speaker attribution needed, 4-week timeline

**Option 1: AI Transcription (BrassTranscripts)**
- Transcription: 25 × $6 = $150
- Review time: 25 interviews × 1.5 hrs × $25/hr = $937.50
- **Total: $1,087.50**
- Timeline: Feasible (transcription in days, review in 3 weeks)

**Option 2: Human Transcription (Rev Standard)**
- Transcription: 25 × 45 min × $1.50 = $1,687.50
- Review time: Minimal (25 × 0.5 hrs × $25 = $312.50)
- **Total: $2,000**
- Timeline: Feasible (5-7 day turnaround typical)

**Recommendation**: For dissertation research with 25 non-technical interviews, AI transcription + review saves $900+ while meeting timeline. Human transcription recommended if budget allows and review time is limited.

## Source

📖 [Original Blog Post](https://brasstranscripts.com/blog/transcription-api-pricing-calculator-prompts-2026#the-research-project-calculator)
