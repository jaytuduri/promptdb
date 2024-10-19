# Contributing to PromptDB

We're excited that you're interested in contributing to PromptDB, our repository of AI prompts and system instructions! This document provides guidelines for contributions to ensure consistency and quality across the project.

## How to Contribute

1. Fork the repository
2. Create a new branch for your contribution
3. Make your changes
4. Submit a pull request

## Guidelines for Prompts and Instructions

When submitting new prompts or instructions, please adhere to the following:

1. **File Format**: Submit prompts and instructions as markdown (.md) files.
2. **Naming Convention**: Use clear, descriptive names for your files, following the pattern `system_[description].md` for instructions, e.g., `system_creative_writing.md` or `system_code_review.md`.
3. **Content Structure**:
   - Start with a brief description of the prompt/instruction's purpose
   - Provide the actual prompt or instruction
   - If applicable, include examples of expected input/output
   - Add any relevant tags or categories at the end of the file

4. **Categorization**: Place your file in the appropriate folder within `/instructions` (e.g., `/instructions/business`, `/instructions/developer`, `/instructions/education`) or `/prompts`. Create new subfolders if necessary, but try to fit within existing categories if possible.

5. **Use the Template**: For instructions, use the template provided in `/templates/instructions_template.md` as a starting point.

## Specific Contribution Guidelines

### For Instructions
- Place in the appropriate subfolder under `/instructions`
- Follow the naming convention: `system_[description].md`
- Use the template in `/templates/instructions_template.md`
- Include clear examples of how the instruction should be used

### For Prompts (Future)
- Place in the `/prompts` folder
- Follow a clear naming convention (to be determined)
- Include context on when and how to use the prompt

### For General Improvements
- Updates to `categories.md` or `models.md` in the `/general` folder should be well-justified and documented
- Improvements to existing files should maintain or enhance clarity and usability

## Updating Documentation
When making significant changes:
1. Update the README.md if your contribution affects the project structure or general information
2. Add an entry to the CHANGELOG.md file describing your changes

## Code of Conduct

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## Questions?

If you have any questions about contributing, please open an issue in the repository, and we'll be happy to help!

Thank you for your contributions to making PromptDB more accessible and effective!
