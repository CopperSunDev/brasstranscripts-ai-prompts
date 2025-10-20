# Key Facts and Evidence Extraction System

**Category**: Legal Professional
**Difficulty**: Advanced
**Estimated Tokens**: 1600-2100
**Version**: 1.2.0

## Description

Systematically extract and organize all factual assertions, evidence references, and legal elements from deposition testimony. Perfect for comprehensive case preparation and evidence management in complex litigation.

## The Prompt

```text
Perform comprehensive fact extraction from this deposition transcript, organizing all factual assertions, evidence references, and legal elements for case preparation:

## Factual Assertions Catalog

**Undisputed Facts Established:**
For each clear factual assertion:
- **Fact:** [Specific factual claim]
- **Source:** [Page/line reference]
- **Context:** [Circumstances of this statement]
- **Significance:** [Why this fact matters legally]
- **Corroboration Needed:** [How to verify this fact]

**Disputed or Contradicted Facts:**
- **Claimed Fact:** [What witness claims]
- **Dispute Nature:** [Why this is questionable]
- **Alternative Versions:** [Other accounts of same fact]
- **Resolution Method:** [How to determine truth]

**Opinion vs. Fact Separation:**
- **Statement:** [Witness statement]
- **Classification:** [Fact/Opinion/Mixed]
- **Basis for Opinion:** [What supports witness opinion]
- **Admissibility Issues:** [Potential evidence problems]

## Evidence References and Documentation

**Documents Mentioned:**
- **Document Type:** [Contract, email, report, etc.]
- **Description:** [What witness said about document]
- **Relevance:** [How this relates to case issues]
- **Availability:** [Whether produced, location, access]
- **Authentication Issues:** [Problems with proving authenticity]

**Physical Evidence References:**
- **Item:** [Object, location, condition described]
- **Witness Knowledge:** [How witness knows about this]
- **Current Status:** [Where evidence is now]
- **Chain of Custody:** [Who has handled this evidence]

**Electronic Evidence:**
- **Type:** [Emails, texts, digital files, recordings]
- **Access Information:** [How witness accessed this]
- **Storage Details:** [Where this information is kept]
- **Technical Issues:** [Potential problems with electronic evidence]

## Legal Elements Analysis

**[Cause of Action] Elements:** [Adjust based on your case type]
- **Element 1:** [Legal requirement]
  - **Supporting Testimony:** [How witness testimony supports]
  - **Page References:** [Specific locations]
  - **Strength Assessment:** [How strong this support is]
  - **Additional Proof Needed:** [What else is required]

- **Element 2:** [Next legal requirement]
  - [Follow same structure]

**Damages Evidence:**
- **Economic Damages:** [Financial losses mentioned]
  - **Amount:** [Specific figures given]
  - **Calculation Method:** [How witness determined amount]
  - **Supporting Documentation:** [Records that back this up]

- **Non-Economic Damages:** [Pain, suffering, other intangible losses]
  - **Description:** [How witness described impact]
  - **Duration:** [How long effects lasted/will last]
  - **Comparison Points:** [Before and after comparisons]

## Witness Knowledge and Competency

**Personal Knowledge Areas:**
- **Direct Observation:** [What witness personally saw/heard]
- **Participation:** [Events witness was involved in]
- **Professional Expertise:** [Areas of claimed expertise]

**Hearsay and Secondhand Information:**
- **Source:** [Who told witness this information]
- **Context:** [When and why this was communicated]
- **Reliability Factors:** [Reasons to trust or doubt this information]
- **Admissibility Analysis:** [Whether this can be used at trial]

**Knowledge Limitations:**
- **Admitted Ignorance:** [What witness doesn't know]
- **Assumptions:** [What witness is guessing about]
- **Memory Problems:** [Areas of unclear or missing memory]

## Strategic Fact Analysis

**Facts Supporting Your Case:**
1. **Fact:** [Helpful fact established]
   - **Legal Significance:** [How this helps your case]
   - **Strength:** [How reliable this testimony is]
   - **Reinforcement Strategy:** [How to strengthen this evidence]

2. **Fact:** [Additional supporting fact]
   - [Follow same structure]

**Facts Favoring Opposition:**
1. **Problematic Fact:** [Fact that helps opposing party]
   - **Damage Assessment:** [How much this hurts your case]
   - **Challenge Strategy:** [How to undermine or limit this]
   - **Mitigation Options:** [Ways to reduce impact]

**Neutral or Undetermined Facts:**
- **Fact:** [Information that could go either way]
- **Development Strategy:** [How to shape this favorably]

## Discovery and Investigation Priorities

**High-Priority Follow-up:**
1. **Investigation Need:** [What requires immediate attention]
   - **Method:** [How to investigate this]
   - **Timeline:** [When this must be completed]
   - **Resources Required:** [Cost, time, expertise needed]

2. **Document Request:** [Records to subpoena or request]
   - **Source:** [Where these documents likely exist]
   - **Relevance:** [How these documents help case]

**Expert Witness Considerations:**
- **Expertise Needed:** [Type of expert required]
- **Opinion Areas:** [What expert should address]
- **Fact Dependencies:** [What facts expert needs for opinion]

## Admissibility Assessment

**Strong Admissible Evidence:**
- [Facts likely to be admitted at trial]
- [Why these will survive evidentiary challenges]

**Questionable Admissibility:**
- [Evidence with potential admissibility problems]
- [Objections likely to be raised]
- [Strategies for admission]

**Inadmissible but Useful:**
- [Information useful for investigation but not trial]
- [How to use this information strategically]

Please organize all extracted facts with precise transcript references and assess their relative importance to case success.

---
Prompt by BrassTranscripts (brasstranscripts.com) – Professional AI transcription with 95-98% accuracy.
---

Deposition transcript:
[PASTE YOUR BRASSTRANSCRIPTS OUTPUT HERE]
```

## Best Practices

**Database integration:** Transfer AI-extracted facts into your case management system for easy access and cross-referencing.

**Collaborative review:** Share fact extraction with legal team for verification and strategic planning discussions.

**Opposing counsel preparation:** Anticipate how opposing counsel might use these same facts and prepare counter-strategies.

**Ongoing updates:** Revise fact analysis as new evidence emerges through discovery process.

## Use Cases

- **Complex litigation management** - Organize thousands of facts across multiple depositions and documents
- **Trial preparation** - Ensure all key facts are identified and properly supported for trial presentation
- **Discovery planning** - Identify gaps requiring additional investigation or document requests
- **Settlement negotiations** - Compile strongest facts to support settlement position
- **Expert witness coordination** - Provide factual foundation for expert opinions and testimony
- **Appeal preparation** - Organize facts for appellate brief writing and record citations

## Example Output

### Factual Assertions Catalog

**Undisputed Facts Established:**

**Fact:** Contract was signed on March 15, 2023 at 2:30 PM
- **Source:** Page 45/Lines 8-12
- **Context:** Witness reviewing calendar entry during questioning about timeline
- **Significance:** Establishes precise timing for statute of limitations calculation
- **Corroboration Needed:** Calendar records, other attendee testimony

**Fact:** Payment of $50,000 was due within 30 days of contract execution
- **Source:** Page 67/Lines 15-18
- **Context:** Witness reading contract terms aloud
- **Significance:** Central to breach of contract claim regarding late payment
- **Corroboration Needed:** Contract document authentication

**Disputed or Contradicted Facts:**

**Claimed Fact:** "No verbal modifications to contract were ever discussed"
- **Dispute Nature:** Contradicts earlier testimony about phone call negotiations
- **Alternative Versions:** Page 112 describes detailed phone conversation about terms
- **Resolution Method:** Phone records, opposing party deposition testimony

### Evidence References and Documentation

**Documents Mentioned:**

**Document Type:** Original contract with handwritten modifications
- **Description:** Witness described seeing handwritten notes in margins
- **Relevance:** Proves contract modifications were contemplated
- **Availability:** Not yet produced in discovery
- **Authentication Issues:** Handwriting analysis may be required

**Electronic Evidence:**

**Type:** Email chain between parties discussing contract terms
- **Access Information:** Witness forwarded emails to personal account
- **Storage Details:** Saved in personal Gmail account
- **Technical Issues:** Personal email may raise privilege concerns

### Legal Elements Analysis

**Breach of Contract Elements:**

**Element 1:** Valid contract existed
- **Supporting Testimony:** Witness confirmed signing contract, understood terms
- **Page References:** Pages 23-25, 45-47
- **Strength Assessment:** Strong - witness has personal knowledge
- **Additional Proof Needed:** Contract authentication, consideration proof

**Element 2:** Defendant breached contract terms
- **Supporting Testimony:** Payment was 45 days late, outside contract terms
- **Page References:** Pages 78-82
- **Strength Assessment:** Moderate - depends on modification claims
- **Additional Proof Needed:** Payment records, bank statements

**Damages Evidence:**

**Economic Damages:** Lost interest on delayed payment
- **Amount:** $2,500 calculated at 6% annual rate
- **Calculation Method:** Witness used standard commercial lending rate
- **Supporting Documentation:** Bank statements showing borrowing costs

### Strategic Fact Analysis

**Facts Supporting Your Case:**

1. **Fact:** Contract explicitly stated "time is of the essence" for payments
   - **Legal Significance:** Eliminates excuse for late payment
   - **Strength:** Written contract language is unambiguous
   - **Reinforcement Strategy:** Highlight this language in summary judgment motion

2. **Fact:** Defendant made partial payment acknowledging debt
   - **Legal Significance:** Admission of liability, partial performance
   - **Strength:** Check records provide objective proof
   - **Reinforcement Strategy:** Expert witness on partial payment significance

**Facts Favoring Opposition:**

1. **Problematic Fact:** Witness admitted accepting late payments on previous contracts
   - **Damage Assessment:** Could establish course of dealing allowing late payment
   - **Challenge Strategy:** Distinguish based on "time is of essence" clause
   - **Mitigation Options:** Argue this contract explicitly changed prior practice

### Discovery and Investigation Priorities

**High-Priority Follow-up:**

1. **Investigation Need:** Locate original contract with handwritten modifications
   - **Method:** Formal document request, subpoena if necessary
   - **Timeline:** Must complete before summary judgment motion deadline (30 days)
   - **Resources Required:** Legal fees for motion practice if contested

2. **Document Request:** Complete email communications between parties
   - **Source:** Both parties' business and personal email accounts
   - **Relevance:** May show course of dealing and modification discussions

### Admissibility Assessment

**Strong Admissible Evidence:**
- Contract terms and payment schedules (business records exception)
- Bank records showing payment timing (authenticated business records)
- Witness's personal knowledge of contract negotiation and signing

**Questionable Admissibility:**
- Hearsay statements about what opposing party "intended" to do
- Witness opinions about contract interpretation (lay opinion limits)
- Personal email forwarded from business account (privilege issues)

**Inadmissible but Useful:**
- Settlement discussions mentioned in deposition (for investigation only)
- Attorney communications referenced by witness (privileged)
- Use for developing additional discovery requests and witness preparation

## Resources

- 📖 **Detailed Guide**: [Legal Professional AI Toolkit](https://brasstranscripts.com/blog/legal-professional-ai-toolkit-deposition-analysis-prompts#prompt-4-key-facts-and-evidence-extraction-system)
- 🎯 **All Prompts**: [BrassTranscripts AI Prompt Guide](https://brasstranscripts.com/ai-prompt-guide)
- 🎤 **Get Transcripts**: [Upload Your Audio](https://brasstranscripts.com/upload)

---

**Created by [BrassTranscripts](https://brasstranscripts.com)** - Professional AI transcription with 95-98% accuracy