# Research Plan

## Goal

The goal of this project is to test how GPT-4-class models perform in real-world situations where user prompts are messy, incomplete, interrupted, or written in normal everyday language.

## Background

A lot of AI testing uses clean, controlled prompts. That does not match how many people actually use these systems. Real users make typos, use slang, rely on voice-to-text, leave out details, upload files, change direction, and expect the model to still understand the job.

This project focuses on whether models can stay useful and reliable in those conditions.

## Research Areas

- Robustness
- Model exploration
- Misuse potential
- Alignment
- Practical AI workflows

## Test Categories

The test set will include:

1. Clear baseline prompts
2. Prompts with typos and misspellings
3. Prompts with missing context
4. Voice-to-text style errors
5. Multi-step task prompts
6. Uploaded file or image-based tasks
7. Conflicting instructions
8. Prompt-injection attempts inside user-provided text
9. Requests where the model must decide whether to answer, ask for clarification, or refuse

## Method

The project will compare regular model responses against fine-tuned model responses using the same test prompts. Each response will be evaluated with a scoring rubric focused on practical usefulness, reliability, safety handling, and recovery from unclear wording.

The point is to see whether fine-tuning improves real-world performance or only changes how the model sounds.

## Expected Outcome

The final result will be a practical report showing where models perform well, where they fail, and whether fine-tuning improves real-world reliability.
