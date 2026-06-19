# Humanizer Skill

**Version:** 1.0.0  
**Author:** fulezhen0618-arch  
**Category:** Content Enhancement, Writing Assistance  
**Status:** Active

## Overview

Humanizer is a Codex skill designed to transform AI-generated content into natural, human-like text. It removes robotic patterns, AI-generated templates, and overused phrases while preserving the original meaning and intent.

## Capabilities

### Primary Use Cases (by priority)

1. **README / Marketing Copy / Email / Social Media**
   - Transform AI-generated documentation into engaging, natural prose
   - Adapt tone for different platforms (professional, casual, engaging)
   - Remove redundant patterns and clichés

2. **Academic & Professional Writing**
   - Humanize essay paragraphs and research text
   - Make homework submissions sound natural
   - Enhance presentation scripts and reports

3. **Code Comments & Documentation**
   - Rewrite auto-generated comments to be clearer and more natural
   - Improve code clarity without changing functionality
   - Add personality to inline documentation

4. **Code Structure & Naming**
   - Suggest improved variable/function names
   - Recommend refactoring for readability
   - Preserve original logic and functionality

## What This Skill Does

- ✅ Removes AI-generated patterns and overused phrases
- ✅ Enhances readability and naturalness
- ✅ Preserves original meaning and intent
- ✅ Adapts tone based on context
- ✅ Suggests improvements without altering core logic
- ✅ Works with code, documentation, and plain text

## What This Skill Does NOT Do

- ❌ Change fundamental logic or functionality
- ❌ Alter factual content or data
- ❌ Plagiarize or produce low-quality output
- ❌ Generate completely new content from scratch

## Installation

### Via Codex Skill Installer

```bash
$skill-installer https://github.com/fulezhen0618-arch/humanizer-skill/tree/main/humanizer
```

### Manual Installation

1. Clone or download this repository
2. Copy the `humanizer` folder to your Codex skills directory
3. Restart Codex desktop
4. The skill will appear in the Skills menu

## Usage

### Basic Usage

1. Select content you want to humanize (code, text, documentation, etc.)
2. In Codex, invoke the humanizer skill
3. Provide context if needed (target audience, tone, content type)
4. Review and accept the humanized output

### Example Prompts

```
"Humanize this README to sound more engaging and less AI-generated"
"Make this code comment clearer and more natural"
"Rewrite this email to sound less formal and more personal"
"Improve this paragraph to flow better without changing the meaning"
```

## Configuration

The skill uses instruction-based processing. Configuration can be customized in `humanizer/instructions.yaml`:

- `tone`: natural, professional, casual, engaging, technical
- `preserve_logic`: true (for code)
- `target_audience`: general, technical, academic, business
- `remove_ai_patterns`: true

## Supported Content Types

- 📝 Markdown and documentation
- 💬 Email and messaging
- 📖 Academic and professional writing
- 💻 Code comments and docstrings
- 🐦 Social media posts
- 📊 Reports and presentations
- 📚 README files and guides

## Requirements

- Codex Desktop (Latest version)
- No external dependencies

## Support & Feedback

For issues, suggestions, or feedback:
- Open an issue: https://github.com/fulezhen0618-arch/humanizer-skill/issues
- Check documentation: See README.md

## License

MIT

## Changelog

### v1.0.0 (Initial Release)
- Core humanizer functionality
- Support for multiple content types
- Instruction-based processing
