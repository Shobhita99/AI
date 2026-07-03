# AI & NLP PROJECTS PORTFOLIO

================================================================================

## 1. Vision-Language Model using Hugging Face Transformers

Developed an Image Question Answering application using the Transformers pipeline to analyze images and generate text-based responses. Utilized a pretrained Vision-Language Model (VLM) that combines computer vision and natural language processing capabilities. Processed multimodal inputs consisting of an image URL and a user query to understand visual content and answer questions. Leveraged the high-level pipeline API from Hugging Face Transformers for efficient model loading, preprocessing, and inference. Demonstrated the application of transformer-based multimodal AI for image understanding, visual reasoning, and conversational question answering.

Skills Used: Python, Transformers, Hugging Face, Vision-Language Models (VLM), Computer Vision, NLP, Deep Learning, Multimodal AI, Image Question Answering.

================================================================================

## 2. Conversation Summarization using FLAN-T5

This project uses the FLAN-T5 Transformer model to automatically generate a concise summary of a conversation. The conversation text is first prefixed with "summarize:" so the model understands the required task. The tokenizer converts the conversation into numerical tokens that can be processed by the model. The FLAN-T5 model generates a summarized version of the conversation using its encoder-decoder architecture. Finally, the generated summary is decoded back into readable text and compared with a human-written summary to evaluate performance.

Skills Used: Python, NLP, Hugging Face Transformers, FLAN-T5, Tokenization, Text Summarization, Deep Learning, PyTorch.

================================================================================

## 3. Text-to-Speech Generation using gTTS

This project uses the gTTS (Google Text-to-Speech) library to convert text input into spoken audio files. The program creates an English speech output from the text "Hello, this is a test." and saves it as an MP3 file. It also demonstrates multilingual support by generating a French audio file for "Bonjour" using the French language setting. The slow=True parameter is used to produce slower speech, making pronunciation clearer for language learning applications. Finally, the generated audio files are played directly in Google Colab/Jupyter Notebook using IPython.display.Audio.

Skills Used: Python, gTTS, Text-to-Speech, Audio Processing, Multilingual Support, Jupyter/Colab Integration.

================================================================================

## 4. ROUGE Evaluation of Original vs PEFT (LoRA) Model

Loads the ROUGE evaluation metric using the evaluate library to measure summarization quality. Calculates ROUGE scores for the original FLAN-T5 model summaries against human-written reference summaries. Calculates ROUGE scores for the LoRA fine-tuned (PEFT) model summaries using the same reference summaries. Uses use_aggregator=True to return average scores and use_stemmer=True to improve word matching accuracy. Prints and compares ROUGE-1, ROUGE-2, and ROUGE-L scores to evaluate whether fine-tuning improved summarization performance.

Skills Used: Python, Hugging Face Evaluate, ROUGE Metrics, PEFT/LoRA, Model Evaluation, Text Summarization.

================================================================================

## 5. GPT-2 Recipe Generation and Evaluation System

Model Loading and Setup: Loaded the fine-tuned GPT-2 model and tokenizer using Hugging Face Transformers. The model was trained on an Indian food recipe dataset to generate recipe-related text.

Text Generation Function: Created a generate_text() function that converts input prompts into tokens and generates recipe text. Used Beam Search (num_beams=5) for better quality output and temperature to control creativity. Applied no_repeat_ngram_size=2 to reduce repetitive phrases.

Recipe Generation: Provided multiple recipe prompts such as Masala Karela and Tomato Puliogere. The model generated recipe instructions based on the learned patterns from training data.

Model Evaluation using BLEU: Calculated BLEU Score using NLTK to measure similarity between generated recipes and reference recipes. Applied a smoothing function to avoid zero scores when exact phrase matches are limited.

Model Evaluation using ROUGE: Computed ROUGE-1, ROUGE-2, and ROUGE-L scores to evaluate word overlap, phrase overlap, and sequence similarity. Calculated the average BLEU score and analyzed ROUGE metrics to assess overall text generation quality.

Interview Summary: "This module loads a fine-tuned GPT-2 model, generates recipe text from user prompts, and evaluates the generated content using BLEU and ROUGE metrics. Beam Search and temperature-based decoding improve generation quality, while BLEU and ROUGE scores measure how closely the generated recipes match reference recipes."

Skills Used: Python, Hugging Face Transformers, GPT-2, NLTK, BLEU Score, ROUGE Metrics, Model Evaluation, Text Generation, Fine-tuning.

================================================================================

## 6. AI Health Assistant Chatbot

Developed an AI-powered healthcare chatbot using the Phi-1.5 Large Language Model (LLM) to answer general health-related questions. Integrated the model with Gradio to create an interactive and user-friendly web interface for real-time conversations. Loaded the fine-tuned model and tokenizer from Google Drive and optimized inference using PyTorch with GPU support. Implemented text generation techniques such as Top-K Sampling and Top-P Sampling to produce natural and relevant responses. Designed features like question submission, response display, and server management, enabling efficient deployment and testing of the chatbot.

Skills Used: Python, Generative AI, Large Language Models (LLMs), Hugging Face Transformers, PyTorch, Gradio, NLP, Model Inference, GPU Computing, Prompt Engineering.

================================================================================

SKILLS SUMMARY

Programming Languages: Python

Frameworks and Libraries: Hugging Face Transformers, PyTorch, Gradio, NLTK, gTTS

AI/ML Techniques: Deep Learning, NLP, Computer Vision, Multimodal AI, Generative AI, LLMs, Model Fine-tuning (PEFT/LoRA)

Models: VLM, FLAN-T5, GPT-2, Phi-1.5

Evaluation Metrics: ROUGE-1, ROUGE-2, ROUGE-L, BLEU Score

Tools: Jupyter/Colab, GPU Computing, Tokenization, Prompt Engineering
