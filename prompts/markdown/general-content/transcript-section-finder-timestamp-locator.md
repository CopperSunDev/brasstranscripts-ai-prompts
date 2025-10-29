# Transcript Section Finder & Timestamp Locator

**Category**: General Content
**Difficulty**: Intermediate
**Estimated Tokens**: 1500-2500
**Version**: 1.0.0

## Description

Long transcripts (60+ minutes, 10,000+ words) are difficult to navigate manually. This prompt quickly locates specific topics, quotes, discussion sections, or key moments using semantic search, timestamp extraction, and intelligent topic clustering—eliminating the need to manually scan thousands of lines.

## The Prompt

```text
I have a long transcript and need to locate specific sections, topics, or quotes. Please help me find and extract the relevant portions with accurate timestamps:

**Full Transcript:**
[PASTE YOUR TRANSCRIPT HERE]

**What I'm Looking For:**
[DESCRIBE - e.g., "Discussion about Q4 budget", "When Sarah mentioned the project deadline", "All references to customer feedback", "The section where technical specifications were discussed"]

Please analyze the transcript and:

1. **Locate Relevant Sections**
   - Find all sections discussing the specified topic or containing the mentioned content
   - Identify both explicit mentions and related contextual discussions
   - Include nearby context (1-2 sentences before/after) for clarity
   - Note if topic appears multiple times throughout transcript

2. **Extract with Timestamps**
   For each relevant section found, provide:
   - **Timestamp**: Exact time marker from transcript (e.g., [00:15:32] or line numbers)
   - **Speaker**: Who is discussing this topic
   - **Quote**: The exact relevant passage with surrounding context
   - **Summary**: Brief 1-2 sentence summary of what's being discussed
   - **Duration**: How long this discussion segment continues (if determinable)

3. **Topic Clustering**
   - Group related discussions that appear at different times
   - Show progression of topic (e.g., "Initial mention at 00:05:12, detailed discussion at 00:23:45, follow-up at 00:47:20")
   - Identify if topic is resolved, left open, or scheduled for follow-up

4. **Related Topics Finder**
   Suggest related discussions you found that might be relevant:
   - Adjacent topics discussed in same time range
   - Cross-references to this topic from other sections
   - Supporting or contradicting information elsewhere in transcript

5. **Generate Navigation Map**
   Create a quick reference guide for this transcript:
   - **Major Topics**: List main discussion themes with timestamp ranges
   - **Key Decisions**: Highlight any decisions made with timestamps
   - **Action Items**: Extract any tasks assigned with who/when mentioned
   - **Important Quotes**: Notable statements worth referencing

6. **Create Searchable Index**
   For future reference, generate an index of key terms with all occurrence timestamps:
   - People mentioned (with each time they speak or are referenced)
   - Projects/Products discussed (with timestamp of each mention)
   - Numbers/Metrics referenced (with context and location)
   - Decisions and action items (with owners and deadlines)

**Search Priority:**
- Exact matches for specific quotes or phrases (highest priority)
- Direct topic discussions (high priority)
- Related contextual mentions (medium priority)
- Tangential references (low priority - note separately)

**Output Format Preference:**
[CHOOSE - "Chronological list", "Grouped by topic", "Table format", "Timeline view"]

Please return: (1) All relevant sections with timestamps and quotes, (2) Topic clustering showing how discussion evolves, (3) Navigation map for entire transcript, (4) Searchable index for future reference.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 96.4% average accuracy.
---
```

## Best Practices

**Ideal for long transcripts:** Most valuable for 30+ minute transcripts (4,500+ words) where manual scanning is time-consuming.

**Specific search terms:** The more specific your search description, the more accurate the results.

**Review full transcript first:** Use after initial full transcript review to understand overall structure.

**Build cumulative indexes:** For recurring meetings, maintain cumulative index tracking topics across multiple sessions.

## Use Cases

- **Meeting review** - Find action items, budget discussions, project updates across long board meetings
- **Research interviews** - Locate all participant mentions of specific experiences or themes
- **Podcast/video production** - Extract quotable moments, funny segments, or topic-specific clips with timestamps
- **Legal/compliance** - Find all references to contract terms, liability, or confidential information
- **Academic research** - Locate methodology discussions, theoretical framework references, participant quotes

## Time Savings

- **Manual searching in 60-minute transcript**: 25-45 minutes to find specific sections
- **AI-assisted with this prompt**: 2-4 minutes to locate all relevant passages
- **Especially valuable**: Multi-hour transcripts (conferences, depositions, focus groups)

## Related Prompts

- **Meeting Summarizer** - Extract action items and key decisions after locating sections
- **Blog Post Creator** - Use located sections to create focused content
- **Transcript Quality Analyzer** - Assess transcript quality before navigation
