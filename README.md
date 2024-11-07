# AI-Application-Tamil-to-English-Translation-Summarization-and-Image-Generation

Multimodal AI Application: Tamil-to-English Translation, Summarization, and Image Generation
This project is a multimodal AI application that translates Tamil text to English, summarizes the translated text, and generates images based on the summary. It combines advanced NLP and image generation models with an easy-to-use Gradio interface.

Table of Contents
Overview
Features
Technologies Used
Installation
Usage
Project Structure
Models Used
Performance Analysis
Contributing
License
Overview
This application takes a Tamil text as input and performs the following operations:

Translation: Translates Tamil text to English.
Summarization: Summarizes the translated English text.
Image Generation: Generates an image from the summarized text.
The entire workflow is accessible through a user-friendly web interface built with Gradio.

Features
Tamil-to-English Translation: Uses the Helsinki-NLP/opus-mt-mul-en model to translate Tamil input to English.
Summarization: Summarizes the translated text using the facebook/bart-large-cnn model.
Image Generation: Generates an image from the summary using a Stable Diffusion model.
Interactive UI: Built with Gradio for an intuitive user experience.
Technologies Used
Hugging Face Inference API: For translation, summarization, and image generation.
Gradio: For creating an interactive web interface.
Python: Primary language for application development.
Requests: For making API calls to Hugging Face.
Stable Diffusion: For image generation from text descriptions.
CUDA (Optional): For GPU acceleration.
