COMPANY: CODETECH IT SOLUTIONS

NAME: NAVEEN.R

INTERN ID:CT08DY717

DOMAIN NAME: ARTIFICIAL INTELLIGENCE

DURATION: 8 WEEKS

MENTOR: NEELA SANTHOSH

DESCRIPTION:

Project Description:

🎯 Objective

The goal of this project is to demonstrate text generation using two approaches inside a Jupyter Notebook:

Pretrained GPT-2 (Transformer-based) for modern, high-quality text generation.

Custom LSTM (Recurrent Neural Network) trained on a toy dataset to illustrate sequence modeling.

This notebook helps learners understand how large pretrained models compare with small, educational models.

⚙️ How It Works
1. Environment Setup

Installs required libraries:

torch, transformers, accelerate for GPT-2.

tensorflow / keras for the LSTM.

Checks if GPU (CUDA) is available.

2. GPT-2 Text Generation (Transformer Model)

Loads the pretrained GPT-2 model and tokenizer from Hugging Face.

Encodes the user’s prompt into tokens.

Generates text by sampling next tokens using:

max_length (output size),

temperature (randomness),

top_k / top_p (nucleus or top-k sampling).

Decodes tokens back into text and prints the continuation.

3. LSTM Text Generation (Custom Model)

Uses a small sample text corpus (provided in the notebook).

Preprocesses text:

Tokenizes words,

Builds vocabulary (word2idx, idx2word),

Creates training sequences (input words → next word).

Defines and trains a Keras Sequential model:

Embedding → LSTM → Dense(softmax).

Generates text:

Starts with a seed sequence,

Predicts the next word repeatedly,

Produces a continuation of specified length.

4. Comparison

GPT-2 → fluent, high-quality output (but requires internet to download weights).

LSTM → simpler, repetitive, but useful for learning how text generation works internally.

🖼️ Tools & Technologies Used
Libraries

Transformers (Hugging Face) – GPT-2 pretrained model.

PyTorch – Backbone for GPT-2.

TensorFlow/Keras – For building and training the LSTM.

NumPy / Python – Data preparation.

Platform

Jupyter Notebook – Interactive step-by-step execution.

🔄 Workflow

Run Environment Setup – installs dependencies.

Run GPT-2 Section – generates text directly from pretrained model.

generate_gpt2("Write a short poem about rain", max_length=100)


Run LSTM Section – trains small LSTM model, then generate text.

sample_from_model("artificial intelligence is", gen_len=30)


Compare Outputs – observe differences between GPT-2 and LSTM.

📦 Model Details
GPT-2

Pretrained on large internet text (117M parameters).

Provides high-quality, human-like continuation.

Supports parameters: length, temperature, top-k, top-p.

LSTM

Small word-level model.

Trained only within the notebook (on toy corpus).

Educational purpose: shows how sequence models work step by step.

✅ Features

Side-by-side demonstration of Transformer vs RNN (LSTM) approaches.

Configurable generation settings.

Educational: shows preprocessing, training, and generation.

Runs entirely in a notebook, no external web app required.

OUPUT:

<img width="1160" height="411" alt="image" src="https://github.com/user-attachments/assets/8072638d-c71a-4a70-81c7-3b05cca4c169" />



<img width="1753" height="188" alt="image" src="https://github.com/user-attachments/assets/595be129-3139-4ff7-9157-c92b6c3b4d29" />


