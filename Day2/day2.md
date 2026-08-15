Prompt engineering is the practice of designing inputs that reliably guide a language model toward the output you want. A strong prompt usually layers five things in order:

Role — telling the model who to act as (e.g. "you are a senior copy editor") sets tone and expertise level.
Context — the background info the model needs but doesn't already have.
Task — a clear, specific instruction for what to actually do.
Examples — a few input/output pairs showing the pattern you want (few-shot prompting is one of the highest-leverage techniques there is).
Output format — telling the model exactly how to structure its answer (bullet points, JSON, XML tags, word limits, etc.).

Beyond structure, a few techniques consistently improve results: being explicit rather than assuming the model will infer intent, asking the model to "think step by step" for reasoning-heavy tasks, giving both positive and negative examples, and iterating — testing the prompt, seeing where it goes wrong, and refining.