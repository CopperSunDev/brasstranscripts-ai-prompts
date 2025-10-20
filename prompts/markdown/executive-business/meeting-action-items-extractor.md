# Meeting Action Items Extractor

**Category**: Executive & Business
**Difficulty**: Beginner
**Estimated Tokens**: 400-600
**Version**: 1.0.0

## Description

Automatically extract every task, assignment, and commitment from meeting transcripts into a project management-ready checklist. Perfect for ensuring no action items get lost and improving team accountability and follow-through rates.

## The Prompt

```text
Based on this meeting transcript, create a comprehensive action item tracker:

1. List every task, assignment, or commitment mentioned
2. Identify the responsible person/team for each item
3. Extract or infer deadlines and due dates
4. Categorize by urgency (High/Medium/Low priority)
5. Note any dependencies between action items
6. Flag items that need clarification or follow-up
7. Format as a project management-ready checklist with status column

Ensure nothing gets lost in translation.

Meeting type: [MEETING TYPE]
Project: [IF APPLICABLE]
Date: [DATE]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 95-98% accuracy.
---

Meeting transcript:
[PASTE YOUR BRASSTRANSCRIPTS OUTPUT HERE]
```

## Best Practices

**Comprehensive capture:** Extract every commitment regardless of how casually mentioned—"I'll look into that" becomes an action item.

**Clear ownership:** Assign specific individuals, not teams, whenever possible to ensure accountability and prevent diffusion of responsibility.

**Explicit deadlines:** Extract stated deadlines or infer reasonable ones based on context ("by next meeting," "this week," "ASAP").

**Dependency identification:** Note when one task blocks another to help prioritize work and anticipate delays.

## Use Cases

- **Project management** - Transfer action items directly into Asana, Jira, Monday.com, or Trello
- **Team accountability** - Clear assignments eliminate "I thought you were doing that" confusion
- **Client deliverables** - Track commitments made to clients with explicit timelines
- **Follow-up tracking** - Ensure every commitment from meetings gets followed through

## Example Output

### Action Item Tracker

**Meeting**: Q4 Product Planning Session
**Date**: October 26, 2025
**Project**: Product Roadmap 2026

---

### High Priority Action Items

**1. Finalize enterprise feature requirements document**
- **Owner**: Sarah Chen (Product Manager)
- **Deadline**: November 1, 2025 (stated: "by next Friday")
- **Status**: [ ] Not Started
- **Dependencies**: Blocks items #3 and #4
- **Notes**: Must include input from sales team on top customer requests

**2. Schedule technical feasibility review with engineering**
- **Owner**: Michael Torres (Engineering Lead)
- **Deadline**: November 3, 2025 (inferred: "early next week")
- **Status**: [ ] Not Started
- **Dependencies**: Requires completion of item #1
- **Notes**: 2-hour meeting needed, include Sarah and David

**3. Create cost estimate for enterprise features**
- **Owner**: Jennifer Liu (Engineering Manager)
- **Deadline**: November 10, 2025 (stated: "within two weeks")
- **Status**: [ ] Not Started
- **Dependencies**: Requires completion of items #1 and #2
- **Notes**: Include infrastructure costs and ongoing maintenance

---

### Medium Priority Action Items

**4. Draft enterprise pricing tier proposal**
- **Owner**: David Park (VP Sales)
- **Deadline**: November 15, 2025 (stated: "mid-November")
- **Status**: [ ] Not Started
- **Dependencies**: Requires completion of item #3
- **Notes**: Coordinate with finance on margin requirements

**5. Research competitor enterprise offerings**
- **Owner**: Amanda Williams (Product Marketing)
- **Deadline**: November 8, 2025 (inferred: "next week")
- **Status**: [ ] Not Started
- **Dependencies**: None
- **Notes**: Focus on feature sets and pricing models from Salesforce, HubSpot, Zendesk

**6. Update product roadmap slides for board presentation**
- **Owner**: Sarah Chen (Product Manager)
- **Deadline**: January 10, 2026 (stated: "before January board meeting")
- **Status**: [ ] Not Started
- **Dependencies**: Requires completion of items #1-4
- **Notes**: Include timeline, resource requirements, and expected revenue impact

**7. Set up weekly sync meetings with sales on enterprise pipeline**
- **Owner**: David Park (VP Sales)
- **Deadline**: November 1, 2025 (inferred: "starting next week")
- **Status**: [ ] Not Started
- **Dependencies**: None
- **Notes**: Invite Sarah Chen to stay aligned on product feedback from prospects

---

### Low Priority Action Items

**8. Explore integration partnerships with complementary products**
- **Owner**: Robert Thompson (Business Development)
- **Deadline**: December 15, 2025 (stated: "by end of year")
- **Status**: [ ] Not Started
- **Dependencies**: None
- **Notes**: Michael mentioned Slack, Microsoft Teams, and Zoom as potential partners

**9. Document current enterprise customer pain points**
- **Owner**: Lisa Martinez (Customer Success)
- **Deadline**: November 30, 2025 (stated: "end of November")
- **Status**: [ ] Not Started
- **Dependencies**: None
- **Notes**: Interview current top 10 customers, focus on feature gaps

**10. Review and update onboarding documentation for enterprise features**
- **Owner**: Amanda Williams (Product Marketing)
- **Deadline**: Q1 2026 (stated: "when features ship")
- **Status**: [ ] Not Started
- **Dependencies**: Requires completion of item #1
- **Notes**: Will need engineering review for technical accuracy

---

### Items Needing Clarification

**11. "Someone should look into the API rate limiting issue"**
- **Owner**: NEEDS CLARIFICATION (mentioned by Sarah, unclear who should own)
- **Deadline**: NEEDS CLARIFICATION
- **Status**: [ ] Not Started
- **Follow-up needed**: Sarah to assign owner and deadline

**12. "We need to think about mobile app improvements"**
- **Owner**: NEEDS CLARIFICATION (general discussion, no owner assigned)
- **Deadline**: NEEDS CLARIFICATION
- **Status**: [ ] Not Started
- **Follow-up needed**: Michael to determine if this is Q4 priority or deferred to 2026

---

### Summary

**Total Action Items**: 12
**High Priority**: 3
**Medium Priority**: 4
**Low Priority**: 3
**Needs Clarification**: 2

**Next Steps**:
1. Circulate this action item list to all meeting participants for review
2. Clarify ownership and deadlines for items #11 and #12
3. Transfer confirmed action items to project management system (Asana)
4. Set up weekly check-in to review progress on high-priority items

**Critical Path Dependencies**:
Item #1 (Requirements Doc) → Item #2 (Tech Review) → Item #3 (Cost Estimate) → Item #4 (Pricing Proposal) → Item #6 (Board Presentation)

---

### Project Management Import Format

**For Asana/Trello/Monday.com** (CSV format):

```
Task,Owner,Due Date,Priority,Status,Dependencies
Finalize enterprise feature requirements document,Sarah Chen,2025-11-01,High,Not Started,None
Schedule technical feasibility review with engineering,Michael Torres,2025-11-03,High,Not Started,#1
Create cost estimate for enterprise features,Jennifer Liu,2025-11-10,High,Not Started,#1 #2
Draft enterprise pricing tier proposal,David Park,2025-11-15,Medium,Not Started,#3
Research competitor enterprise offerings,Amanda Williams,2025-11-08,Medium,Not Started,None
```

## Related Resources

- **Source Blog Post**: [Corporate Meeting Documentation](https://brasstranscripts.com/blog/corporate-meeting-documentation-transcription-workflow#extracting-action-items-automatically)
- **Prompt Collection**: [AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- **Get Transcripts**: [BrassTranscripts Upload](https://brasstranscripts.com/upload)

## Changelog

- **v1.0.0** (2025-10-26) - Initial release with comprehensive action item extraction