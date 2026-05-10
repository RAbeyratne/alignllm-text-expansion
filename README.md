# AlignLLM: Addressing Short Answer Limitations in LLM-as-a-Judge Systems

This repository contains code and datasets related to the paper titled "AlignLLM: Addressing Short Answer Limitations in LLM-as-a-Judge Systems". 

## Keywords

LLMs-as-Judges, Case-alignment, Text Expansion

## Repository Structure

- `code/`: This directory contains the codebase for implementing / evaluating the metrics.
- `README.md`: This file provides an overview of the repository.

##
- ILRAlign and WILRAlign package (Case alignment): https://pypi.org/project/alignllm-case-alignment-package/

## Datasets

- SQuAD 1.1 master datset: https://huggingface.co/datasets/Ramitha/squad-master-600
- SQuAD 1.1 min-length answer inverted master datset: https://huggingface.co/datasets/Ramitha/squad-master-200-least-negative
- Answer length results dataset - https://huggingface.co/datasets/Ramitha/squad1.1-600-raw-results
- Min answer length original expanded results dataset - https://huggingface.co/datasets/Ramitha/squad1.1-minimum-200-positive-expanded-results
- Min answer length inverted expanded results dataset - https://huggingface.co/datasets/Ramitha/squad1.1-minimum-200-negative-expanded-results