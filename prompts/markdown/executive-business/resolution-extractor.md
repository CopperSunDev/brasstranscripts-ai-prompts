# Resolution Extractor

**Category**: Executive & Business
**Difficulty**: Intermediate
**Source**: [Board Meeting Transcription Guide](https://brasstranscripts.com/blog/board-meeting-transcription-corporate-governance-guide)

## Description

Extracts formal resolutions, motions, and voting records from board meeting transcripts for minutes documentation. Identifies resolution language, movers, seconders, and vote counts for accurate corporate governance records.

## Use Cases

- Board meeting minutes preparation
- Resolution documentation for corporate records
- Voting record extraction
- Compliance documentation
- Committee meeting documentation

## The Prompt

```text
Analyze this board meeting transcript and extract all formal resolutions, motions, and voting records for minutes documentation.

MEETING CONTEXT:
- Organization type: [Public company/Private company/Nonprofit/HOA]
- Meeting type: [Regular board meeting/Special meeting/Annual meeting/Committee meeting]
- Quorum requirements: [Majority/Supermajority/Specific number]

Extract and format:

1. **Resolutions Passed**
   For each resolution:
   - Resolution number (if applicable)
   - Exact resolution language (verbatim from the motion)
   - Moved by: [Director name]
   - Seconded by: [Director name]
   - Vote: [Unanimous/Vote count For-Against-Abstain]
   - Effective date (if specified)

2. **Motions Tabled or Withdrawn**
   - Motion description
   - Reason for tabling/withdrawal
   - Expected return date (if specified)

3. **Formal Dissent Statements**
   - Director name
   - Matter dissented from
   - Stated rationale (only if director requested formal notation)

4. **Delegations of Authority**
   - Authority delegated
   - To whom
   - Scope and limitations
   - Expiration (if any)

5. **Required Follow-Up**
   - Action items assigned
   - Responsible party
   - Due date
   - Reporting requirement

FORMAT: Structure output for direct incorporation into formal minutes.

TRANSCRIPT:
[Paste your board meeting transcript here]

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with speaker identification.
---
```

## Expected Output

The prompt generates structured resolution documentation including:
- Complete resolution text with parliamentary details
- Voting records for each motion
- Tabled and withdrawn motions
- Formal dissent statements
- Authority delegations and action items

## Customization Tips

- Add resolution numbering scheme for your organization
- Include specific committee authorization requirements
- Add bylaws-specific voting threshold references
- Modify for nonprofit or HOA governance requirements

## Best Practices

- Delete transcript after minutes are approved
- Use as drafting aid, not replacement for formal minutes
- Verify resolution language against recording if critical
- Include dissent only when formally requested by director

## Related Prompts

- [Board Minutes Drafting Assistant](./board-minutes-drafting-assistant.md) - Complete minutes drafting
- [Meeting Action Items Extractor](./meeting-action-items-extractor.md) - General action item extraction

## Resources

- [Board Meeting Transcription Guide](https://brasstranscripts.com/blog/board-meeting-transcription-corporate-governance-guide)
- [BrassTranscripts Upload](https://brasstranscripts.com)
