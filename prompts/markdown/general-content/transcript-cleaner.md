# Transcript Cleaner

**Category**: General Content
**Use Case**: Transcript Processing and Cleanup
**Complexity**: Beginner
**Output**: Cleaned, readable transcript preserving speaker voice

## Overview

This AI prompt removes filler words, false starts, and repetitions from raw transcripts while preserving the speaker's voice and all important content. Essential first step in any transcript processing workflow.

## The Prompt

```text
Clean this raw transcript while preserving the speaker's voice and all important content.

CLEANING RULES:
1. Remove filler words: um, uh, like (when filler), you know, I mean, basically, actually, honestly, literally (when not literal)
2. Remove false starts: "I was going to—I decided to" → "I decided to"
3. Remove repetitions: "It was really, really good" → "It was really good"
4. Fix incomplete sentences when meaning is clear
5. Preserve intentional emphasis and speaking style
6. Keep technical terms exactly as spoken
7. Maintain all factual content—don't summarize or omit

DO NOT:
- Remove emotional language or emphasis
- Change meaning or intent
- Add information not present
- Over-formalize casual speech
- Remove speaker personality

OUTPUT FORMAT:
- Return the full cleaned transcript
- Use paragraph breaks at natural pauses or topic shifts
- Preserve speaker labels exactly as they appear

TRANSCRIPT TO CLEAN:
[PASTE YOUR TRANSCRIPT HERE]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Get Your Raw Transcript
Upload your audio to [BrassTranscripts](https://brasstranscripts.com/upload) and download the TXT format.

### Step 2: Copy the Prompt
Paste the entire prompt into ChatGPT, Claude, or your preferred AI assistant.

### Step 3: Add Your Transcript
Replace `[PASTE YOUR TRANSCRIPT HERE]` with your raw transcript text.

### Step 4: Review Results
Spot-check key sections to ensure meaning is preserved.

## Pro Tips for Best Results

**Process in chunks**: For transcripts over 5,000 words, break into logical sections.

**Provide context**: Add a note about the content type (interview, meeting, podcast) for better results.

**Compare before/after**: Keep the original to verify no content was lost.

**Run before speaker labeling**: Clean first, then assign names for better consistency.

## Before/After Example

**Before (raw)**:
> Speaker A: So, um, I was thinking that we should, you know, probably look at the, the quarterly numbers because, I mean, they're actually really important for, like, understanding where we're at.

**After (cleaned)**:
> Speaker A: I was thinking we should look at the quarterly numbers because they're really important for understanding where we're at.

## Example Use Cases

- **Meeting transcripts**: Clean up verbal tics for professional documentation
- **Podcast episodes**: Prepare transcripts for blog posts or show notes
- **Interview transcripts**: Create readable versions for research analysis
- **Lecture recordings**: Make educational content easier to read and study

## Expected Output Format

The AI will return:

1. **Full cleaned transcript** with all content preserved
2. **Paragraph breaks** at natural pauses
3. **Speaker labels** intact and consistent
4. **No summaries or omissions**—complete transcript only

## Related Prompts

- **Speaker Labeler**: Replace "Speaker A/B" with actual names
- **Timestamp Formatter**: Optimize timestamps for your use case
- **Transcript Section Organizer**: Add structure and headers
- **Transcript Content Repurposer**: Transform into blog posts, summaries, etc.

---

**Source**: [BrassTranscripts Transcript Processing Workflow Guide](https://brasstranscripts.com/blog/transcript-processing-workflow-complete-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
