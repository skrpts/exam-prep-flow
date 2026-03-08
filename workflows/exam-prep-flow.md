---
type: workflow
id: exam-prep-flow
title: Exam Prep Flow
description: "Syllabus review, gap analysis, revision materials, and practice papers"
tags: [Production, Tested]
connections:
  - target: study-planning
    type: uses
  - target: exam-preparation
    type: uses
  - target: plan-studies
    type: uses
  - target: prepare-for-exam
    type: uses
  - target: flashcard-creator
    type: uses
  - target: practice-question-generator
    type: uses
---

## Overview

This workflow takes students from syllabus review through to exam readiness, identifying knowledge gaps and producing targeted revision materials.

## Pipeline Stages

### Stage 1: Syllabus Review

Invoke the **study-planning** skill to review the exam syllabus and create a structured revision schedule.

### Stage 2: Gap Analysis

Invoke the **plan-studies** prompt to identify knowledge gaps by comparing study progress against syllabus requirements.

### Stage 3: Revision Materials

Invoke the **exam-preparation** skill to generate targeted revision materials including flashcards and summaries for weak areas.

### Stage 4: Practice Papers

Invoke the **practice-question-generator** prompt to create exam-style practice papers for timed practice.

## Output

Exam preparation package containing:

- Structured revision timetable
- Knowledge gap analysis
- Targeted flashcards for weak areas
- Practice papers with model answers
