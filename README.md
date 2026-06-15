# COGS-560-Project-LLMs-with-Perturbations
Research Project of Ezgi Bakır (student number 2740504) for the Course Cogs560-LLMs for Reasoning and Cognition 

This repository contains the dataset, prompts, model outputs, and code
for the term project "EVALUATING THE ROBUSTNESS OF GEMMA MODELS ON PERTURBED REASONING QUESTIONS: A COMPARATIVE STUDY".

## Contents
- `data/` — the 100-question dataset (English + Turkish, with solutions)
  and the 8-shot prompt examples
- `results/` — raw answers from the three models
- `code/` — the Python pipelines (local Ollama for Gemma 2 9B and
  Gemma 4 E4B; Google API for Gemma 4 31B)
- `report.pdf` — the full project report

## Models
- Gemma 2 9B (Ollama)
- Gemma 4 E4B (Ollama)
- Gemma 4 31B (Google API)
