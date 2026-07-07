# SC-ES
Beyond String Matching: Semantic Early Stopping for Cost-Efficient LLM Reasoning
This repository contains the code, data, and ablation study results for our project, which builds upon the methodology introduced in the paper "Escape Sky-high Cost: Early-stopping Self-Consistency for Multi-Step Reasoning".

📁 Repository Structure
Here is a guide to the key files and datasets included in this repository:

1. Main Implementation
Final_version_paper_code.ipynb The primary notebook for our project. It utilizes pre-generated results from the reasoning self-consistency tasks provided by the original paper (specifically GPT3.5_result and GPT4_result).

all_figures.zip Contains all the figures, plots, and visualizations generated during our experiments and final runs.

2. Model Evaluation Outputs
T0.7 GSM8K200.jsonl Results of the GPT-OSS model evaluated on a subset of 200 questions from the GSM8K dataset for the reasoning self-consistency task.

T0.7 startegy200.jsonl Results of the GPT-OSS model evaluated on a subset of 200 questions from the StrategyQA dataset for the reasoning self-consistency task.

3. Ablation Study
ablation-study (1).ipynb The notebook documenting our ablation experiments. This file analyzes the effects of varying window sizes and charts the performance tradeoffs.

ablation-results.zip The raw results and data points from the ablation study, detailing the accuracy vs. window size tradeoff curves across the datasets.
