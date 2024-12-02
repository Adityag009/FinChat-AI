# FinChat-AI

**FinChat-AI** is an advanced AI-powered project designed to analyze financial markets using Natural Language Processing (NLP) techniques. It leverages cutting-edge transformer models, such as [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b), fine-tuned with LoRA (Low-Rank Adaptation), to provide insights into financial data and sentiment.

## Features

- **Sentiment Analysis**: Accurately determines the sentiment (positive, neutral, negative) of financial news and market-related text.
- **Pattern Recognition**: Identifies technical patterns like the Inverted Head and Shoulders from textual market descriptions.
- **Fine-Tuned LoRA Weights**: The repository includes pre-trained LoRA weights for fine-tuning ChatGLM2-6B, enabling efficient deployment of the model with reduced computational overhead.
- **Customizable Prompts**: Users can input financial scenarios or market updates, and the model generates insightful analyses based on pre-trained knowledge and fine-tuning.
- **Transformer-based Architecture**: Uses Hugging Face’s `transformers` library for seamless interaction and deployment of models.

## Repository Content

- **`Finchat2.ipynb`**: The primary notebook demonstrating how to load the model, interact with it, and perform tasks such as sentiment analysis and pattern recognition.
- **`saved_model.zip`**: Contains fine-tuned LoRA weights, allowing users to replicate and further fine-tune the project on their datasets.
- **`README.md`**: This file provides an overview of the project, its features, and usage instructions.
- **Training Resources**: Scripts for training with LoRA and integrating with Meta-LLaMA-2 architecture.

## Model and Training Details

- **Base Model**: [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b)
- **Fine-Tuning**: Utilizes LoRA for efficient parameter updates during training.
- **Training Dataset**: Focused on financial data, market updates, and technical analysis descriptions.
- **Frameworks**:
  - `Hugging Face Transformers`
  - `PEFT` for LoRA
  - `PyTorch` for model deployment
