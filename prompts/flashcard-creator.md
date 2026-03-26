---
type: prompt
id: flashcard-creator
title: Flashcard Creator
description: "Task prompt for generating revision flashcards"
tags: [Production]
connections:
  - target: exam-preparation
    type: derived_from
---

## Purpose

Creates flashcards focused on exam-relevant content for active recall practice.

## Prompt

### Inputs

- **Revision materials:** {{steps.prepare-for-exam.output}}
- **Gap analysis:** {{steps.plan-studies.output}}

Create {{input.flashcard_count}} flashcards from the revision materials and gap analysis above, targeting the key concepts most likely to appear in the exam for this module. Each flashcard should have a clear question on the front and a concise answer on the back. Include a mix of definition cards, concept explanation cards, and application cards.

**Front:** [question]
**Back:** [answer]
