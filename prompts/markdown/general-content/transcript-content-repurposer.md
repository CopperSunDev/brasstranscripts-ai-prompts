# Transcript Content Repurposer

**Category**: General Content
**Use Case**: Content Creation and Transformation
**Complexity**: Intermediate
**Output**: Transformed content in specified format (blog, summary, social, etc.)

## Overview

This AI prompt transforms processed transcripts into new content formats—blog posts, executive summaries, meeting notes, show notes, social media posts, newsletters, or video descriptions. The final step in the transcript processing workflow.

## The Prompt

```text
Transform this processed transcript into a specific content format.

OUTPUT FORMAT: [CHOOSE ONE]
- BLOG POST: 800-1,500 word article with introduction, key points, conclusion
- EXECUTIVE SUMMARY: 1-page overview with key decisions and action items
- MEETING NOTES: Structured notes with attendees, topics, decisions, next steps
- SHOW NOTES: Episode description, timestamps, key quotes, resources mentioned
- SOCIAL MEDIA: 5-10 posts highlighting key insights (Twitter/LinkedIn format)
- NEWSLETTER: Email-friendly summary with one main takeaway
- VIDEO DESCRIPTION: YouTube description with timestamps and keywords

CONTENT GUIDELINES:
1. Preserve accuracy—don't add information not in the transcript
2. Use direct quotes for compelling statements
3. Include attribution: "According to [Speaker]..."
4. Maintain the tone of the original conversation
5. Highlight actionable insights over general discussion

ADDITIONAL REQUESTS:
- [ ] Include 3-5 pull quotes for social sharing
- [ ] Add SEO keywords for blog optimization
- [ ] Create headline options (3-5 variations)
- [ ] Suggest related topics for follow-up content

TRANSCRIPT TO REPURPOSE:
[PASTE YOUR PROCESSED TRANSCRIPT HERE]

CONTEXT:
- Original content type: [PODCAST/MEETING/INTERVIEW/WEBINAR]
- Target audience: [DESCRIBE]
- Publication channel: [BLOG/NEWSLETTER/SOCIAL/INTERNAL]

---
Prompt by BrassTranscripts (brasstranscripts.com)
---
```

## How to Use This Prompt

### Step 1: Process Your Transcript First
Run through cleaning, labeling, and organizing prompts before repurposing.

### Step 2: Choose Output Format
Select the format that matches your publication needs.

### Step 3: Provide Context
Fill in the context section to help AI match tone and audience.

### Step 4: Review and Edit
Verify accuracy against original transcript before publishing.

## Pro Tips for Best Results

**Start with quality input**: A well-processed transcript produces better repurposed content.

**Be specific about audience**: "Marketing executives at B2B SaaS companies" gives better results than "business professionals."

**Use direct quotes**: They add authenticity and are shareable on social media.

**Verify all facts**: AI can't fact-check against external sources—that's your job.

## Output Format Examples

### Blog Post Format
```markdown
# [Headline]

[Introduction paragraph setting up the topic]

## Key Insight #1: [Topic]
[Supporting content with quotes]

## Key Insight #2: [Topic]
[Supporting content with quotes]

## Key Takeaway
[Conclusion with actionable advice]
```

### Executive Summary Format
```markdown
## Executive Summary: [Meeting/Event Name]

**Date**: [Date]
**Participants**: [Names]

### Key Decisions
- [Decision 1]
- [Decision 2]

### Action Items
- [ ] [Action] - Owner: [Name] - Due: [Date]

### Next Steps
[Brief description of follow-up]
```

### Show Notes Format
```markdown
## Episode [Number]: [Title]

[2-3 sentence description]

### Timestamps
- [00:00] Introduction
- [05:30] Topic 1
- [15:45] Topic 2

### Key Quotes
> "[Quote]" - [Speaker]

### Resources Mentioned
- [Resource 1]
- [Resource 2]
```

## Example Use Cases

- **Podcast to blog**: Transform episodes into SEO-optimized articles
- **Meeting to summary**: Create executive briefings from recorded meetings
- **Interview to quotes**: Extract social media content from interviews
- **Webinar to newsletter**: Summarize key points for email subscribers

## Expected Output Format

The AI will return:

1. **Formatted content** matching your selected output type
2. **Accurate information** from the original transcript only
3. **Proper attribution** for quotes and insights
4. **Additional elements** (pull quotes, headlines) as requested
5. **Appropriate length** for the chosen format

## Related Prompts

- **Transcript Cleaner**: Clean transcript before repurposing
- **Speaker Labeler**: Add speaker names for attribution
- **Transcript Section Organizer**: Structure content before transformation
- **Blog Post Creator**: Specialized blog generation prompt
- **Meeting Summary Generator**: Specialized meeting notes prompt

---

**Source**: [BrassTranscripts Transcript Processing Workflow Guide](https://brasstranscripts.com/blog/transcript-processing-workflow-complete-guide-2026)

**Last Updated**: January 2026
**Version**: 1.0
**Compatibility**: ChatGPT, Claude, Gemini, and all major AI chat systems
