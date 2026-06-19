# Humanizer Skill - Prompt Templates

## System Prompt

```
You are the Humanizer skill for Codex. Your role is to transform AI-generated content 
into natural, human-like text while strictly preserving the original meaning and intent.

Core Responsibilities:
1. Remove AI-generated patterns and robotic language
2. Enhance readability and natural flow
3. Preserve all factual accuracy and original meaning
4. Adapt tone based on context and audience
5. Maintain code functionality (never change logic)

CRITICAL: Never change the fundamental meaning, alter code logic, or remove important information.
```

## User Prompts - Documentation & README

### Humanize a README

```
Please humanize this README to sound more engaging and natural while keeping all technical accuracy intact.

Make it:
- More engaging and less robotic
- Clear and scannable
- Friendly but professional
- Action-oriented

Content to humanize:
{INSERT_CONTENT}

Provide the humanized version.
```

### Improve Technical Documentation

```
Rewrite this documentation to be clearer and more natural without losing technical accuracy.

Target:
- More readable and conversational
- Easier to follow
- Remove corporate jargon
- Maintain all technical details

Content:
{INSERT_CONTENT}

Provide the improved version.
```

## User Prompts - Academic & Professional Writing

### Humanize Academic Writing

```
Please rewrite this academic paragraph to sound more natural and less AI-generated 
while maintaining academic rigor and accuracy.

Keep:
- All factual information
- Technical terminology
- Main arguments
- Citations and references

Make it:
- More naturally written
- Better flowing
- Less robotic
- Appropriately formal

Content:
{INSERT_CONTENT}

Provide the humanized version.
```

### Professional Report/Presentation

```
Rewrite this report section to be more engaging and natural without losing professionalism.

Preserve:
- All data and statistics
- Key conclusions
- Important details
- Professional tone

Improve:
- Readability
- Flow and structure
- Remove AI patterns
- Add clarity

Content:
{INSERT_CONTENT}

Provide the improved version.
```

## User Prompts - Communication

### Humanize Email Draft

```
Please rewrite this email to sound more natural and personal while keeping it professional.

Keep:
- The main message and purpose
- All important information
- Professional tone
- Any specific details or dates

Make it:
- More conversational
- Friendly but formal
- Concise and clear
- Authentic sounding

Email draft:
{INSERT_CONTENT}

Provide the humanized email.
```

### Social Media Post

```
Rewrite this social media post to be more engaging, authentic, and natural.

Keep:
- Core message
- Any facts or statistics
- Call-to-action
- Key information

Make it:
- More engaging and relatable
- Authentic voice
- Conversational tone
- Punchy and clear

Content:
{INSERT_CONTENT}

Provide the humanized post.
```

## User Prompts - Code & Comments

### Humanize Code Comments

```
Rewrite these code comments to be clearer, more natural, and more like a real developer wrote them.

CRITICAL RULES:
- NEVER change any code logic or functionality
- Only modify the comments/documentation
- Make comments clear and concise
- Explain intent, not just what the code does
- Remove redundancy

Code:
{INSERT_CODE}

Provide the code with improved comments only.
```

### Improve Docstrings

```
Rewrite these docstrings to be more natural and helpful without changing code functionality.

Rules:
- Keep all parameter descriptions accurate
- Maintain return type information
- Remove verbose/robotic language
- Make them more readable
- Explain purpose clearly

Code with docstrings:
{INSERT_CODE}

Provide the improved version.
```

## User Prompts - Content Type Detection

### Auto-detect and Humanize

```
Please identify the content type and humanize this appropriately:

Content:
{INSERT_CONTENT}

Analyze:
1. What type of content is this?
2. What tone should it have?
3. Who is the target audience?
4. What key information must be preserved?

Then provide a humanized version that sounds natural and authentic.
```

## Content Type - Specific Prompts

### General Text

```
Make this sound more natural and less like it was written by an AI. 
Preserve all meaning and important details.

Original:
{INSERT_CONTENT}

Humanized version:
```

### Code Documentation

```
Rewrite this code documentation to be clearer and more natural:

Original:
{INSERT_CONTENT}

Requirements:
- Keep all technical accuracy
- Improve readability
- Make it sound human-written
- Maintain example accuracy
- Preserve all important details

Rewritten:
```

### README Content

```
Make this README section more engaging and natural while keeping technical accuracy:

Original:
{INSERT_CONTENT}

Goals:
- Sound engaging but professional
- Clear and scannable
- Natural language
- Remove AI patterns
- Keep all technical details

Improved:
```

## Tone-Specific Prompts

### Professional Tone

```
Rewrite in a professional but not stuffy tone.

Keep:
- Formal appropriateness
- Business clarity
- Authority and credibility
- Direct communication

Add:
- Friendliness and approachability
- Natural language
- Conversational flow
- Human touch

Content:
{INSERT_CONTENT}

Professional but friendly version:
```

### Casual Tone

```
Rewrite in a casual, conversational tone while keeping key information.

Make it:
- Relaxed and approachable
- Like talking to a friend
- Natural and authentic
- Still clear and informative

Content:
{INSERT_CONTENT}

Casual version:
```

### Engaging Tone

```
Rewrite to be more engaging, compelling, and interesting.

Add:
- Emotional resonance
- Action orientation
- Storytelling elements
- Reader interest

Preserve:
- Factual accuracy
- Key information
- Original meaning
- Important details

Content:
{INSERT_CONTENT}

Engaging version:
```

## Advanced Prompts

### Multiple Iterations

```
I want to humanize this content in multiple passes.

Pass 1 - Remove AI patterns and improve readability:
Pass 2 - Adapt tone to [TONE]:
Pass 3 - Final polish for [TARGET_AUDIENCE]:

Content:
{INSERT_CONTENT}

Provide each pass separately, then the final version.
```

### Before/After with Explanation

```
Humanize this and explain what you changed and why.

Original:
{INSERT_CONTENT}

Analysis:
- What AI patterns did you identify?
- What did you change?
- Why those changes?
- What did you preserve?

Humanized version:
{INSERT_CONTENT}

Explain your changes.
```

### Preserving Specific Elements

```
Humanize this content but PRESERVE these specific elements:
- {ELEMENT_1}
- {ELEMENT_2}
- {ELEMENT_3}

Content:
{INSERT_CONTENT}

Rewrite to sound more natural while keeping those elements unchanged.
```

## Response Format

All humanizer outputs should follow this format:

```
## Original Content
[Original text]

## Humanized Version
[Improved text]

## Changes Made
- [Change 1]
- [Change 2]
- [Change 3]

## Tone & Target
- Tone: [tone used]
- Target Audience: [audience]
- Content Type: [type]
```

## Quick Reference - Common Transformations

### "State-of-the-art" replacements
- "state-of-the-art" → "modern" / "latest" / "current"

### "Comprehensive" replacements
- "comprehensive implementation" → "full implementation" / "complete solution"
- "comprehensive guide" → "complete guide" / "full guide"

### "Facilitate" replacements
- "facilitate" → "help" / "enable" / "allow"
- "facilitate enhanced processing" → "improve processing" / "speed up processing"

### "In order to" simplification
- "in order to" → "to"

### "Aforementioned" removal
- "aforementioned" → remove or use "that" / "the"
- "the aforementioned system" → "that system" / "the system"

### Wordy phrase simplification
- "take into consideration" → "consider"
- "manifest" → "show" / "display"
- "it is noteworthy that" → direct statement
- "going forward" → remove or rephrase
- "at this point in time" → "now" / "currently"
- "due to the fact that" → "because"
