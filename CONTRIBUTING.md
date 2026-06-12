# Contributing to Electronics Playground

Thank you for your interest in contributing to the Electronics Playground repository! This document provides guidelines and instructions for contributing.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Pull Request Process](#pull-request-process)
- [Content Guidelines](#content-guidelines)
- [Commit Messages](#commit-messages)
- [Questions or Need Help?](#questions-or-need-help)

---

## 📖 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all. We expect all contributors to:

- Be respectful and inclusive
- Welcome newcomers and help them get started
- Focus on constructive criticism
- Respect differing opinions and experiences
- Report unacceptable behavior

### Expected Behavior

- Use welcoming and inclusive language
- Be patient and understanding
- Provide and accept constructive feedback
- Focus on what is best for the community

---

## 🤝 How to Contribute

### Getting Started

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/Electronics_Playground.git`
3. **Create** a new branch: `git checkout -b feature/your-feature-name`
4. **Make** your changes
5. **Commit** your changes (see [Commit Messages](#commit-messages))
6. **Push** to your branch: `git push origin feature/your-feature-name`
7. **Create** a Pull Request

### Types of Contributions

#### 📝 Documentation Improvements
- Fix typos and grammatical errors
- Clarify existing documentation
- Add missing explanations
- Improve formatting and structure

#### 💡 New Content
- Add new topics or concepts
- Create practical examples
- Write problem solutions
- Add diagrams and illustrations

#### 🐛 Bug Fixes
- Fix errors in existing content
- Correct conceptual mistakes
- Update outdated information

#### 🎨 Content Organization
- Reorganize topics for better flow
- Create index or navigation improvements
- Improve overall repository structure

---

## 🐛 Reporting Bugs

### Before Reporting

1. Check if the issue already exists
2. Verify you're using the latest version
3. Search in [GitHub Issues](https://github.com/devamitra-b/Electronics_Playground/issues)

### Reporting Process

**Create a new issue** with the following information:

```markdown
## Bug Description
Clear and concise description of what went wrong.

## Where Found
- Location: [e.g., `/03-number-systems/` or `README.md`]
- Section: [e.g., "Binary Conversions"]

## Expected vs Actual
**Expected**: What should happen
**Actual**: What actually happens

## Steps to Reproduce
1. Step one
2. Step two
3. ...

## Screenshots/Examples
If applicable, include images or code snippets.

## Context
- Browser/Tool: [if applicable]
- OS: [Windows/Mac/Linux]
- Other relevant info
```

---

## 💡 Suggesting Enhancements

### Before Suggesting

1. Check if the suggestion already exists
2. Search [GitHub Issues](https://github.com/devamitra-b/Electronics_Playground/issues)
3. Verify relevance to the repository scope

### Enhancement Proposal

**Create a new issue** with:

```markdown
## Enhancement Description
Clear description of the suggested improvement.

## Motivation
Why this enhancement is valuable.

## Proposed Solution
How you envision this being implemented.

## Alternative Approaches
Other ways this could be approached.

## Additional Context
Links, references, or examples.
```

---

## 📋 Pull Request Process

### Before Submitting

1. ✅ Ensure content is accurate and well-researched
2. ✅ Follow [Content Guidelines](#content-guidelines)
3. ✅ Check spelling and grammar
4. ✅ Follow [Commit Messages](#commit-messages) guidelines
5. ✅ Update relevant documentation

### PR Description Template

```markdown
## Description
Brief description of changes.

## Type of Change
- [ ] Documentation update
- [ ] New content
- [ ] Bug fix
- [ ] Enhancement
- [ ] Other: [specify]

## Related Issue
Fixes #[issue number] (if applicable)

## Changes Made
- Point 1
- Point 2
- Point 3

## Checklist
- [ ] I have read the CONTRIBUTING guidelines
- [ ] My content follows project conventions
- [ ] I have checked for duplicate issues/PRs
- [ ] Content is accurate and well-structured
- [ ] I have updated documentation if needed

## Additional Notes
Any additional context or considerations.
```

### Merge Criteria

PRs will be merged when:
- ✅ Content is accurate and well-researched
- ✅ Follows repository standards
- ✅ No conflicts with main branch
- ✅ Approved by maintainers
- ✅ Commit history is clean

---

## 📝 Content Guidelines

### File Naming Conventions

```
Good:
- number-systems.md
- logic-gates-basics.md
- 01-electrical-fundamentals/

Avoid:
- Number Systems.md (use hyphens, not spaces)
- LogicGates.md (use lowercase)
- folder (be descriptive)
```

### Markdown Formatting

#### Headings
```markdown
# Main Title (use once per document)
## Section Heading
### Subsection
#### Sub-subsection
```

#### Lists
```markdown
### Unordered List
- Item 1
- Item 2
  - Nested item
  - Another nested

### Ordered List
1. First step
2. Second step
   1. Substep
```

#### Code Blocks
```markdown
For inline code: `variable_name`

For code blocks:
\`\`\`language
code here
\`\`\`
```

#### Links and References
```markdown
[Anchor text](https://example.com)
[Internal file](./path/to/file.md)
[Internal heading](#heading-name)
```

### Content Structure

Each topic should include:

1. **Overview**: Brief introduction
2. **Concepts**: Main ideas and theory
3. **Examples**: Practical demonstrations
4. **Applications**: Real-world usage
5. **Practice Problems**: Exercises for learning
6. **References**: Additional resources

### Writing Style

- ✅ Clear and concise
- ✅ Technical but accessible
- ✅ Avoid jargon without explanation
- ✅ Use active voice
- ✅ Provide examples
- ✅ Proofread carefully

---

## 💬 Commit Messages

### Commit Format

```
<type>: <subject>

<body>

<footer>
```

### Type

- `docs:` Documentation and content changes
- `feat:` New features or content
- `fix:` Bug fixes or corrections
- `style:` Formatting, structure improvements
- `refactor:` Content reorganization
- `chore:` Maintenance tasks

### Subject Line
- Use imperative mood ("add" not "added")
- Don't capitalize first letter
- No period (.) at the end
- Limit to 50 characters

### Body
- Explain what and why, not how
- Wrap at 72 characters
- Separate from subject with blank line
- Use bullet points for multiple changes

### Examples

```
docs: add binary conversion examples

- Add detailed step-by-step examples
- Include common conversion techniques
- Add practice problems with solutions

Fixes #15
```

```
fix: correct typo in ohms-law section

Changed "resistence" to "resistance"
Updated related references
```

```
feat: add operational amplifier basics

New section covering:
- Op-amp characteristics
- Common configurations
- Applications in circuits
```

---

## ❓ Questions or Need Help?

### Getting Help

1. 📖 Check existing documentation
2. 🔍 Search [GitHub Issues](https://github.com/devamitra-b/Electronics_Playground/issues)
3. 💬 Start a [Discussion](https://github.com/devamitra-b/Electronics_Playground/discussions)
4. 📧 Contact the maintainer

### Useful Resources

- [GitHub Help](https://help.github.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Git Documentation](https://git-scm.com/doc)

---

## 🙏 Thank You!

Your contributions make this repository better for everyone. We appreciate:
- Your time and effort
- Thoughtful suggestions
- Quality content
- Community spirit

Whether you're fixing typos, adding examples, or suggesting improvements, your participation is valued!

---

**Last Updated**: June 12, 2026  
**Maintainer**: Devamitra B
