# Speaker Attribution Error Corrector

**Category**: General Content
**Difficulty**: Intermediate
**Estimated Tokens**: 1200-1800
**Version**: 1.0.0

## Description

While AI speaker identification is highly accurate, some attribution errors can occur that confuse readers and misattribute important statements. This prompt systematically identifies and corrects speaker attribution mistakes using context clues, speech patterns, and logical conversation flow.

## The Prompt

```text
I have a transcript with automatic speaker identification that contains some speaker attribution errors. Please help me identify and correct these mistakes systematically:

**Transcript with Speaker Labels:**
[PASTE YOUR TRANSCRIPT HERE]

**Known Speaker Information (if available):**
- Speaker names: [LIST KNOWN PARTICIPANTS]
- Voice characteristics: [DESCRIBE - e.g., "Speaker 1 is female with British accent, Speaker 2 is male with American accent"]
- Context clues: [ANY RELEVANT INFO - e.g., "John is the CEO mentioned in line 45", "Sarah discusses marketing topics"]

Please analyze the transcript and:

1. **Identify Attribution Errors**
   - Find instances where speaker labels switch mid-sentence or mid-thought
   - Detect unnatural speaker changes (e.g., one person asking and answering their own question)
   - Flag conversations where responses don't logically match questions
   - Note any single sentence unrealistically attributed to 3+ different speakers

2. **Detect Pattern-Based Errors**
   - Identify systematic errors (e.g., Speaker 2 and Speaker 3 consistently confused)
   - Find sections where all speakers labeled generically ("Speaker 1, 2, 3") but context reveals names
   - Detect when one speaker's dialogue is split across multiple speaker IDs
   - Note timestamp clusters where speaker switches happen every 2-3 seconds (likely incorrect)

3. **Apply Context-Based Corrections**
   - Use content context (e.g., "As I mentioned earlier" links to previous speaker)
   - Identify speakers through self-references ("Hi, I'm John", "My team and I...")
   - Track topic ownership (technical discussions likely same expert throughout)
   - Recognize response patterns (answering questions logically pairs speakers)

4. **Suggest Systematic Corrections**
   For each error type found, provide:
   - **Error description**: "Speaker 2 and Speaker 3 confused in lines 145-230"
   - **Evidence**: Quote 2-3 specific examples showing the error
   - **Recommended fix**: "All 'Speaker 3' in this section should be 'Speaker 2' based on topic continuity"
   - **Confidence level**: High/Medium/Low based on available evidence

5. **Generate Corrected Version**
   - Provide the fully corrected transcript with accurate speaker labels
   - Highlight major corrections made (e.g., "Consolidated 4 speaker IDs into 2 actual speakers")
   - Flag any sections where attribution remains uncertain for manual review

6. **Create Find-and-Replace Commands**
   If corrections are systematic, provide exact find-and-replace commands:
   - "Replace all 'Speaker 3:' with 'Speaker 2:' in lines 145-230"
   - "Replace 'Speaker 1' with 'John Smith' throughout document"

**Priority**: Focus on errors that significantly impact readability and comprehension. Minor labeling inconsistencies that don't affect meaning can be noted separately.

Please return: (1) Summary of errors found, (2) Specific correction recommendations, (3) Fully corrected transcript, (4) Any uncertain sections flagged for manual review.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with professional-grade accuracy.
---
```

## Best Practices

**Provide context:** Any known speaker information (names, roles, voice characteristics) dramatically improves correction accuracy.

**Section processing:** For long transcripts (60+ minutes), process in 15-20 minute sections for more accurate corrections.

**Audio cross-reference:** For high-stakes documents (legal, medical, compliance), verify corrections against original audio.

**Iterative refinement:** Run prompt once for initial corrections, then re-run on corrected version to catch remaining errors.

## Use Cases

- **Multi-speaker meetings** - Fix attribution errors in 4+ person board meetings and team discussions
- **Panel discussions** - Correct confusion in conference panels and roundtable conversations
- **Podcast interviews** - Ensure accurate host/guest attribution for publication
- **Focus groups** - Consolidate and correctly attribute participant responses
- **Legal depositions** - Verify witness/attorney attribution for court records
- **Academic interviews** - Ensure accurate participant attribution for research analysis

## Time Savings

- **Manual speaker error correction**: 30-60 minutes per hour of multi-speaker transcript
- **AI-assisted with this prompt**: 5-10 minutes per hour of transcript
- **Especially valuable**: 4+ speaker meetings, panel discussions, group interviews

## Related Prompts

- **Transcript Formatting & Style Standardizer** - Apply consistent formatting after speaker correction
- **Technical Terminology Consistency Checker** - Verify terminology after speaker attribution fixes
- **Meeting Summarizer** - Extract action items with correctly attributed speakers
