MASTERING NARRATIVE: FILMS AND NCERT TEXTBOOKS ABSTRACTIVE SUMMARIZATION USING BART, T5 AND GPT

Movie Plot Summarizer

This project aims to summarize movie plot summaries using natural language processing techniques. It leverages the Hugging Face Transformers library for text generation and the NLTK toolkit for text processing tasks. Summaries are fetched from a dataset and Wikipedia, with a focus on extracting and generating concise plot summaries using T5 models. Evaluation metrics such as ROUGE scores (ROUGE-1) are calculated to assess the quality of generated summaries against reference summaries. Error handling and logging ensure robust performance even when data is unavailable or summaries cannot be generated.

Features:

    Fetches movie plot summaries from both a local dataset and Wikipedia.
    Uses T5 models for generating concise summaries from fetched content.
    Calculates ROUGE-1 scores to evaluate the quality of generated summaries.
    Error handling to manage cases where plot summaries are not available or cannot be fetched.

Usage:

    Users can input movie titles to retrieve and summarize plot summaries.
    ROUGE-1 scores are displayed to assess the quality of generated summaries.

