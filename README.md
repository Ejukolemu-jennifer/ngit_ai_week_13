# Week 13: LLM Benchmarking & Evaluation

## Task Overview
This project evaluates the performance of the updated Llama 3.1 8B model on content analysis tasks, specifically focusing on policy summarization and question-answering.

## Strengths of the Model
- **Precise Information Extraction:** The model successfully extracted specific constraints (like the 90-day password policy) without hallucinating facts.
- **Concise Formatting:** Bullet points generated during the summarization test were clean, scannable, and directly addressed the core rules.

## Limitations of the Model
- **Context Boundaries:** The model relies strictly on the provided context; complex policy interpretation might require explicit few-shot guiding prompts.
- **Dependency on Versioning:** Older API model references can deprecate quickly, requiring code updates to stable endpoints (e.g., transitioning from Llama 3 to Llama 3.1).
