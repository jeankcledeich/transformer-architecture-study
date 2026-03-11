# Transformer Architecture Study

## Background
The Transformer (or Transformer model) is a deep learning architecture introduced in June 2017 by Ashish Vaswani and colleagues in the paper "Attention Is All You Need". It revolutionized natural language processing (NLP) by achieving state‑of‑the‑art results on machine translation tasks while being faster to train than previous recurrent models. Unlike recurrent or convolutional networks, the Transformer relies entirely on attention mechanisms to model dependencies between words, without using recurrence or convolutions.

Key components:
- **Multi‑Head Self‑Attention**: Allows the model to jointly attend to information from multiple representation subspaces.
- **Positional Encoding**: Provides order information to the model.
- **Feed‑Forward Networks**: Position‑wise fully connected layers after attention.
- **Layer Normalization and Residual Connections**: Ensure stable training.

The architecture consists of an encoder stack and a decoder stack, each typically with six identical layers. Transformers have become foundational for models like BERT, GPT, and Vision Transformers, extending beyond NLP to computer vision, speech recognition, and more.

## Key Technical Contributions (from "Attention Is All You Need")
- Introduced the Transformer architecture, a network based solely on attention mechanisms, eliminating recurrence and convolutions.
- Developed multi‑head self‑attention to capture information from multiple representation subspaces.
- Introduced positional encodings to provide order information to the model.
- Demonstrated superior translation quality (e.g., 28.4 BLEU on WMT 2014 English‑to‑German) with greater parallelism and significantly reduced training time.
- Showed the model’s generalization to other tasks such as English constituency parsing.

## Original Paper Authors
- Ashish Vaswani
- Noam Shazeer
- Niki Parmar
- Jakob Uszkoreit
- Llion Jones
- Aidan N. Gomez
- Łukasz Kaiser
- Illia Polosukhin