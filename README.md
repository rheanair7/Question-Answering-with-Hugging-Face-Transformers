# Question-Answering-with-Hugging-Face-Transformers
This project implements an interactive Question Answering (QA) system using pre-trained transformer models from the Hugging Face library. The application takes a paragraph (context) and a user-generated question, then returns the most likely answer from the context using state-of-the-art NLP techniques. It's a simplified but foundational setup that demonstrates how powerful language models can extract and reason over textual information.
# Overview
Question Answering (QA) is a key task in Natural Language Processing (NLP) that involves extracting an accurate answer to a given question from a provided context passage. This project uses a pre-trained model fine-tuned on the SQuAD 2.0 dataset, which enables it to handle both answerable and unanswerable questions.Rather than building a full pipeline from scratch, this project leverages models like deepset/roberta-base-squad2, allowing for high performance even with minimal compute resources. The entire QA system runs locally and supports real-time interaction through the terminal, making it a great starting point for experimenting with transformers, LLMs, and downstream NLP tasks.
# Technologies
Language:	Python 3.x
NLP Library:	Transformers by Hugging Face
Model:	deepset/roberta-base-squad2
Deep Learning:	PyTorch
Environment: Google Colab
# How it works

The user is prompted to paste a paragraph of context (e.g., an article, story, or summary).

The user then asks a question about the content.

The system tokenizes both the context and question, feeds them to the model, and uses the output logits to find the span of the answer.

The answer is decoded and printed as natural language.
# Demo
Please enter the context paragraph:

Context:
The prefrontal cortex, located at the front of the brain, is responsible for higher-order functions such as decision-making, social behavior, and personality expression. It is also involved in planning complex cognitive behavior and moderating correct social behavior. Damage to this area may result in changes in personality, difficulty in planning or focusing, and inappropriate social responses. Recent studies suggest that the prefrontal cortex works closely with the limbic system, especially the amygdala, to regulate emotional responses.

Now ask your question based on the context:
Q: How does damage to the prefrontal cortex affect behavior?

Answer: changes in personality, difficulty in planning or focusing, and inappropriate social responses
