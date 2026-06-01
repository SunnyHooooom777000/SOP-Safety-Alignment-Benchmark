# SOP-Safety-Alignment-Benchmark
A small open-source benchmark and toolkit for evaluating LLM safety alignment in industrial SOP scenarios.
# SOP Safety Alignment Benchmark

SOP Safety Alignment Benchmark is an open-source project for evaluating how large language models respond to safety-critical industrial SOP scenarios.

The project focuses on situations where an AI assistant must avoid unsafe shortcuts, incorrect operational guidance, or responses that violate standard operating procedures.

## Motivation

Large language models are increasingly used in technical and industrial contexts. However, in safety-critical environments, a helpful answer is not always a safe answer.

This project aims to provide a lightweight benchmark for testing whether LLMs can follow industrial safety constraints, identify hazardous instructions, and generate safer alternatives.

## Project Goals

- Build a small dataset of industrial SOP safety scenarios
- Define safe and unsafe response examples
- Provide evaluation rubrics for LLM safety alignment
- Support future experiments with DPO, RLHF, Safe RLHF, and preference optimization
- Help researchers test whether models can follow safety constraints in practical industrial settings

## Repository Structure

```text
sop-safety-alignment-benchmark/
├── data/
│   ├── scenarios.jsonl
│   └── preference_pairs.jsonl
├── rubrics/
│   └── safety_rubric.md
├── examples/
│   └── sample_evaluation.md
├── scripts/
│   └── validate_dataset.py
├── README.md
└── LICENSE
