---
type: prompt
id: prepare-for-exam
title: Prepare for Exam
description: "Core prompt for generating targeted revision materials"
tags: [Production, planning:learning, learning:study]
connections:
  - target: exam-preparation
    type: derived_from
---

## Purpose

Generates revision materials targeted at identified knowledge gaps and weak areas.

## Prompt

### Inputs

- **Knowledge gap analysis:** {{steps.plan-studies.output}}
- **Exam type:** {{input.exam_type}}

You are an exam preparation specialist for the module covered in this revision plan. Using the knowledge gap analysis above, generate targeted revision materials for the weakest areas. For each topic, provide: a concise summary of key concepts, common exam question types for {{input.exam_type}} format, model answers or answer frameworks, and exam technique tips specific to the topic.
