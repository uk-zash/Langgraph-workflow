# LangGraph Workflow Examples

This repository contains a collection of Jupyter notebook examples demonstrating various workflows using LangGraph, a library for building stateful, multi-actor applications with LLMs.

## Overview

LangGraph is a powerful framework for creating complex, stateful workflows that integrate large language models (LLMs) with custom logic. This project showcases different types of workflows including parallel processing, conditional branching, iterative loops, and LLM-based interactions.

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd LangGraph
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables by creating a `.env` file with your API keys (e.g., for Groq or other LLM providers).

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Workflows

### Core Workflows
- **test_installation.ipynb**: Basic setup and installation verification for LangGraph.
- **llm_workflow.ipynb**: Introduction to integrating LLMs into LangGraph workflows.
- **prompt_chaining.ipynb**: Demonstrates chaining multiple prompts in a sequential workflow.
- **bmi_workflow.ipynb**: Example of a simple calculation workflow (Body Mass Index).

### Parallel Workflows
Located in the `Parallel Workflow/` directory:
- **simpleParallel.ipynb**: Basic parallel execution of tasks.
- **withLLM.ipynb**: Parallel workflows incorporating LLM interactions.

### Conditional Workflows
Located in the `Conditional Workflow/` directory:
- **quadratic_equation.ipynb**: Workflow with conditional logic for solving quadratic equations.
- **llmBasedReview.ipynb**: Conditional workflow using LLM for content review and decision-making.

### Iterative Workflows
Located in the `Iterative Workflow/` directory:
- **workflow.ipynb**: Example of iterative processes with loops and feedback mechanisms.

## Project Structure

```
LangGraph/
├── .gitignore
├── README.md
├── requirements.txt
├── test_installation.ipynb
├── llm_workflow.ipynb
├── prompt_chaining.ipynb
├── bmi_workflow.ipynb
├── Conditional Workflow/
│   ├── quadratic_equation.ipynb
│   └── llmBasedReview.ipynb
├── Iterative Workflow/
│   └── workflow.ipynb
└── Parallel Workflow/
    ├── simpleParallel.ipynb
    └── withLLM.ipynb
```

## Usage

Each notebook can be opened and run individually in Jupyter. Start with `test_installation.ipynb` to verify your setup, then explore the other examples based on your interests.

## Dependencies

- langchain
- langgraph
- langchain-groq
- dotenv
- ipykernel

## Contributing

Feel free to contribute additional workflow examples or improvements to existing ones.

