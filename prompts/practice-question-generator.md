---
type: prompt
id: practice-question-generator
title: Practice Question Generator
description: "Task prompt for generating exam-style practice questions"
tags: []
connections:
  - target: exam-preparation
    type: derived_from
---

## Purpose

Generates practice questions that mirror the format and difficulty of actual exam papers.

## Prompt

Generate {{count}} practice questions in the style of {{exam_type}} based on the following syllabus topics. Include a mix of question types appropriate for the exam format. For each question, provide a model answer and mark scheme showing how marks are allocated. Include timing guidance for each question based on the overall exam duration.
