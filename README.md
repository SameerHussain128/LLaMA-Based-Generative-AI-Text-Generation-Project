# LLaMA-Based-Generative-AI-Text-Generation-Project

# Goal
The main goal of this project is to build a text-generation system using the Meta LLaMA 3.2-1B model, which generates human-like responses to given prompts.

# Objectives
1. Implement a transformer-based text generator using the LLaMA model from Hugging Face.
2. Optimize memory usage using BitsAndBytes (bnb) for 4-bit quantization, enabling efficient model loading.
3. Integrate tokenization & text pipeline for seamless text input and generation.
4. Fine-tune inference settings to ensure high-quality, coherent responses.
5. Deploy the model efficiently on GPUs with device_map="auto".


# Project Description
This project utilizes Meta's LLaMA 3.2-1B model for natural language text generation. The model is loaded using Hugging Face's Transformers library with 4-bit quantization for reduced memory consumption. The system takes a user prompt (e.g., "Job description of Generative AI") and generates coherent and contextually relevant text as output.

# Key Components
1. Hugging Face Transformers – Loading the pre-trained LLaMA model.
2. BitsAndBytesConfig – Enabling 4-bit quantization to optimize memory usage.
3. AutoTokenizer & AutoModelForCausalLM – Tokenizing text and generating responses.
4. Pipeline for Text Generation – Defining a text-generation pipeline.
5. Inference Process – Processing user input and generating meaningful responses.





This project utilizes Meta's LLaMA 3.2-1B model for natural language text generation. The model is loaded using Hugging Face's Transformers library with 4-bit quantization for reduced memory consumption. The system takes a user prompt (e.g., "Job description of Generative AI") and generates coherent and contextually relevant text as output.
