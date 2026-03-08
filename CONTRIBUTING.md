# Contributing to Filament PHP v5 Expert Skill

Thank you for your interest in improving this skill! Contributions are welcome and appreciated.

## How to Contribute

### Reporting Issues

Found a mistake or outdated information? Please open an issue with:
- **Title**: Clear description of the issue
- **Description**: What's wrong and what should it be?
- **References**: Links to official docs if applicable
- **Version**: Which Filament/Laravel version does it affect?

### Improving Documentation

#### Typos & Clarity
1. Fork the repository
2. Create a branch: `git checkout -b fix/typo-in-section`
3. Make your changes
4. Commit: `git commit -m "Fix typo in Resource Structure section"`
5. Push: `git push origin fix/typo-in-section`
6. Open a Pull Request

#### Adding Examples
1. Ensure the example is from real Filament 5.3.2+ code
2. Include comments explaining complex patterns
3. Follow the existing code style and formatting
4. Add to the appropriate section with context

#### Adding Anti-patterns
1. Include both ❌ WRONG and ✅ CORRECT patterns
2. Explain why the wrong pattern is problematic
3. Reference official documentation when possible
4. Test the correct pattern works

### Adding New Content

#### New Best Practice
- Ensure it's v5-specific
- Include reasoning and benefits
- Add references to official docs
- Consider including a code example

#### New Generation Command
- Verify the command exists in Filament 5.x
- Include realistic output/usage
- Explain what the command does
- Show required parameters and options

#### Updated References
- Link to official Filament, Laravel, or Pest documentation
- Ensure links are not version-specific (use latest)
- Add description of what the link covers

## Development Guidelines

### Content Standards

1. **Accuracy**: Information must be accurate for Filament 5.x
2. **Current**: Use only v5 patterns, never mention v3/v4 deprecated patterns
3. **Type Safety**: Emphasize PHP 8.3+ type declarations
4. **Security**: Include security best practices and warnings
5. **Testing**: Show how to test the patterns with Pest/Livewire

### Code Examples

- Use realistic, working code
- Include necessary imports
- Add comments for complex logic
- Keep examples concise but complete
- Test before submitting

### Writing Style

- Be clear and concise
- Use active voice when possible
- Include reasoning behind recommendations
- Use emoji indicators (✅, ❌, ⚠️) consistently
- Format code blocks with language specification

### Git Workflow

1. **Fork** the repository
2. **Create branch** for your feature: `git checkout -b feature/description`
3. **Make changes** and test locally
4. **Commit** with clear messages: `git commit -m "Add new section: ..."`
5. **Push** to your fork: `git push origin feature/description`
6. **Open PR** with description of changes

### Commit Messages

Use clear, descriptive commit messages:

```
Add new anti-pattern example for file visibility

- Added ❌ WRONG and ✅ CORRECT examples
- Explained why explicit visibility is required
- Referenced Filament documentation
```

Bad:
```
fix stuff
update readme
```

## Review Process

1. **Initial Review**: Maintainer reviews for accuracy and completeness
2. **Feedback**: Request changes if needed
3. **Testing**: Verify examples work with Filament 5.3.2+
4. **Approval**: Merge when ready
5. **Release**: Updated skill available within 24 hours

## Questions?

- Open an issue with label `question`
- Check existing issues and discussions
- Reference the Skill Content Structure in README.md

## Code of Conduct

This project welcomes contributions from everyone. Please be respectful and constructive in all interactions.

---

Thank you for helping improve this skill! 🎉
