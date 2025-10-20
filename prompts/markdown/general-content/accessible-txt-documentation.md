# Accessible TXT Documentation Generator

**Category**: General Content
**Difficulty**: Intermediate
**Estimated Tokens**: 700-1000
**Version**: 1.0.0

## Description

Transform any transcript format into WCAG-compliant accessible documentation with proper structure and formatting. Creates clean, screen reader-optimized TXT files perfect for accessibility requirements, documentation archives, and universal device compatibility.

## The Prompt

```text
Create a WCAG-compliant accessible transcript document from this source material.

Accessibility Requirements:
1. Clear speaker identification
2. Logical paragraph structure
3. Proper headings and sections
4. Description of non-speech audio [when present]
5. UTF-8 encoding
6. Screen reader optimization
7. Remove filler words for clarity

Document Structure:
- Title: [Meeting/Interview/Lecture Title]
- Date: [Date if known]
- Participants: [List of speakers]
- Main Content: [Formatted transcript]
- Summary: [Key points and action items]

Formatting Guidelines:
- Use "Speaker Name:" for speaker labels
- Add blank lines between speaker turns
- Group related exchanges into paragraphs
- Include timestamps for key moments [optional]
- Add [DESCRIPTION] tags for non-speech audio

Content Optimization:
- Remove filler words (um, uh, like) for readability
- Fix obvious transcription errors
- Maintain natural speech patterns
- Preserve important pauses [indicated]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 95-98% accuracy.
---

Source Transcript:
[PASTE YOUR TRANSCRIPT IN ANY FORMAT]

Please create a clean, accessible TXT document following W3C guidelines and optimized for screen readers.
```

## Best Practices

**Speaker Identification:** Use consistent "Speaker Name:" format at the start of each turn for clear attribution.

**Paragraph Structure:** Group related exchanges logically to improve reading flow and comprehension.

**Non-Speech Audio:** Include descriptions like [applause], [laughter], or [pause] when contextually important.

**Filler Word Removal:** Edit out "um," "uh," "like" to create cleaner, more professional documentation.

## Use Cases

- **Accessibility Compliance** - Create WCAG 2.1 conformant transcripts for legal requirements
- **Meeting Documentation** - Generate clean, professional meeting minutes from recordings
- **Archive Records** - Create long-term accessible documentation for institutional archives
- **Research Interviews** - Transform interview recordings into readable research documentation
- **Educational Content** - Provide accessible lecture transcripts for students with disabilities
- **Legal Records** - Generate court-ready transcripts meeting accessibility standards

## WCAG Compliance Features

### Level A Requirements (Essential)
- ✅ Text alternative for non-text content
- ✅ Adaptable presentation without loss of information
- ✅ Distinguishable content with clear structure
- ✅ Keyboard accessible navigation (inherent in TXT format)

### Level AA Requirements (Enhanced)
- ✅ Clear contrast and readable text size (user-controlled in TXT)
- ✅ Consistent navigation and identification
- ✅ Input assistance through clear labeling
- ✅ Compatible with assistive technologies

### Best Practice Enhancements
- UTF-8 encoding for universal character support
- Logical heading hierarchy for screen reader navigation
- Descriptive speaker labels for context
- Clean formatting without special characters that confuse screen readers

## Example Transformation

**Input (SRT with timing):**
```
1
00:00:00,000 --> 00:00:03,500
Um, welcome everyone to today's, uh, discussion

2
00:00:03,500 --> 00:00:07,200
about, like, transcription formats
```

**Output (Accessible TXT):**
```
PROJECT DISCUSSION: TRANSCRIPTION FORMATS
Date: October 2, 2025
Participants: John Smith (Host), Sarah Johnson (Guest)

=== INTRODUCTION ===

John Smith: Welcome everyone to today's discussion about transcription formats. I'm excited to explore the different options available and how to choose the right format for your specific workflow needs.

Sarah Johnson: Thanks for having me, John. The key thing to understand about transcript formats is that each serves a distinct purpose, and choosing the wrong format can create unnecessary friction in your workflow.

[Discussion continues...]

=== KEY POINTS SUMMARY ===

1. TXT format provides universal accessibility and screen reader compatibility
2. SRT/VTT formats are essential for video subtitle applications
3. JSON format enables programmatic analysis and AI integration
4. Format selection should be based on specific use case requirements
```

## Technical Specifications

### Character Encoding
- **Required:** UTF-8 encoding for maximum compatibility
- **Prohibited:** Special encoding that may not render on all devices
- **Line Endings:** Standard LF or CRLF depending on platform

### Formatting Standards
- **Speaker Labels:** "Speaker Name:" format at start of turn
- **Blank Lines:** One blank line between speaker turns
- **Paragraphs:** Group related exchanges logically
- **Sections:** Use `=== SECTION NAME ===` for major divisions
- **Timestamps:** Optional `[HH:MM:SS]` for key moments

### Accessibility Features
- **No Special Formatting:** Avoid bold/italic markup that doesn't render in TXT
- **Simple Punctuation:** Standard periods, commas, question marks only
- **Clear Attribution:** Every statement has clear speaker identification
- **Logical Flow:** Content organized for linear reading by screen readers

## Related Resources

- [W3C Web Accessibility Initiative - Transcripts](https://www.w3.org/WAI/media/av/transcripts/) - Official WCAG guidelines
- [Section 508 Captions and Transcripts](https://www.section508.gov/create/captions-transcripts/) - US federal compliance
- [Transcription File Formats Guide](https://brasstranscripts.com/transcription-file-formats) - Complete format comparison

## Tags

`accessibility`, `wcag-compliance`, `txt-format`, `screen-reader`, `documentation`, `archive-quality`, `universal-compatibility`
