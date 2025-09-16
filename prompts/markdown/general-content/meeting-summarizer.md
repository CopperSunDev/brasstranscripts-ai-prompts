# Meeting Summary and Action Items

**Category**: General Content
**Difficulty**: Beginner
**Estimated Tokens**: 600-1000
**Version**: 1.2.0

## Description

Convert lengthy meeting recordings into concise, actionable summaries that keep teams aligned and productive. Perfect for transforming team meetings, client calls, project discussions, and strategic sessions into organized documentation that drives accountability and follow-through.

## The Prompt

```text
Please analyze this meeting transcript and create a comprehensive summary with the following structure:

## Meeting Overview
- Date, participants, and main purpose
- Key decisions made
- Overall outcomes

## Discussion Highlights
- Main topics covered (with bullet points)
- Important concerns or challenges raised
- Innovative ideas or solutions proposed

## Action Items
- Specific tasks assigned (with responsible person if mentioned)
- Deadlines mentioned
- Follow-up meetings scheduled

## Key Decisions
- Final decisions made
- Approvals given
- Budget or resource allocations

## Next Steps
- Immediate priorities
- Longer-term initiatives
- Required follow-up actions

Please keep the summary concise but comprehensive, focusing on actionable information rather than conversational details.

Transcript:
[PASTE YOUR TRANSCRIPT HERE]
```

## Best Practices

**Speaker tracking:** Use JSON format to automatically identify who said what and assign accountability for action items.

**Time references:** Include timestamps for important decisions using SRT/VTT formats when precision matters.

**Confidentiality:** Always review before sharing to ensure sensitive information is appropriately handled.

**Distribution:** Create different summary levels for different stakeholder groups (executive summary vs. detailed team summary).

## Use Cases

- **Team meetings** - Weekly standups, sprint planning, retrospectives
- **Client calls** - Project updates, requirement discussions, feedback sessions
- **Board meetings** - Strategic discussions, quarterly reviews, governance decisions
- **Project meetings** - Status updates, milestone reviews, problem-solving sessions
- **Sales meetings** - Prospect calls, deal reviews, pipeline discussions
- **Training sessions** - Workshop summaries, knowledge transfer, skill development

## Example Output

### Meeting Summary: Q4 Product Launch Planning

**Meeting Overview**
- **Date:** September 16, 2025
- **Participants:** Sarah (Product Manager), Mike (Engineering Lead), Lisa (Marketing Director), Tom (Sales Manager)
- **Purpose:** Finalize Q4 product launch strategy and timeline
- **Key Decisions:** Launch date confirmed for November 15, 2025; marketing budget approved at $50K
- **Overall Outcomes:** Clear launch plan established with defined responsibilities and deadlines

**Discussion Highlights**
- **Product readiness:** Engineering confirmed core features complete, testing phase begins October 1
- **Marketing strategy:** Focus on digital channels with emphasis on video content and customer testimonials
- **Sales preparation:** Need updated training materials and pricing strategy finalization
- **Concerns raised:** Potential conflict with competitor launch timing; resource allocation for support team
- **Solutions proposed:** Accelerate beta testing program; implement phased support team scaling

**Action Items**
- **Sarah:** Finalize beta testing program and recruit 50 test users (Due: September 30)
- **Mike:** Complete security audit and performance testing (Due: October 15)
- **Lisa:** Develop launch campaign assets and schedule content calendar (Due: October 30)
- **Tom:** Create sales training materials and update pricing documentation (Due: October 20)
- **All:** Weekly check-in meetings every Thursday at 2 PM starting September 23

**Key Decisions**
- **Launch date:** November 15, 2025 (firm commitment)
- **Marketing budget:** $50,000 approved for launch campaign
- **Beta program:** 50 users for 4-week testing period
- **Support scaling:** Hire 2 additional support staff by November 1

**Next Steps**
- **Immediate (This week):** Kick off beta recruitment, begin security audit preparation
- **Short-term (Next 30 days):** Execute beta testing, develop marketing assets, create training materials
- **Long-term (Next 60 days):** Launch campaign execution, sales team training, support team scaling

## Advanced Techniques

**Multi-format analysis:** For complex meetings, combine formats:
```text
I have this meeting in multiple formats:
- TXT for clean content analysis
- JSON with speaker identification
- SRT with precise timestamps

Please create a comprehensive summary that uses speaker attribution from JSON and timestamps from SRT for key decisions.
```

**Stakeholder-specific summaries:** Request different summary levels:
```text
Please create two versions:
1. Executive summary (2-3 bullet points) for leadership team
2. Detailed summary (full format above) for project team
```

**Follow-up automation:** Add tracking elements:
```text
Additionally, please create:
- A task list suitable for project management tools
- Calendar entries for mentioned meetings and deadlines
- Risk assessment for identified concerns
```

## Integration Tips

**Weekly workflow:** Use this prompt systematically for all recurring team meetings to maintain consistent documentation.

**Project management integration:** Export action items directly to your project management system for automatic task creation.

**Accountability tracking:** Use speaker identification to ensure clear ownership of action items and decisions.

**Historical reference:** Maintain meeting summaries as searchable documentation for project history and decision tracking.

## Quality Assurance

Before distributing meeting summaries:

- [ ] Verify all action items have clear owners
- [ ] Confirm deadlines are accurately captured
- [ ] Ensure sensitive information is appropriately handled
- [ ] Check that key decisions are clearly stated
- [ ] Validate participant names and roles
- [ ] Review for completeness and clarity

## Resources

- 📖 **Detailed Guide**: [7 Powerful LLM Prompts to Transform Your Transcripts](https://brasstranscripts.com/blog/powerful-llm-prompts-transcript-optimization#prompt-2-meeting-summary-and-action-items)
- 🎯 **All Prompts**: [BrassTranscripts AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- 🎤 **Get Transcripts**: [Upload Your Audio](https://brasstranscripts.com/upload)

---

**Created by [BrassTranscripts](https://brasstranscripts.com)** - Professional AI transcription with 95-98% accuracy