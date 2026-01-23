# Transcript Section Organizer

**Category**: General Content
**Use Case**: Transcript Processing and Structure
**Complexity**: Intermediate
**Output**: Structured transcript with headers and table of contents

## Overview

This AI prompt adds section headers and structure to long transcripts based on topic changes. Essential for transcripts over 15 minutes to make content navigable and professional.

## The Prompt

```text
Add section headers and structure to this transcript based on topic changes.

ORGANIZATION RULES:
1. Identify natural topic shifts in the conversation
2. Add clear H2 headers for major sections
3. Add H3 subheaders for subtopics within sections
4. Create a table of contents at the top
5. Preserve all original content—don't summarize

HEADER STYLE: [CHOOSE ONE]
- DESCRIPTIVE: "Discussion of Q3 Revenue Performance"
- QUESTION-BASED: "How Did Q3 Revenue Perform?"
- TOPIC-BASED: "Q3 Revenue"
- TIMESTAMP-BASED: "[12:34] Q3 Revenue Discussion"

ADDITIONAL FORMATTING:
- [ ] Add bold to key decisions or action items
- [ ] Add bullet summaries at end of each section
- [ ] Highlight direct quotes worth noting
- [ ] Mark follow-up items or unresolved questions

OUTPUT STRUCTURE:
## Table of Contents
[Auto-generated list of sections]

## Section 1: [Header]
[Content]

## Section 2: [Header]
[Content]

TRANSCRIPT TO ORGANIZE:
[PASTE YOUR TRANSCRIPT HERE]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Clean and Label First
Run through Transcript Cleaner and Speaker Labeler prompts before organizing.

### Step 2: Choose Header Style
Select the style that matches your use case and audience.

### Step 3: Select Formatting Options
Check the additional formatting options you want applied.

### Step 4: Review Structure
Verify section breaks make sense and no content was lost.

## Pro Tips for Best Results

**Process long transcripts in parts**: For 60+ minute transcripts, organize in 20-minute chunks.

**Match header style to audience**: Use question-based for FAQ content, topic-based for documentation.

**Add context**: Note the meeting type or purpose to help AI identify logical sections.

**Verify completeness**: Ensure no content was accidentally summarized or omitted.

## Header Style Examples

### Descriptive Style
```
## Discussion of Q3 Revenue Performance
## Marketing Campaign Results and Next Steps
## Engineering Roadmap for Q4
```

### Question-Based Style
```
## How Did Q3 Revenue Perform?
## What Were the Marketing Campaign Results?
## What's the Engineering Roadmap for Q4?
```

### Topic-Based Style
```
## Q3 Revenue
## Marketing Campaigns
## Engineering Roadmap
```

### Timestamp-Based Style
```
## [00:00] Introduction and Agenda
## [05:30] Q3 Revenue Discussion
## [18:45] Marketing Campaign Review
```

## Example Use Cases

- **Meeting transcripts**: Create structured meeting notes with clear sections
- **Interview transcripts**: Organize by topic for easier analysis
- **Podcast episodes**: Prepare for show notes and chapter markers
- **Training recordings**: Structure educational content for reference

## Expected Output Format

The AI will return:

1. **Table of contents** at the top with section links
2. **H2 section headers** for major topics
3. **H3 subheaders** for subtopics
4. **All original content** preserved in full
5. **Optional formatting** (bold decisions, section summaries) as requested

## Related Prompts

- **Transcript Cleaner**: Clean transcript before organizing
- **Speaker Labeler**: Add speaker names before organizing
- **Timestamp Formatter**: Format timestamps for your use case
- **Transcript Content Repurposer**: Transform organized transcript into new formats

---

**Source**: [BrassTranscripts Transcript Processing Workflow Guide](https://brasstranscripts.com/blog/transcript-processing-workflow-complete-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
