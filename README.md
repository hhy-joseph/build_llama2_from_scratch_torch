# MiniLlama2-Tutorial

Welcome to **MiniLlama2-Tutorial**! This repository is a comprehensive tutorial to build a large language model (LLM) from scratch using PyTorch. We'll create a smaller version of the Llama 2 model, covering everything from foundational concepts to deployment, with hands-on exercises in Jupyter notebooks. The tutorial uses traditional Chinese (HK) data from Lihkg for training, making it relevant for regional language processing.

## Overview

This tutorial is designed for aspiring ML engineers looking to understand and implement LLMs. Starting with basic concepts like tokenization and attention mechanisms, we'll progressively build a fully functional model, pre-train it, fine-tune it, and deploy it. Each lesson is accompanied by a Jupyter notebook with code, explanations, and exercises.

## Lesson Plan

- **Lesson 0: Setup and Data Preparation**
  Set up the environment (Google Colab or local venv) and retrieve 100 rows of Lihkg data.

- **Lesson 1: Introduction to Language Models and Transformers**
  Explore language models, transformer architecture, and Llama 2 overview.

- **Lesson 2: Tokenization and Embedding**
  Implement tokenization and embedding layers for text processing.

- **Lesson 3: Attention Mechanism**
  Build a single attention head and visualize attention weights.

- **Lesson 4: Multi-Head Attention and Transformer Block**
  Expand to multi-head attention and construct a full transformer block.

- **Lesson 5: Building the Language Model**
  Integrate components to create the complete model architecture.

- **Lesson 6: Pre-Training the Model**
  Pre-train the model on Lihkg data with training loops and analysis.

- **Lesson 7: Fine-Tuning the Model**
  Fine-tune the model for specific tasks and evaluate performance.

- **Lesson 8: Deployment and Hosting**
  Deploy the model for inference using a simple server.

## Prerequisites

- **Google Colab** (recommended) or a local Python environment (3.8+).
- Basic knowledge of Python and PyTorch.
- Internet access for package and data downloads.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/joseph-hhy/MiniLlama2-Tutorial.git
   cd MiniLlama2-Tutorial
   ```

2. **Google Colab Setup**
   * Open notebooks/Lesson0-Setup_and_Data_Prep.ipynb in Colab.
   * Run all cells to install packages and download the Lihkg dataset.

3. **Local Setup (Optional)**
   * Create and activate a virtual environment:
     ```bash
     python -m venv minillama2_env
     # Windows: minillama2_env\Scripts\activate
     # Mac/Linux: source minillama2_env/bin/activate
     ```
   * Install dependencies:
     ```bash
     pip install torch datasets pandas numpy matplotlib flask
     ```
   * Open notebooks in Jupyter:
     ```bash
     jupyter notebook
     ```

4. **Verify Data**
   * After running Lesson 0, ensure data/lihkg_sample.csv exists with 100 rows of Lihkg data.

## Getting Started

Start with Lesson0-Setup_and_Data_Prep.ipynb to set up your environment and download the dataset. Then proceed sequentially through the notebooks in the notebooks/ folder.

## Support the Project

If you find this tutorial helpful, consider supporting me! Buy me a coffee.

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-%23FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/josephhhy)


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

* Llama 2 by Meta AI (Llama 2 on Hugging Face).
* Lihkg dataset by AlienKevin (LIHKG dataset).
* PyTorch community for excellent documentation and tools.