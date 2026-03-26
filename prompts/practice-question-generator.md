---
type: prompt
id: practice-question-generator
title: Practice Question Generator
description: "Task prompt for generating exam-style practice questions"
tags: [Production]
connections:
  - target: exam-preparation
    type: derived_from
---

## Purpose

Generates practice questions that mirror the format and difficulty of actual exam papers.

## Prompt

### Inputs

- **Revision materials:** {{steps.prepare-for-exam.output}}
- **Gap analysis:** {{steps.plan-studies.output}}
- **Exam type:** {{input.exam_type}}
- **Module:** {{input.module_name}}

Generate {{input.question_count}} practice questions based on the revision materials and gap analysis above, using the {{input.exam_type}} exam format for the {{input.module_name}} module. Include a mix of question types appropriate for the exam format. For each question, provide a model answer and mark scheme showing how marks are allocated. Include timing guidance for each question based on the overall exam duration.
