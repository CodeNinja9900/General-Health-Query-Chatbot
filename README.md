# General-Health-Query-Chatbot
Chatbot for General Health Queries
General Health Query Chatbot
1. Task Objective
The primary objective of this project is to develop an AI-powered chatbot capable of answering general health-related questions. The chatbot is designed to be friendly, clear, and safe, strictly avoiding specific medical advice or diagnoses. It is engineered to always recommend consulting a healthcare professional for personalized guidance, embodying principles of responsible AI.
2. Dataset Used
This project does not rely on a specific pre-trained dataset for health information in the traditional sense. Instead, it leverages the knowledge embedded within a pre-trained Large Language Model (LLM) to generate responses to user queries. The model's training data implicitly contains a vast amount of general knowledge, including health-related information, which it uses to formulate its answers.

3. Models Applied
   Large Language Model (LLM):
   Model Name: Mistral-7B-Instruct-v0.2
   Provider: Mistral AI (accessed via Hugging Face)
   Optimization: The model was loaded with 4-bit quantization using BitsAndBytesConfig (load_in_4bit=True, bnb_4bit_quant_type="nf4", bnb_4bit_use_double_quant=True) to optimize memory    usage   and allow it to run efficiently on resource-constrained environments like Colab's T4 GPU.

4. Key Results and Findings
    Successful LLM Integration: The Mistral-7B-Instruct-v0.2 model was successfully loaded and configured for text generation, demonstrating its capability to process and respond to health      queries.
    Effective Prompt Engineering: Through carefully crafted system prompts, the chatbot was guided to adopt the persona of a helpful medical assistant, providing general information while       adhering to critical safety guidelines.
    Robust Safety Filters: Implemented explicit instructions within the prompt and an appended disclaimer to ensure the chatbot does not give specific medical advice or diagnoses,               consistently directing users to consult healthcare professionals.
    Functional Chatbot Pipeline: A transformers.pipeline was established, enabling a seamless interaction flow from user query to model response, including chat template application and         response extraction.
    bd
