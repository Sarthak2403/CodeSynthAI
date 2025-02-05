# CodeSynthAI Project

## Overview

AgenticAI is an automated AI-driven code generation and execution framework. It leverages OpenAI models and the `autogen` library to create agents that can generate, execute, and evaluate Python scripts. This project demonstrates the generation of financial data visualizations, such as stock performance comparisons.

## Features

- Uses OpenAI's GPT models for AI-driven code generation.
- Implements `autogen` to manage autonomous AI agents.
- Supports automated Python script execution with a local command-line executor.
- Generates stock performance plots for financial analysis.
- Saves visualizations as image files for later reference.

## Installation

To set up the environment, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone <repository_url>
   cd agenticai
   ```

2. **Create a Conda Virtual Environment**

   ```bash
   conda create --name agenticai_env python=3.10
   conda activate agenticai_env
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**
   Create a `.env` file and add your OpenAI API key:

   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Usage

To run the notebook, execute:

```bash
jupyter notebook agenticai.ipynb
```

## How It Works

1. Loads OpenAI API key from `.env`.
2. Configures an AI-powered `code_writer_agent` to generate Python scripts.
3. Sets up a `code_executor_agent` to execute the generated code.
4. Generates and saves a stock market visualization for NVDA and TSLA.

## Output

- The script generates a stock gain plot for NVDA and TSLA Year-to-Date (YTD).
