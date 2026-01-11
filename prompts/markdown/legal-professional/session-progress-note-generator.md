# Session Progress Note Generator

**Category**: Legal Professional (Healthcare Documentation)
**Difficulty**: Intermediate
**Source**: [Therapy Session Transcription Guide](https://brasstranscripts.com/blog/therapy-session-transcription-privacy-documentation-guide)

## Description

Creates clinical progress notes from therapy session transcripts using SOAP format (Subjective, Objective, Assessment, Plan). Designed for mental health professionals who need efficient, compliant documentation.

## Use Cases

- Clinical progress note documentation
- Therapy session summary creation
- Insurance documentation requirements
- Treatment progress tracking
- Supervision preparation

## The Prompt

```text
Create a clinical progress note from this therapy session transcript. Follow standard documentation requirements while protecting patient privacy.

SESSION DETAILS:
- Session type: [Individual/Couples/Family/Group]
- Session length: [50 minutes/90 minutes/other]
- Treatment modality: [CBT/DBT/Psychodynamic/Integrative/etc.]

Generate a progress note including:

1. **Subjective** (Client presentation)
   - Affect and mood observed
   - Key concerns or topics raised
   - Significant statements (paraphrase, don't quote extensively)

2. **Objective** (Observable data)
   - Mental status observations
   - Behavioral observations during session
   - Changes from previous sessions

3. **Assessment** (Clinical interpretation)
   - Progress toward treatment goals
   - Clinical impressions
   - Risk factors if relevant (suicidal ideation, safety concerns)

4. **Plan** (Next steps)
   - Interventions to continue
   - Homework or between-session tasks
   - Goals for next session
   - Recommended changes to treatment plan

FORMAT REQUIREMENTS:
- 150-400 words total
- Clinical language appropriate for medical record
- No direct quotes longer than one sentence
- Focus on treatment-relevant content only

TRANSCRIPT:
[Paste your session transcript here]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---
```

## Expected Output

The prompt generates a SOAP-formatted progress note including:
- Subjective observations of client presentation
- Objective behavioral and mental status data
- Clinical assessment and treatment progress
- Plan for future sessions and interventions

## Customization Tips

- Adjust word count for your documentation requirements
- Add specific treatment goal tracking for your approach
- Include diagnosis-specific assessment criteria
- Modify for couples/family therapy formats

## Privacy Considerations

- Transcripts should be deleted after note creation
- Do not use as psychotherapy notes (HIPAA distinction)
- Store completed notes according to HIPAA requirements
- Ensure patient consent for recording was obtained

## Related Prompts

- [Supervision Case Summary](./supervision-case-summary.md) - Prepare session material for supervision
- [Interview Thematic Analysis](../general-content/interview-thematic-analysis.md) - Research interview analysis

## Resources

- [Therapy Session Transcription Guide](https://brasstranscripts.com/blog/therapy-session-transcription-privacy-documentation-guide)
- [BrassTranscripts Upload](https://brasstranscripts.com)
