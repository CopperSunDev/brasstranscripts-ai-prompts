# Transcript Formatting & Style Standardizer

**Category**: General Content
**Difficulty**: Intermediate
**Estimated Tokens**: 1000-1500
**Version**: 1.0.0

## Description

Transform raw AI transcription output into professionally formatted documents following your specific style guide requirements. This prompt applies consistent formatting, grammar, punctuation, speaker labels, and technical notation across entire transcripts.

## The Prompt

```text
I have a raw AI-generated transcript that needs professional formatting and style standardization. Please help me apply consistent rules and formatting throughout the document:

**Current Transcript:**
[PASTE YOUR TRANSCRIPT HERE]

**Formatting Requirements:**
- Style preference: [Clean read / Verbatim / Intelligent verbatim]
- Number formatting: [Spell out 1-9, numerals 10+ / All numerals / All spelled out]
- Time format: [12-hour with AM/PM / 24-hour / Spelled out]
- Speaker label format: [Full names / "Speaker 1,2,3" / Role titles]
- Timestamp frequency: [Every paragraph / Every 30 seconds / None / Custom]

Please standardize the following throughout the transcript:

1. **Speaker Labels**
   - Apply consistent format for all speaker identifications
   - Place labels on separate lines before dialogue
   - Ensure no mid-sentence label interruptions

2. **Grammar and Punctuation**
   - Add proper sentence-ending punctuation
   - Insert commas for natural reading flow (not based on pauses)
   - Correct obvious grammatical errors while preserving speaker voice
   - Apply consistent capitalization rules

3. **Number and Time Formatting**
   - Standardize all number representations per style guide
   - Format all time references consistently
   - Add commas to large numbers (1,000 not 1000)

4. **Content Notation**
   - Mark inaudible sections as [inaudible HH:MM:SS]
   - Indicate unclear content as [unclear] or [unclear: best guess?]
   - Note significant non-speech sounds: [laughter], [phone rings]
   - Handle simultaneous speech: [speaking simultaneously]

5. **Technical Terms and Acronyms**
   - Spell out acronyms on first use: Full Name (ACRONYM)
   - Use acronym alone in subsequent references
   - Verify technical term spellings and correct if needed
   - Flag uncertain terminology for manual review

6. **Remove or Clean**
   - Remove excessive filler words ("um," "uh," "like") if clean read style
   - Eliminate false starts and repeated words unless verbatim required
   - Clean up run-on sentences into proper sentence structure
   - Remove irrelevant background conversation or noise

7. **Consistency Checks**
   - Ensure consistent spelling of names, companies, products throughout
   - Verify consistent terminology (don't alternate between synonyms)
   - Apply consistent paragraph breaks at logical conversation points
   - Maintain consistent tense and voice

Please return the fully formatted transcript with all standardizations applied, and provide a brief summary of major changes made (e.g., "Corrected 47 instances of inconsistent speaker labels, standardized 23 number formats, removed 156 filler words").

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with professional-grade accuracy.
---
```

## Best Practices

**Style guide clarity:** Specify your style preferences clearly (AP Style, Chicago Manual, internal company standards).

**Verbatim requirements:** For legal or medical transcripts, explicitly state verbatim requirements to prevent content removal.

**Sample review:** After first use, review a sample section to verify formatting matches expectations before processing full document.

**Save preferences:** Document your style choices for consistent formatting across multiple transcripts.

## Use Cases

- **Corporate meetings** - Convert raw Zoom transcripts into professionally formatted meeting minutes
- **Podcast transcripts** - Clean up automatic transcription for website publication with proper speaker attribution
- **Research interviews** - Prepare qualitative research transcripts for analysis software
- **Video content** - Format subtitle exports into readable blog posts or documentation
- **Legal proceedings** - Ensure consistent verbatim formatting for deposition transcripts
- **Medical records** - Apply SOAP format standards to clinical interview transcripts

## Time Savings

- **Manual formatting**: 60-90 minutes per hour of transcript
- **AI-assisted with this prompt**: 5-10 minutes per hour of transcript
- **Especially valuable**: 20,000+ word transcripts from conferences or long meetings

## Related Prompts

- **Speaker Attribution Error Corrector** - Fix speaker identification mistakes
- **Technical Terminology Consistency Checker** - Verify industry-specific terms
- **Transcript Quality Analyzer** - Assess overall transcript quality before formatting
