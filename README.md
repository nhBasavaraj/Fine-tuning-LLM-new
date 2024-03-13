# Fine-Tune Gemma-2b-It

This project demonstrates the fine-tuning process for the Gemma-2b-It model for code generation tasks. Gemma-2b-It is a language model that can be fine-tuned for specific tasks using techniques like quantization and low-rank adapters (LoRA).

## Overview

The project consists of a Jupyter Notebook (`finetune_gemma_2b_it.ipynb`) that guides you through the following steps:

1. Prerequisites
2. Model Loading
3. Dataset Preparation
4. Applying LoRA
5. Training the Model
6. Sharing Adapters on the Hugging Face Model Hub
7. Testing the Fine-Tuned Model

## Files

- `finetune_gemma_2b_it.ipynb`: Jupyter Notebook containing the code for fine-tuning Gemma-2b-It.
- `README.md`: This file providing an overview of the project.
- `requirements.txt`: This is the requirements file. 

## Prerequisites

Before running the notebook, ensure you have the necessary prerequisites, including GPU support and required Python packages.

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
6. Open and run the `finetune_gemma_2b_it.ipynb` notebook in a suitable environment.

## Credits

- This project utilizes the Hugging Face Transformers library for model fine-tuning.
- Dataset used for fine-tuning: [TokenBender/code_instructions_122k_alpaca_style](https://huggingface.co/datasets/TokenBender/code_instructions_122k_alpaca_style)
