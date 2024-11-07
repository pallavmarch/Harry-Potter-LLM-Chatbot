# ⚡ Harry Potter Themed Language Model Chatbot ⚡

This project features a custom-trained chatbot capable of answering questions about the Harry Potter universe. Leveraging Hugging Face's transformers, langchain, and Gradio, the chatbot processes inputs to generate accurate and lore-based responses.

## 🚀 Project Overview
The Harry Potter LLM chatbot is built using a fine-tuned language model that interprets prompts and generates responses rooted in the Harry Potter world. From explaining magical concepts like Horcruxes to describing the Triwizard Tournament, this chatbot is designed for Harry Potter enthusiasts looking to explore its universe in an interactive way.

## 📦 Installation

Install the required packages:
```bash
pip install -q accelerate==0.21.0 peft==0.4.0 bitsandbytes==0.40.2 transformers==4.28.1 trl==0.4.7 pypdf langchain gradio
```

## 🛠️ Features
- **Text Generation**: Fine-tuned model generates answers to Harry Potter-themed questions.
- **Interactive Interface**: Utilizes Gradio to provide a user-friendly chatbot interface.
- **Customizable Style**: CSS for dark mode styling to enhance user experience.

## 🔧 How to Run

1. **Set up Google Colab**:
   - Clone the repository and set up Google Colab for execution.

2. **Configure the Environment**:
   - Load model dependencies and required configurations.
   - Set up Gradio for the interactive chatbot.

3. **Launch the Interface**:
   - Run the `demo.launch()` command in Google Colab. This will open a Gradio interface where you can type Harry Potter-related questions.

4. **Ask Questions!**
   - Use the Gradio interface to type in any Harry Potter question (e.g., “What is a Horcrux?” or “Describe the Triwizard Tournament.”) and get an AI-generated response.

## 📊 Model Configuration

- **Model**: NousResearch/Llama-2-13b-chat-hf
- **Quantization**: 4-bit configuration to optimize performance on limited resources.
- **Tokenizer**: Hugging Face tokenizer adapted to Harry Potter terminology.

## ⚙️ Gradio Interface

The Gradio UI is styled with dark mode and a themed color palette, creating an immersive experience for users.


Enjoy your magical chat experience! 🧙‍♂️
