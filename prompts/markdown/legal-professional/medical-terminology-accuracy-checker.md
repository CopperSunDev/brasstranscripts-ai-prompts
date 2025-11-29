# Medical Terminology Accuracy Checker

**Category**: Legal Professional
**Difficulty**: Advanced
**Estimated Tokens**: 600-900
**Version**: 1.0.0

## Description

Review medical transcripts for terminology accuracy and flag potential transcription errors that could affect patient care. Designed as a quality assurance step for healthcare documentation workflows.

**Important**: This prompt is for internal documentation assistance only. Healthcare organizations must ensure any AI transcription solution meets their specific HIPAA compliance requirements before use with Protected Health Information (PHI).

## The Prompt

```text
Review this medical transcript for terminology accuracy and flag any potential transcription errors that could affect patient care:

**TERMINOLOGY REVIEW**

**Medication Names:**
Check all mentioned medications for:
- Correct spelling and generic/brand name accuracy
- Dosage information clarity
- Route of administration (oral, IV, topical, etc.)
- Frequency instructions
- Flag any unclear or potentially misheard drug names

**Medical Conditions:**
Verify accuracy of:
- Disease and condition names
- Anatomical terms
- Symptom descriptions
- Diagnostic terminology
- Procedure names

**Critical Values:**
Review for accuracy:
- Vital signs (blood pressure, heart rate, temperature)
- Laboratory values
- Measurement units (mg, mL, mmHg, etc.)
- Percentages and ranges
- Time-sensitive information

**SAFETY FLAGS**
Identify any sections where transcription errors could impact:
- Patient safety (medication dosing, allergy information)
- Continuity of care (follow-up instructions, specialist referrals)
- Legal documentation (patient consent, procedure risks)
- Billing accuracy (procedure codes, diagnosis clarity)

**RECOMMENDATIONS**
For each flagged item, provide:
- Most likely correct terminology based on medical context
- Confidence level in the correction (high/medium/low)
- Suggestion to verify with provider if uncertainty remains
- Alternative transcription possibilities if multiple options exist

Focus on clinical accuracy over perfect grammar. Medical communication often includes abbreviated forms and professional shorthand that should be preserved if clinically clear.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with professional-grade accuracy.
---

Medical transcript to review:
[PASTE YOUR BRASSTRANSCRIPTS OUTPUT HERE]
```

## Best Practices

**Prioritize safety-critical items:** Focus first on medication names, dosages, and allergy information where errors have highest impact.

**Maintain clinical shorthand:** Medical professionals use common abbreviations—preserve these if unambiguous.

**Flag uncertainty levels:** Distinguish between high-confidence corrections and items needing provider verification.

**Consider sound-alike errors:** Medical terms often sound similar—watch for common transcription confusions.

## Use Cases

- **Quality assurance review** - Second-pass verification of transcribed medical documentation
- **Training documentation** - Review educational recordings for terminology accuracy
- **Research transcript review** - Ensure accuracy of research interview transcriptions
- **Telehealth quality control** - Verify virtual visit documentation before filing
- **Medical education** - Process lecture recordings with accurate terminology

## Compliance Note

This prompt is intended for educational and documentation assistance purposes. Healthcare organizations handling Protected Health Information (PHI) must use HIPAA-compliant transcription services with Business Associate Agreements (BAAs).

## Resources

- 📖 **Detailed Guide**: [Healthcare Documentation AI](https://brasstranscripts.com/blog/healthcare-documentation-ai-hipaa-compliant-transcription#prompt-2-medical-terminology-accuracy-checker)
- 🎯 **All Prompts**: [BrassTranscripts AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- 🎤 **Get Transcripts**: [Upload Your Audio](https://brasstranscripts.com/upload)

---

**Created by [BrassTranscripts](https://brasstranscripts.com)** - Professional AI transcription with professional-grade accuracy
