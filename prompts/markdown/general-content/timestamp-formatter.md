# Timestamp Formatter

**Category**: General Content
**Use Case**: Transcript Processing and Timestamp Optimization
**Complexity**: Intermediate
**Output**: Transcript with timestamps formatted for specific use case

## Overview

This AI prompt reformats timestamps in your transcript for different use cases: reading, video captions, research, or podcast show notes. Choose your output format and get properly formatted timestamps.

## The Prompt

```text
Reformat the timestamps in this transcript for my specific use case.

MY USE CASE: [CHOOSE ONE]
- READING: Add timestamps every 1-2 minutes as paragraph markers
- VIDEO CAPTIONS: Format as SRT/VTT with 2-3 second segments
- RESEARCH: Preserve all timestamps, format as [HH:MM:SS]
- PODCAST SHOW NOTES: Keep only major topic timestamps
- REMOVE: Strip all timestamps for clean reading

FORMATTING RULES BY USE CASE:

For READING:
- Add timestamp at start of each major topic or every 2 minutes
- Format: [12:34] at paragraph start
- Remove mid-sentence timestamps

For VIDEO CAPTIONS:
- Keep segments under 42 characters wide
- 2-3 second display time per segment
- Match natural speech breaks

For RESEARCH:
- Preserve all original timestamps
- Standardize format: [HH:MM:SS]
- Align with speaker turns

For PODCAST SHOW NOTES:
- Extract only topic-change timestamps
- Format: [MM:SS] Topic Name
- Create clickable chapter markers

TRANSCRIPT TO REFORMAT:
[PASTE YOUR TRANSCRIPT HERE]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Choose Your Use Case
Select the format that matches your intended output.

### Step 2: Copy and Customize
Paste the prompt and select one USE CASE option.

### Step 3: Add Your Transcript
Include the timestamped transcript from BrassTranscripts.

### Step 4: Apply Results
Use the reformatted timestamps in your final output.

## Pro Tips for Best Results

**Start with JSON format**: BrassTranscripts JSON includes word-level timestamps for precise formatting.

**Match your platform**: YouTube prefers specific SRT formatting; check platform guidelines.

**Test a sample**: Before processing a long transcript, test formatting on a short section.

**Keep original backup**: Save your original timestamps before reformatting.

## Use Case Examples

### Reading Format
```
[00:00] Welcome to today's discussion about AI transcription.

[02:15] Let's start with how the technology actually works.

[05:30] The key breakthrough came in 2022 with transformer models.
```

### Video Captions Format (SRT)
```
1
00:00:00,000 --> 00:00:03,500
Welcome to today's discussion
about AI transcription.

2
00:00:03,500 --> 00:00:06,200
Let's start with how
the technology actually works.
```

### Podcast Show Notes Format
```
[00:00] Introduction
[02:15] How AI Transcription Works
[05:30] The 2022 Breakthrough
[12:45] Accuracy Comparisons
[18:30] Practical Applications
```

## Expected Output Format

The AI will return:

1. **Reformatted transcript** matching your selected use case
2. **Consistent timestamp format** throughout
3. **Appropriate segment lengths** for use case
4. **Clean, professional output** ready for use

## Related Prompts

- **Transcript Cleaner**: Clean transcript before timestamp formatting
- **Speaker Labeler**: Add speaker names
- **Transcript Section Organizer**: Add structure and headers
- **Subtitle Timing Optimizer**: Fine-tune video caption timing

---

**Source**: [BrassTranscripts Transcript Processing Workflow Guide](https://brasstranscripts.com/blog/transcript-processing-workflow-complete-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
