# Technical Terminology Consistency Checker

**Category**: General Content
**Difficulty**: Advanced
**Estimated Tokens**: 1500-2500
**Version**: 1.0.0

## Description

Technical discussions require precise terminology. This prompt automatically identifies and corrects industry-specific terms, jargon, acronyms, and specialized vocabulary that AI transcription commonly misinterprets due to phonetic similarity or uncommon usage patterns.

## The Prompt

```text
I have a transcript from a technical discussion that contains specialized terminology. Please help me identify terminology errors and ensure consistent, accurate usage throughout:

**Transcript:**
[PASTE YOUR TRANSCRIPT HERE]

**Industry/Domain Context:**
[SPECIFY - e.g., "Software development", "Medical/Healthcare", "Legal", "Financial", "Marketing", "Engineering", "Scientific research"]

**Known Technical Terms (if any):**
[LIST ANY SPECIFIC TERMS YOU KNOW ARE DISCUSSED - e.g., "Kubernetes, API endpoints, PostgreSQL, React hooks"]

Please analyze the transcript for technical terminology issues:

1. **Identify Likely Terminology Errors**
   - Find words or phrases that sound similar to common technical terms but are incorrect
     Examples: "communities" → "Kubernetes", "react hooks" → "React Hooks", "API in points" → "API endpoints"
   - Detect inconsistent capitalization of technical terms (e.g., "kubernetes" vs "Kubernetes", "github" vs "GitHub")
   - Flag phrases that seem out of context or nonsensical in technical discussions
   - Identify acronyms transcribed as words (e.g., "A.P.I." or "ay-pee-eye" → "API")

2. **Verify Domain-Specific Terminology**
   Based on the industry context, check for proper usage of:
   - **Software/Tech**: Framework names, programming languages, tools, methodologies
   - **Medical**: Procedures, medications, conditions, anatomical terms, abbreviations
   - **Legal**: Case names, legal terms, statutes, court names, procedural terminology
   - **Financial**: Products, regulations, metrics, institutions, accounting terms
   - **Engineering**: Components, processes, specifications, measurements, standards
   - **Scientific**: Methodologies, equipment, chemicals, species names, units

3. **Check Consistency Across Document**
   - Verify the same concept uses identical terminology throughout (not alternating synonyms)
   - Ensure consistent acronym usage (spell out first use, acronym only thereafter)
   - Check proper noun capitalization (product names, company names, technology names)
   - Verify consistent hyphenation and spacing (e.g., "e-commerce" vs "ecommerce", "front end" vs "front-end")

4. **Flag Uncertain Terms for Review**
   Mark terms that could be correct but seem unusual:
   - Low-frequency technical terms you're unsure about
   - Proper nouns (product names, company names) that may be correct but uncommon
   - Context-specific jargon that doesn't match standard industry usage
   - Terms where multiple valid spellings exist

5. **Suggest Corrections with Evidence**
   For each identified issue, provide:
   - **Current text**: Quote the problematic term with surrounding context
   - **Likely correct term**: Your best interpretation based on context and domain knowledge
   - **Reasoning**: Why this correction makes sense contextually
   - **Confidence level**: High/Medium/Low based on context clarity
   - **Find-and-replace command**: Exact command to fix all instances (if systematic error)

6. **Generate Corrected Transcript**
   Provide fully corrected version with:
   - All high-confidence terminology corrections applied
   - Medium-confidence corrections marked [corrected: original → new?]
   - Low-confidence terms flagged [verify: possible term?]
   - Summary of major changes made (e.g., "Corrected 23 instances of 'communities' to 'Kubernetes'")

7. **Create Domain-Specific Glossary**
   For future reference, list all technical terms found in this transcript:
   - **Acronyms**: Full spelling + acronym (e.g., "Application Programming Interface (API)")
   - **Proper Nouns**: Correct capitalization and spelling
   - **Technical Terms**: Standard industry spelling and formatting

**Priority**: Focus on high-frequency errors and terms critical to meaning. Flag low-confidence corrections for manual verification before applying globally.

Please return: (1) Terminology error analysis, (2) High-confidence corrections with find-and-replace commands, (3) Flagged uncertain terms, (4) Fully corrected transcript, (5) Technical glossary for this document.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 96.4% average accuracy.
---
```

## Best Practices

**Provide domain context:** Specifying the industry enables domain-specific terminology validation.

**List known terms:** Providing even 3-5 known technical terms dramatically improves detection accuracy.

**Verify high-impact corrections:** Terms appearing 20+ times should be manually verified before bulk replacement.

**Cross-reference authoritative sources:** For uncertain terms, verify against official documentation or industry standards.

## Use Cases

- **Software development meetings** - Correct framework names, programming terms, and tool references
- **Medical dictation** - Verify medication names, procedures, and anatomical terms
- **Legal depositions** - Ensure accurate case citations, statute references, and legal terminology
- **Financial analysis** - Standardize product names, regulations, and financial metrics
- **Engineering specifications** - Verify component names, measurements, and technical standards
- **Scientific research** - Correct methodology names, equipment terms, and chemical names

## Time Savings

- **Manual terminology verification**: 45-90 minutes per hour of technical transcript
- **AI-assisted with this prompt**: 8-12 minutes per hour of technical transcript
- **Especially valuable**: Highly technical content (engineering specs, medical procedures, legal briefs)

## Related Prompts

- **Speaker Attribution Error Corrector** - Fix speaker labels before terminology check
- **Transcript Formatting & Style Standardizer** - Apply formatting after terminology corrections
- **Transcript Quality Analyzer** - Assess overall transcript quality including terminology
