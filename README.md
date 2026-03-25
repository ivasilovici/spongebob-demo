# SpongeBob Role-Playing — LLM Demo

Interactive demo built for a Deep Learning course project at UPV/EHU (2026).

This web app showcases how two open-source language models — **Gemma 4B** and **Qwen 4B** — attempt to imitate the personalities of SpongeBob and Squidward from SpongeBob SquarePants using three different prompting techniques:

- **Zero-shot**: no examples provided
- **Few-shot**: a few dialogue examples included in the prompt
- **System + Few-shot**: a character description in the system prompt combined with examples

For each dialogue input, the app displays the six generated responses side by side, along with a judge score (1–5) averaged from two LLM-as-a-judge evaluators. The gold standard (original line from the show) is also shown for reference.

## How to use

Select a character (Squidward or SpongeBob) and click **New example** to explore random dialogues from the dataset.

## Tech

Static HTML/CSS/JS — no framework, no backend. All responses are pre-generated and embedded directly in the page.
