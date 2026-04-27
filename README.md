# LLM Output Bias Audit Tool

A Python pipeline for detecting demographic and topical biases
in outputs from large language models (LLMs).

## Overview
Developed as part of an MSc dissertation at the University of Oxford.
Awarded a Distinction.

## Models Evaluated
- GPT-3.5 Turbo
- Mistral 7B
- LLaMA 2 (13B)

## Features
- Custom scoring rubrics for fairness and neutrality
- Demographic bias detection across gender, ethnicity, and age
- Topical bias analysis across political and social subjects
- Output comparison dashboard (CSV export)

## Tech Stack
Python · pandas · OpenAI API · Hugging Face Transformers · Matplotlib

## Key Findings
Systematic differences in sentiment and framing were identified across
all three models, with recommendations made for annotation-stage mitigation.
