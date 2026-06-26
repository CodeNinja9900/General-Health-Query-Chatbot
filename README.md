# General-Health-Query-Chatbot
Chatbot for General Health Queries
General Health Query Chatbot
This project develops a General Health Query Chatbot designed to provide friendly, clear, and general information about health-related questions. Built with a strong emphasis on safety and responsible AI, the chatbot is engineered to avoid giving specific medical advice or diagnoses, always recommending consultation with a healthcare professional.

Features
Large Language Model (LLM): Utilizes Mistral-7B-Instruct-v0.2 from Hugging Face, optimized with 4-bit quantization for efficient performance on GPU environments.
Prompt Engineering: Incorporates a robust system prompt to establish a helpful medical assistant persona and guide the model's responses.
Safety Filters: Explicitly configured to prevent the chatbot from offering medical advice or diagnoses, with an additional safety disclaimer appended to every response.
Dependencies: Leverages transformers, accelerate, and bitsandbytes for LLM interaction and optimization.
