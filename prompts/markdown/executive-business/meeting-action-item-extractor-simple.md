# Meeting Action Item Extractor (Simple)

**Category**: Executive & Business
**Difficulty**: Beginner
**Estimated Tokens**: 300-400
**Version**: 1.0.0

## Description

A streamlined, beginner-friendly prompt for extracting action items from meeting transcripts. Produces owner-grouped output with key decisions, open questions, and next meeting topics. Perfect for busy professionals who need quick, actionable results without complex formatting.

## The Prompt

```text
Analyze the following meeting transcript and extract all action items, decisions, and follow-ups.

For each action item, provide:
1. **Task**: Clear description of what needs to be done
2. **Owner**: Person responsible (from speaker labels, or "Unassigned" if unclear)
3. **Deadline**: Due date if mentioned, or "Not specified"
4. **Context**: Brief note on why this was assigned (1 sentence)

Format the output as a structured list organized by owner. At the end, include:
- **Key Decisions Made**: List any decisions finalized during the meeting
- **Open Questions**: Items that need follow-up but weren't resolved
- **Next Meeting Topics**: Items explicitly deferred to future discussion

TRANSCRIPT:
[Paste your transcript here]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---
```

## Best Practices

**Use speaker-labeled transcripts:** Upload your recording to BrassTranscripts to get automatic speaker identification (Speaker 1, Speaker 2, etc.), which the AI uses to assign task ownership.

**Add speaker names to the prompt:** If you know who's who, add context like "Speaker 1 is Sarah (Project Manager), Speaker 2 is Mike (Developer)" before the transcript.

**Review before distributing:** Verify action items and ownership before sending to your team. AI extraction is highly accurate but benefits from human review.

**Distribute within 24 hours:** Send the structured action items while the meeting is fresh. Prompt distribution significantly improves follow-through.

## Use Cases

- **Team meetings** - Capture all tasks and assignments from weekly standups
- **Client calls** - Document commitments and deliverables with clear ownership
- **Project kickoffs** - Extract initial assignments and dependencies
- **One-on-ones** - Track action items from manager/employee discussions
- **Cross-functional meetings** - Ensure nothing falls through the cracks

## Example Output

**Speaker 2 (Design Lead)**
- [ ] Create mockups for homepage and about page — Deadline: End of month
- [ ] Contact marketing team for updated product photos — Deadline: Today

**Speaker 3 (Mike)**
- [ ] Create product page mockups (pending photos) — Deadline: End of month

**Key Decisions Made**
- Website redesign mockups due end of month
- Speaker 2 taking homepage/about page, Mike taking product pages

**Open Questions**
- None identified

**Next Meeting Topics**
- Tuesday: Review mockup progress

## Related Resources

- **Source Blog Post**: [Meeting Action Items: AI Prompt Template](https://brasstranscripts.com/blog/meeting-action-items-ai-prompt-template)
- **Advanced Version**: [Meeting Action Items Extractor](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/executive-business/meeting-action-items-extractor.md) - More comprehensive with priority levels and CSV export
- **Prompt Collection**: [AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- **Get Transcripts**: [BrassTranscripts Upload](https://brasstranscripts.com)

## Changelog

- **v1.0.0** (2025-12-25) - Initial release with simple 4-field action item format
