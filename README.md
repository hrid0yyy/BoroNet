BornoNet: Bengali Speech Recognition

BornoNet is a fine-tuned Wav2Vec2 model for classifying Bengali speech into character labels (e.g., ত, অ, ক). Trained on ~25,625 audio samples, it achieves ~87.5% test accuracy. Deployed on Hugging Face with a Gradio Space for interactive inference.

Hugging Face Model: hrid0yyy/BornoNet

Gradio Space: hrid0yyy/BornoNet-Space

Features

Classifies Bengali speech into ~50 unique characters.
Built on facebook/wav2vec2-base with a custom classification head.
Supports 16kHz mono MP3 inputs.
Web-based inference via Gradio Space.
