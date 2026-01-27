# AI Prompting Guidelines

AI prompting is programming with words, not asking questions. Treat prompts as instructional specifications rather than conversational queries to a probabilistic completion engine.

## Core Principles

### Use Personas
Assign the AI a specific role and audience context to narrow focus and leverage expertise from a defined perspective.

- Define who the AI should be (e.g., "You're a senior site reliability engineer")
- Specify the context of the task
- This helps the AI draw from relevant domain knowledge

### Always Be Contexting (ABC)
Never assume the AI knows something. Missing context gets filled with guesses and hallucinations.

- Include all relevant facts, even ones that seem obvious
- Be specific and detailed without holding back information
- Give explicit permission to say "I don't know" when uncertain
- The more context provided, the better the output

### Define Output Requirements
Specify exactly what you want the output to look like.

- Format: lists, paragraphs, word count, structure
- Tone: professional, casual, technical, transparent
- Style constraints and structural preferences
- Any specific conventions to follow

### Use Few-Shot Examples
Provide 2-3 concrete examples of the desired output style.

- Teaches through demonstration rather than description
- Removes ambiguity in expectations
- Shows the AI exactly what success looks like

## Advanced Techniques

### Chain of Thought (COT)
Request step-by-step reasoning before arriving at a final answer. This helps the AI work through complex problems methodically.

- Ask the AI to "think through this step by step"
- Modern AI platforms often have "Extended Thinking" modes for this purpose

### Tree of Thought (TOT)
Request multiple solution approaches to be explored simultaneously.

- Ask for synthesis and evaluation of the best path
- Useful for complex problems with multiple valid approaches

### Adversarial Validation
Create competing perspectives that critique each other.

- AI excels at critiquing over original creation
- Use this to validate and improve initial outputs
- Have the AI review its own work from a different angle

## Process Workflow

Before writing a prompt:

1. Think clearly about what you actually need
2. Write specifications in a notebook first if needed
3. Ask yourself: "Could a human succeed with this information?"
4. If the answer is no, add more clarity and context

## Key Insight

All prompting problems are thinking problems. If your prompt doesn't work, the issue is usually unclear thinking about what you actually want. Clarify your own thinking first; the AI mirrors your clarity level.

## References

### Academic Papers
- [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/pdf/2201.11903)
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/pdf/2305.08291)
- [Adversarial Validation Research](https://arxiv.org/pdf/2410.04663)

### Resources
- [Prompt Engineering Guide](https://promptingguide.ai/)
- [Why Context is Everything](https://medium.com/@unstitution21/why-context-is-everything-a1db99b28671)
- [The Ultimate Guide to AI Prompting (Video)](https://youtube.com/watch?v=pwWBcsxEoLk)

### Patrick posts
- [How to rock: The Ultimate Guide to Creating Better AI Prompts](https://patrickelectric.work/blog/2025/ultimate-guide-to-creating-better-ai-prompts/)
