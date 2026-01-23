# Speaker Labeler

**Category**: General Content
**Use Case**: Transcript Processing and Speaker Attribution
**Complexity**: Beginner
**Output**: Transcript with named speakers replacing generic labels

## Overview

This AI prompt replaces generic speaker labels (Speaker A, Speaker B) with actual names or roles. Essential for making transcripts readable and professionally usable.

## The Prompt

```text
Replace speaker labels in this transcript with the correct names based on the context I provide.

SPEAKER INFORMATION:
- Speaker A is: [NAME AND ROLE]
- Speaker B is: [NAME AND ROLE]
- Speaker C is: [NAME AND ROLE]
(Add more as needed)

IF SPEAKERS AREN'T IDENTIFIED:
- Analyze speaking patterns to suggest likely roles
- Note: "Based on question patterns, Speaker A appears to be the interviewer"
- Label by role if names unknown: "Interviewer:", "Guest:", "Host:"

LABELING RULES:
1. Replace ALL instances of "Speaker A/B/C" with provided names
2. Use consistent format: "Name:" at start of each speaking turn
3. Preserve all original content exactly
4. Note any speakers who couldn't be confidently identified

OUTPUT FORMAT:
- Full transcript with corrected speaker labels
- If any speakers unclear, add note at the top explaining assumptions

TRANSCRIPT TO LABEL:
[PASTE YOUR CLEANED TRANSCRIPT HERE]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Clean Your Transcript First
Run through the Transcript Cleaner prompt before labeling speakers.

### Step 2: Gather Speaker Information
List who participated and their roles (host, guest, interviewer, etc.).

### Step 3: Fill In Speaker Details
Replace the placeholder speaker information with actual names and roles.

### Step 4: Review Attribution
Check a few speaker turns to verify correct assignment.

## Pro Tips for Best Results

**Provide roles, not just names**: "Speaker A is: Sarah Chen, VP of Marketing" helps AI understand context.

**Use the AI for unknowns**: If you don't know names, ask AI to identify by speaking patterns.

**Verify critical sections**: Double-check attribution for quotes you'll publish.

**Note uncertain attributions**: Flag any speakers the AI couldn't confidently identify.

## Example Use Cases

- **Interview transcripts**: Assign interviewer and interviewee names
- **Podcast episodes**: Label host(s) and guest(s) consistently
- **Meeting transcripts**: Attribute statements to specific team members
- **Panel discussions**: Track multiple speakers throughout

## Handling Unknown Speakers

When you don't have speaker names, provide context:

**Example context**:
> "This is a podcast interview about machine learning. One speaker is the host who asks questions, the other is a guest expert."

The AI can then:
- Identify who asks questions (host)
- Identify who provides expertise (guest)
- Label by role: "Host:", "Guest:"

## Expected Output Format

The AI will return:

1. **Full transcript** with named speakers
2. **Consistent labeling format** throughout
3. **Attribution notes** for any uncertain identifications
4. **All original content** preserved exactly

## Related Prompts

- **Transcript Cleaner**: Clean up raw transcript before labeling
- **Timestamp Formatter**: Format timestamps for your use case
- **Transcript Section Organizer**: Add structure and headers
- **Speaker Attribution Error Corrector**: Fix misattributed sections

---

**Source**: [BrassTranscripts Transcript Processing Workflow Guide](https://brasstranscripts.com/blog/transcript-processing-workflow-complete-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
