# Transcript Format Converter

**Category**: General Content
**Use Case**: Format Conversion and Compatibility
**Complexity**: Intermediate
**Output**: Transcript converted to specified format (TXT, SRT, VTT, JSON)

## Overview

This AI prompt converts transcripts between formats: TXT, SRT, VTT, and JSON. Useful when you need a different format than what you have, or when converting for specific platforms.

## The Prompt

```text
Convert this transcript to a different format.

SOURCE FORMAT: [TXT/SRT/VTT/JSON]
TARGET FORMAT: [TXT/SRT/VTT/JSON]

CONVERSION REQUIREMENTS:

**TXT to SRT/VTT:**
- Estimate timestamps based on ~150 words per minute speaking rate
- Split into 2-3 second segments
- Keep segments under 42 characters wide

**SRT to VTT:**
- Add WEBVTT header
- Change comma to period in timestamps (00:00:00,000 → 00:00:00.000)
- Add speaker tags if speakers are identified

**VTT to SRT:**
- Remove WEBVTT header
- Change period to comma in timestamps
- Strip styling tags, keep text only
- Add sequence numbers

**Any to TXT:**
- Remove timestamps and formatting
- Add paragraph breaks at natural pauses
- Keep speaker labels

**Any to JSON:**
- Structure as segments array
- Include start/end times
- Add speaker attribution
- Include metadata (duration, speaker count)

OUTPUT:
- Full converted transcript
- Note any information lost in conversion
- Flag any segments needing manual review

TRANSCRIPT TO CONVERT:
[PASTE YOUR TRANSCRIPT HERE]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Identify Your Formats
Note what format you have and what format you need.

### Step 2: Specify Conversion Direction
Fill in SOURCE FORMAT and TARGET FORMAT.

### Step 3: Paste Your Transcript
Include the full transcript in its current format.

### Step 4: Review Output
Check for any information loss or segments flagged for review.

## Pro Tips for Best Results

**Use BrassTranscripts for all formats**: We provide TXT, SRT, VTT, and JSON with every transcription—no conversion needed.

**Preserve original**: Keep your source file; conversion can lose information.

**Test a sample first**: Convert a short section before processing long transcripts.

**Verify timing**: AI-estimated timestamps may need manual adjustment.

## Conversion Matrix

| From → To | TXT | SRT | VTT | JSON |
|-----------|-----|-----|-----|------|
| **TXT** | — | Estimated timing | Estimated timing | Estimated timing |
| **SRT** | Loses timing | — | Simple conversion | Structured data |
| **VTT** | Loses timing/styling | Loses styling | — | Structured data |
| **JSON** | Loses structure | Full conversion | Full conversion | — |

### What's Lost in Conversion

- **To TXT**: Timestamps, formatting, styling
- **To SRT from VTT**: Styling, positioning, speaker tags
- **To VTT from TXT**: Need estimated timestamps
- **To JSON from TXT**: Need estimated timing

## Example Conversions

### TXT to SRT
**Input (TXT)**:
```
Speaker 1: Welcome to the podcast. Today we're talking about AI.

Speaker 2: Thanks for having me. I've worked in AI for five years.
```

**Output (SRT)**:
```
1
00:00:00,000 --> 00:00:04,000
Speaker 1: Welcome to the podcast.
Today we're talking about AI.

2
00:00:04,000 --> 00:00:08,000
Speaker 2: Thanks for having me.
I've worked in AI for five years.
```

### SRT to VTT
**Input (SRT)**:
```
1
00:00:00,000 --> 00:00:04,000
Welcome to the podcast.
```

**Output (VTT)**:
```
WEBVTT

00:00:00.000 --> 00:00:04.000
Welcome to the podcast.
```

## Example Use Cases

- **YouTube upload**: Convert TXT to SRT for caption upload
- **Web player**: Convert SRT to VTT for HTML5 video
- **Reading**: Convert SRT/VTT to clean TXT
- **Development**: Convert any format to JSON for API use

## Expected Output Format

The AI will return:

1. **Fully converted transcript** in target format
2. **Proper formatting** for the target format
3. **Notes** about any information lost
4. **Flags** for segments needing manual review

## Better Alternative: Download All Formats

BrassTranscripts includes all four formats (TXT, SRT, VTT, JSON) with every transcription. No conversion needed—download the format you need.

**[Upload audio and get all formats →](https://brasstranscripts.com/upload)**

## Related Prompts

- **Timestamp Formatter**: Optimize timestamps for specific use cases
- **Subtitle Timing Optimizer**: Fine-tune caption timing
- **Format Conversion Optimizer**: Advanced format transformation

---

**Source**: [BrassTranscripts Transcription File Formats Guide](https://brasstranscripts.com/blog/transcription-file-formats-decision-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
