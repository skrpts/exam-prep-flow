---
type: prompt
id: flashcard-creator
title: Flashcard Creator
description: "Task prompt for generating revision flashcards"
tags: []
connections:
  - target: exam-preparation
    type: derived_from
---

## Purpose

Creates flashcards focused on exam-relevant content for active recall practice.

## Prompt

Create {{count}} flashcards from the following study material, targeting the key concepts most likely to appear in the exam. Each flashcard should have a clear question on the front and a concise answer on the back. Include a mix of definition cards, concept explanation cards, and application cards.

**Front:** [question]
**Back:** [answer]
