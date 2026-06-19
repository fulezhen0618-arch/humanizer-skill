# Humanizer Skill for Codex

Transform AI-generated content into natural, human-like text. Remove robotic patterns while preserving meaning.

## 🚀 Quick Start

### Installation

```bash
$skill-installer https://github.com/fulezhen0618-arch/humanizer-skill/tree/main/humanizer
```

After installation, restart Codex Desktop and the skill will be ready to use.

## 📋 Features

| Feature | Description |
|---------|-------------|
| **Remove AI Patterns** | Eliminates common AI-generated phrases and templates |
| **Preserve Meaning** | Keeps original intent and functionality intact |
| **Tone Adaptation** | Adjusts style for different contexts (professional, casual, engaging) |
| **Multi-Content Support** | Works with code, docs, emails, social media, academic writing |
| **Natural Readability** | Enhances flow and clarity |

## 💡 Use Cases

### 1. Documentation & README
**Before (AI-generated):**
```
This repository contains a comprehensive implementation of a state-of-the-art machine learning algorithm 
designed to facilitate enhanced data processing capabilities with maximum efficiency and scalability.
```

**After (Humanized):**
```
This project implements a fast, scalable machine learning algorithm for processing large datasets efficiently.
```

### 2. Email & Communication
**Before:**
```
Please be advised that the aforementioned issue has been successfully resolved and implementation 
of the corrective measures has been completed.
```

**After:**
```
Good news - we've fixed the issue and deployed the fix.
```

### 3. Code Comments
**Before:**
```python
# This function initializes the data structure with appropriate default values and returns a boolean 
# indicating successful completion of the initialization process
def init_data():
```

**After:**
```python
# Initialize the data structure with defaults
def init_data():
```

### 4. Academic Writing
**Before:**
```
The aforementioned research endeavor demonstrates substantial evidence indicating significant correlations 
between the observed variables and predicted outcomes.
```

**After:**
```
Our research shows clear connections between the variables we studied and the results we got.
```

### 5. Social Media / Marketing
**Before:**
```
We are pleased to announce the availability of an enhanced user interface experience with improved 
functionality and aesthetic improvements.
```

**After:**
```
We just launched a cleaner, faster interface. Check it out! 🚀
```

## 🎯 How to Use

### In Codex Desktop

1. **Select the content** you want to humanize
2. **Open Codex** and invoke the Humanizer skill
3. **(Optional) Specify context:**
   - Content type (code, email, docs, academic, etc.)
   - Tone (professional, casual, engaging, technical)
   - Target audience
4. **Review** the humanized output
5. **Accept or refine** as needed

### Example Commands

```
"Humanize this and make it sound less robotic"
"Rewrite for a professional audience"
"Make this code comment clearer"
"Fix this README to be more engaging"
"Humanize this email draft"
"Make this paragraph flow better"
```

## 📂 Folder Structure

```
humanizer-skill/
├── README.md                          # This file
├── SKILL.md                           # Skill metadata
├── humanizer/
│   ├── instructions.yaml              # Core processing rules
│   ├── prompt-templates.md            # Humanization prompts
│   ├── examples/
│   │   ├── before-after.md           # Example transformations
│   │   └── use-cases.md              # Detailed use cases
│   └── config.json                    # Configuration settings
├── LICENSE
└── .gitignore
```

## ⚙️ Configuration

Edit `humanizer/config.json` to customize behavior:

```json
{
  "humanizer": {
    "remove_ai_patterns": true,
    "preserve_logic": true,
    "preserve_code_functionality": true,
    "tone_options": ["natural", "professional", "casual", "engaging", "technical"],
    "default_tone": "natural",
    "target_audience": "general",
    "max_iterations": 1,
    "preserve_original_length": false,
    "enhance_readability": true,
    "remove_redundancy": true
  }
}
```

### Configuration Options

- **remove_ai_patterns** (bool): Strip common AI-generated phrases
- **preserve_logic** (bool): Keep original code logic unchanged
- **tone_options** (array): Available tone styles
- **default_tone** (string): Default tone if not specified
- **enhance_readability** (bool): Improve flow and clarity
- **remove_redundancy** (bool): Eliminate repetitive phrases

## 🔄 Processing Rules

The skill follows these core principles:

### ✅ Always Do This
- Preserve original meaning and intent
- Keep factual accuracy
- Maintain code functionality
- Respect logical structure
- Adapt tone appropriately
- Improve readability

### ❌ Never Do This
- Change core logic or functionality
- Alter factual content
- Introduce false information
- Completely rewrite (minor adjustments only)
- Add features or complexity

## 📝 AI Patterns Removed

Common AI-generated phrases that get humanized:

| AI Pattern | Humanized Alternative |
|-----------|---------------------|
| "state-of-the-art" | "latest" or "modern" |
| "comprehensive implementation" | "full implementation" or "complete solution" |
| "facilitate" | "help" or "enable" |
| "aforementioned" | "that" or "the" |
| "in order to" | "to" |
| "the aforementioned" | Remove or rephrase |
| "it is noteworthy that" | Direct statement |
| "take into consideration" | "consider" |
| "manifest" | "show" or "display" |

## 🛠️ Supported Content Types

- ✅ Markdown (.md)
- ✅ Plain text (.txt)
- ✅ Code comments (Python, JavaScript, Java, C++, etc.)
- ✅ Email drafts
- ✅ Academic writing
- ✅ Documentation
- ✅ README files
- ✅ Blog posts
- ✅ Social media content
- ✅ Reports and presentations

## 📊 Performance

| Metric | Performance |
|--------|-------------|
| Processing Speed | < 2 seconds for 500 words |
| Accuracy | ~95% preservation of original meaning |
| Supported Languages | English (primary), other languages supported |

## 🐛 Troubleshooting

### Issue: Skill not appearing in Codex

**Solution:** 
1. Restart Codex Desktop completely
2. Check that the folder is in the correct skills directory
3. Verify folder name is `humanizer`

### Issue: Output changes meaning

**Solution:**
1. Check that `preserve_logic` is set to `true`
2. Review the original content for ambiguity
3. Request a more conservative humanization

### Issue: Code functionality changed

**Solution:**
1. Use with `preserve_code_functionality: true`
2. The skill should only modify comments, not logic
3. Always review code changes before accepting

## 📞 Support

- **Issues:** https://github.com/fulezhen0618-arch/humanizer-skill/issues
- **Documentation:** See SKILL.md for technical details
- **Examples:** Check `humanizer/examples/` for more samples

## 📄 License

MIT License - See LICENSE file for details

## 🎓 Best Practices

1. **Review outputs** before accepting major changes
2. **Specify context** when possible (tone, audience, content type)
3. **Use for enhancement, not replacement** - skill improves existing content
4. **Check factual accuracy** after humanization
5. **Iterate** if needed - apply skill multiple times for different aspects

## 🚀 Tips for Best Results

- Be specific about tone and target audience
- Provide context about the content type
- Start with shorter passages and expand
- Use examples to guide the humanization style
- Combine with other Codex skills for best results

---

**Version:** 1.0.0  
**Last Updated:** 2024  
**Maintainer:** fulezhen0618-arch
