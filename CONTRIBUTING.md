# Contributing to BrassTranscripts AI Prompts

Thank you for your interest in contributing to the BrassTranscripts AI Prompts repository! This guide will help you add new prompts and maintain the dual-format structure and cross-linking system.

## Table of Contents

- [Overview](#overview)
- [Adding New Prompts](#adding-new-prompts)
- [Dual Format Requirements](#dual-format-requirements)
- [Cross-Linking Implementation](#cross-linking-implementation)
- [Repository Structure](#repository-structure)
- [Quality Standards](#quality-standards)
- [Testing and Validation](#testing-and-validation)

## Overview

This repository maintains **23 AI prompts** in dual formats (Markdown + YAML) with cross-linking integration to the BrassTranscripts website. Each prompt must be added in both formats and linked from the corresponding blog post or guide page.

### Current Prompt Categories

- **Executive & Business**: 5 prompts
- **Content Marketing**: 5 prompts
- **Legal Professional**: 5 prompts
- **General Content**: 8 prompts (including the master transcript processing prompt)

## Adding New Prompts

### Step 1: Create Markdown Version

Create a new file in `/prompts/markdown/` with the following structure:

```markdown
# [Prompt Name]

**Category:** [Category Name]
**Source:** [BrassTranscripts blog post or guide URL]
**Use Case:** [Brief description of what this prompt does]
**AI Tools:** [List of compatible AI tools]

## Description

[Detailed description of the prompt's purpose and capabilities]

## The Prompt

```
[Full prompt text here]
```

## Key Features

- [Feature 1]
- [Feature 2]
- [Feature 3]

## Use Cases

- **[Use Case 1]:** [Description]
- **[Use Case 2]:** [Description]

## Example Workflow

1. [Step 1]
2. [Step 2]
3. [Step 3]

## Advanced Variations

[Any specialized versions or modifications]

## Related Resources

- [Link to BrassTranscripts source page]
- [Other relevant resources]

---

*This prompt is part of the BrassTranscripts AI Prompts collection. For more prompts, see our [complete library](https://github.com/CopperSunDev/brasstranscripts-ai-prompts).*
```

### Step 2: Create YAML Version

Create a corresponding file in `/prompts/yaml/` with this structure:

```yaml
name: "[Prompt Name]"
category: "[Category Name]"
description: "[Brief description matching the markdown version]"
source_url: "[BrassTranscripts blog post or guide URL]"
use_cases:
  - "[Use case 1]"
  - "[Use case 2]"
ai_tools:
  - "[AI Tool 1]"
  - "[AI Tool 2]"
key_features:
  - "[Feature 1]"
  - "[Feature 2]"
prompt_template: |
  [Full prompt text - must match markdown version exactly]
workflow_steps:
  - "[Step 1]"
  - "[Step 2]"
specialized_variations:
  [variation_name]: "[Variation description]"
related_resources:
  - name: "[Resource Name]"
    url: "[Resource URL]"
tags:
  - "[tag1]"
  - "[tag2]"
```

### Step 3: File Naming Convention

Use kebab-case for all filenames:
- Markdown: `prompt-name-description.md`
- YAML: `prompt-name-description.yml`

Examples:
- `executive-meeting-minutes-prompt.md`
- `executive-meeting-minutes-prompt.yml`

## Dual Format Requirements

### Content Consistency

Both formats must contain:
- **Identical prompt text** - Word-for-word matching
- **Same use cases and features** - Consistent information
- **Matching source URLs** - Link to the same BrassTranscripts page
- **Compatible AI tools** - Same list of supported platforms

### Validation Checklist

Before submitting, verify:
- [ ] Markdown and YAML versions contain identical prompt text
- [ ] All metadata fields are consistent between formats
- [ ] Source URL links to correct BrassTranscripts page
- [ ] File names follow kebab-case convention
- [ ] Content follows repository quality standards

## Cross-Linking Implementation

### For Blog Posts (Markdown Files)

Add GitHub links to the blog post using this format:

```markdown
📖 [View Markdown Version](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/your-prompt-file.md) | ⚙️ [Download YAML Format](https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/yaml/your-prompt-file.yml)
```

### For React Components (Guide Pages)

Add GitHub links using React/JSX syntax:

```jsx
{/* GitHub Repository Links */}
<div className="mt-6 bg-blue-50 border border-blue-200 rounded-lg p-4">
  <h4 className="font-semibold text-blue-900 mb-3">📖 Get This Prompt from GitHub</h4>
  <p className="text-blue-700 text-sm mb-3">
    Access this prompt in different formats from our open-source repository:
  </p>
  <div className="flex flex-col sm:flex-row gap-3">
    <a
      href="https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/markdown/your-prompt-file.md"
      target="_blank"
      rel="noopener noreferrer"
      className="inline-flex items-center gap-2 px-4 py-2 bg-white text-blue-700 border border-blue-300 rounded-md hover:bg-blue-50 transition-colors text-sm font-medium"
    >
      📖 View Markdown Version
    </a>
    <a
      href="https://github.com/CopperSunDev/brasstranscripts-ai-prompts/blob/main/prompts/yaml/your-prompt-file.yml"
      target="_blank"
      rel="noopener noreferrer"
      className="inline-flex items-center gap-2 px-4 py-2 bg-white text-blue-700 border border-blue-300 rounded-md hover:bg-blue-50 transition-colors text-sm font-medium"
    >
      ⚙️ Download YAML Format
    </a>
  </div>
</div>
```

### Cross-Linking Placement

- **Blog Posts**: Add links at the end of each prompt section
- **Guide Pages**: Add links immediately after the main prompt template
- **Multiple Prompts**: Add individual links for each prompt in the post

## Repository Structure

```
brasstranscripts-ai-prompts/
├── README.md                          # Main repository overview
├── CONTRIBUTING.md                    # This file
├── LICENSE                            # MIT License
├── prompts/
│   ├── markdown/                      # Human-readable versions
│   │   ├── [category-prompt-name].md
│   │   └── ...
│   ├── yaml/                         # Machine-readable versions
│   │   ├── [category-prompt-name].yml
│   │   └── ...
├── schemas/
│   └── prompt-schema.yml             # YAML validation schema
└── examples/
    ├── api-usage/                    # API integration examples
    └── automation/                   # Automation examples
```

## Quality Standards

### Content Requirements

- **Professional Language**: Clear, professional tone throughout
- **Complete Information**: All sections filled out completely
- **Accurate Metadata**: Correct categories, tools, and source URLs
- **Tested Prompts**: All prompts should be tested with target AI tools

### Technical Requirements

- **Valid YAML**: All YAML files must pass schema validation
- **Valid Markdown**: Proper markdown formatting and syntax
- **Working Links**: All URLs must be functional and current
- **Consistent Naming**: Follow established naming conventions

### SEO Optimization

- **Descriptive Titles**: Clear, searchable prompt names
- **Rich Metadata**: Complete use cases and feature descriptions
- **Keyword Integration**: Natural use of relevant keywords
- **Cross-References**: Links to related prompts and resources

## Testing and Validation

### Before Submitting

1. **Test the Prompt**: Verify it works with stated AI tools
2. **Validate YAML**: Use the schema to check YAML structure
3. **Check Links**: Ensure all URLs are functional
4. **Review Content**: Proofread for clarity and accuracy

### Validation Tools

- **YAML Schema**: Use `/schemas/prompt-schema.yml` for validation
- **Link Checker**: Verify all external links work
- **AI Testing**: Test prompts with ChatGPT, Claude, etc.

### Common Issues

- **Mismatched Content**: Ensure markdown and YAML contain identical prompt text
- **Broken Links**: Check that source URLs are current and accessible
- **Invalid YAML**: Validate syntax and structure against schema
- **Missing Metadata**: Complete all required fields in both formats

## Update Requirements

### When Adding New Prompts

1. **Update README.md**: Increment total count (currently 23 prompts)
2. **Update Category Counts**: Adjust category totals if needed
3. **Add to Examples**: Include in automation/API examples if applicable
4. **Cross-Link**: Add GitHub links to source website page

### Version Control

- **Commit Message Format**: Use descriptive commit messages
- **Branch Naming**: Use feature branches for new prompts
- **Pull Requests**: Submit PRs for review before merging

## Getting Help

For questions or assistance:

1. **Check Examples**: Review existing prompts for format guidance
2. **Schema Reference**: Use YAML schema for structure requirements
3. **Website Integration**: Reference existing cross-linking implementations
4. **Documentation**: This guide covers most common scenarios

## Repository Maintenance

### Regular Updates

- **Prompt Testing**: Verify prompts work with latest AI tool versions
- **Link Validation**: Check that all source URLs remain functional
- **Content Updates**: Refresh prompts based on user feedback
- **Schema Evolution**: Update validation schema as needed

### Quality Assurance

- **Automated Testing**: Use CI/CD for YAML validation
- **Manual Review**: Human review of all new prompt content
- **User Feedback**: Monitor usage and incorporate improvements
- **Performance Tracking**: Measure cross-linking effectiveness

---

Thank you for contributing to the BrassTranscripts AI Prompts repository! Your contributions help make AI-powered transcript processing more accessible to everyone.