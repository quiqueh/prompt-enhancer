# Prompt Enhancer Quick Reference Guide

## Universal Prompt Enhancement Principles

1. **Be specific**: Concrete details yield better results than vague requests
2. **Provide context**: Include relevant background information
3. **Define scope**: Clarify what should be included and excluded
4. **Specify format**: Indicate structure, length, and presentation
5. **Include examples**: When possible, provide examples of desired output
6. **Define audience**: Specify who the content is for
7. **Set tone**: Indicate the desired voice and emotional quality
8. **Use constraints**: Limitations often lead to more creative and focused results
9. **Break complex requests into steps**: Number multi-part requests
10. **Request revisions clearly**: When iterating, explain what needs to change

## Quick Templates by Type

### General Purpose Template
```
I need [content type] about [topic] for [audience]. 
It should be [length] and written in a [tone] style. 
Focus on [specific aspects]. 
Include [specific elements].
Structure it with [format details].
```

### Creative Content Template
```
Write a [genre] [content type] about [topic/character/situation].
Style: [writing style/author reference]
Tone: [emotional quality]
Key elements: [required components]
Length: [word count/structure]
```

### Technical Writing Template
```
Create a [technical document type] about [technical topic] for [expertise level].
Focus on [specific technical aspects].
Include [specific technical elements].
Format with [structural requirements].
Use [specific terminology/standards].
```

### Conversational Template
```
Role-play as [character/expert] discussing [topic] with me.
Knowledge level: [expertise level]
Style: [conversational style]
Focus on [specific aspects of the topic]
Avoid [areas to exclude]
```

### Visual Description Template
```
Describe [subject] in detail. 
Focus on [visual aspects] and [sensory details].
Style: [descriptive approach]
Purpose: [how description will be used]
Include [specific elements]
```

### Step-by-Step Template
```
Explain how to [process/task] for [audience].
Prerequisites: [required knowledge/materials]
Difficulty level: [complexity]
Include [specific details/warnings/tips]
Format with [numbered steps/sections]
```

## Common Enhancement Elements

### Audience Specifications
- "For beginners with no prior knowledge"
- "For technical experts in the field"
- "For business executives with limited technical background"
- "For middle school students (ages 11-13)"
- "For creative professionals seeking inspiration"

### Tone Options
- "Formal and academic"
- "Conversational and approachable"
- "Professional but engaging"
- "Enthusiastic and motivational"
- "Serious and authoritative"
- "Humorous and light-hearted"

### Length Specifications
- "Concise, under 300 words"
- "Comprehensive, 1500-2000 words"
- "Brief summary in 3-5 bullet points"
- "Detailed exploration with 5-7 sections"
- "A 30-second elevator pitch"

### Format Options
- "As a numbered list"
- "In a problem-solution format"
- "Using headings and subheadings"
- "As a Q&A dialogue"
- "With a thesis statement and supporting arguments"
- "Following a chronological structure"

### Common Constraints
- "Without using technical jargon"
- "Including only information from the provided sources"
- "Using analogies for complex concepts"
- "With examples for each point"
- "In 5 steps or fewer"
- "Using specific terminology/vocabulary"

## Example Enhanced Prompts

### Before Enhancement
"Tell me about quantum computing."

### After Enhancement
"Create an introduction to quantum computing for undergraduate computer science students. Explain the basic principles using clear analogies, focus on practical applications being developed today, and address how it differs from classical computing. Include a brief section on quantum bits and superposition. Keep it informative but approachable, approximately 800 words, with section headings for easy navigation."

---

### Before Enhancement
"Write a sci-fi story."

### After Enhancement
"Write a near-future science fiction short story (800-1000 words) about the first human-AI collaborative art exhibition. The story should be told from the perspective of the human artist who has mixed feelings about the partnership. Use a contemplative tone with moments of wonder, focusing on themes of creativity, authenticity, and the evolving relationship between humans and artificial intelligence. Include sensory details about the exhibition space and the artwork created. The story should end on an ambiguous note that makes the reader think about the future of art."

---

### Before Enhancement
"How do I fix my code?"

### After Enhancement
"Help me debug the following Python function that's supposed to merge two sorted lists but isn't working correctly. I need you to:
1. Identify the logical errors in the code
2. Explain why these errors are causing the function to fail
3. Provide a corrected version with comments explaining the changes
4. Suggest a test case to verify the fix works

Here's my code:
```python
def merge_sorted_lists(list1, list2):
    result = []
    i = j = 0
    while i < len(list1) and j < len(list2):
        if list1[i] < list2[j]:
            result.append(list1[i])
            i += 1
        else:
            result.append(list2[j])
            j += 1
    return result
```"
