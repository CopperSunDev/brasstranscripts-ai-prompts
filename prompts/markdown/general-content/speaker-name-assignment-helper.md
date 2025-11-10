# Speaker Name Assignment Helper

**Category**: General Content
**Difficulty**: Beginner
**Estimated Tokens**: 800-1200
**Version**: 1.0.0

## Description

After automatic speaker identification labels your transcript as "Speaker 0," "Speaker 1," "Speaker 2," etc., you need to figure out which label corresponds to which person. This prompt analyzes your transcript to identify speakers using context clues, self-introductions, role indicators, and conversation patterns—saving you from manually listening to the entire recording.

## The Prompt

```text
I have a transcript with automatic speaker labels (Speaker 0, Speaker 1, Speaker 2, etc.) and need help identifying which label corresponds to which person. Please analyze the transcript and help me assign names to speaker numbers:

**Transcript with Speaker Labels:**
[PASTE YOUR TRANSCRIPT HERE]

**Known Information (if available):**
- Number of participants: [e.g., "4 people in total"]
- Participant names (if known): [e.g., "Sarah Chen, Mike Rodriguez, Alex Kim, Jordan Lee"]
- Meeting/conversation context: [e.g., "Product planning meeting", "Podcast interview with marketing expert", "Focus group about mobile app"]
- Any other helpful details: [e.g., "CEO leads the meeting", "Host introduces guest at start"]

Please analyze the transcript and:

1. **Identify Self-Introductions**
   - Find where speakers introduce themselves by name ("Hi, I'm Sarah", "This is Mike speaking")
   - Note any explicit name mentions in greetings or sign-offs
   - Identify instances where speakers refer to themselves by name

2. **Analyze Role Indicators**
   - Identify leadership patterns (who sets agenda, assigns tasks, makes decisions)
   - Detect expertise areas (who discusses technical topics, marketing, finance, etc.)
   - Note facilitation behavior (who asks questions vs. provides answers)
   - Recognize host/guest dynamics in interviews or podcasts

3. **Use Conversation Context Clues**
   - Track who responds to specific questions (e.g., "Sarah, what do you think?" followed by response)
   - Identify speakers through content ownership ("My team and I...", "In my department...")
   - Note references to roles or titles ("As CEO, I believe...", "From an engineering perspective...")
   - Recognize topic continuity (same speaker discussing related points throughout)

4. **Detect Relationship Patterns**
   - Identify reporting relationships (who defers to whom, who assigns tasks)
   - Note collaborative pairs (two speakers who frequently build on each other's points)
   - Recognize communication styles (formal vs. casual, technical vs. non-technical)

5. **Generate Speaker Identification Report**
   For each speaker label, provide:
   - **Most likely name**: Based on strongest evidence
   - **Confidence level**: High/Medium/Low
   - **Supporting evidence**: 2-3 specific quotes or context clues
   - **Alternative possibilities**: If uncertain, list other candidates

6. **Create Find-and-Replace Commands**
   Once identities are confirmed, provide exact commands:
   - "Replace all 'Speaker 0:' with 'Sarah Chen:' throughout"
   - "Replace all 'Speaker 1:' with 'Mike Rodriguez:' throughout"
   - Continue for all speakers identified

**Format preference:** Provide results in order from highest to lowest confidence, starting with speakers who have clear identifying information.

Please return: (1) Speaker identification summary with evidence, (2) Confidence levels for each assignment, (3) Find-and-replace commands for confirmed identities, (4) Suggestions for verifying uncertain assignments.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with automatic speaker identification.
---
```

## Best Practices

**Provide context upfront:** Meeting type, participant list, and roles dramatically improve identification accuracy.

**Start with beginning and end:** Introductions and conclusions often contain the clearest speaker identification cues.

**Cross-reference with audio:** For important transcripts, verify AI suggestions by listening to a few key moments where speakers are identified.

**Process systematically:** Identify obvious speakers first (those with clear self-introductions), then use their established patterns to identify others.

**Mark uncertainties:** When confidence is low, note these sections for manual verification rather than guessing.

## Use Cases

**Business Meetings**: Identify executives, managers, and team members in recorded strategy sessions or planning meetings.

**Research Interviews**: Distinguish interviewer from participant(s) in qualitative research, especially with multiple interviewees.

**Podcast Episodes**: Identify host(s) and guest(s) when creating show notes or searchable transcripts.

**Focus Groups**: Assign participant identifiers when analyzing group discussions for research or user testing.

**Training Sessions**: Identify instructor vs. participants in recorded training or educational content.

**Panel Discussions**: Distinguish between moderator and multiple panelists in conferences or webinars.

## Common Patterns

**Clear identifiers:**
- Self-introductions: "Hi, I'm Sarah, the product manager"
- Direct address: "Mike, can you share the numbers?" (next speaker is Mike)
- Role references: "As CEO, I think..." (identifies executive role)

**Subtle clues:**
- Topic ownership: Speaker who consistently discusses engineering is likely the technical lead
- Decision authority: Speaker who assigns tasks or makes final calls is likely the leader
- Facilitation: Speaker who asks most questions is likely meeting host or interviewer

**Red flags:**
- Speakers never mentioned by name (may need audio verification)
- Multiple speakers with similar speech patterns (harder to distinguish)
- Very short transcript with minimal context clues (may need additional information)

## Workflow

1. **Copy transcript** with speaker labels from your transcription service
2. **Gather known information** (participant names, meeting context, roles)
3. **Run prompt** with transcript and context
4. **Review results** focusing on high-confidence assignments first
5. **Verify uncertain cases** by spot-checking audio at suggested timestamps
6. **Execute find-replace** to update speaker labels with actual names
7. **Final review** to ensure assignments make logical sense throughout

## Tips for Better Results

**Include timestamps:** If your transcript has timestamps, mention them—they help verify identification.

**Note distinctive speech:** If you know someone has an accent, uses technical jargon, or has other distinctive patterns, mention it.

**Provide meeting agenda:** Knowing what topics were discussed and who was responsible helps match content to speakers.

**Start with obvious cases:** If you're certain about one or two speakers, share that—it helps identify others by elimination.

## Related Prompts

**After identification:**
- Use [Speaker Attribution Error Corrector](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/general-content/speaker-attribution-error-corrector.md) if speaker labels seem incorrect
- Use [Meeting Minutes Generator](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/executive-business/meeting-minutes-generator.md) to create formal documentation

**For better source material:**
- Review [Audio Quality Pre-Recording Checklist](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/general-content/audio-quality-pre-recording-checklist.md) for future recordings

## Source

This prompt is featured in the [Speaker Identification Complete Guide](https://brasstranscripts.com/blog/speaker-identification-complete-guide) on BrassTranscripts.com. Learn more about how speaker identification works and best practices for multi-speaker transcription.

## Contributing

Found a way to improve this prompt? Submit suggestions via [GitHub Issues](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/issues) or contribute directly with a pull request.

## License

This prompt is provided under the MIT License. Free to use, modify, and distribute for any purpose.
