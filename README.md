# English to French Translation Machine
A sequence-to-sequence LSTM model for translating English to French, implemented in PyTorch using the OPUS100 parallel corpus from Hugging Face Datasets.

## Features

- **LSTM Architecture**: Encoder-Decoder model with attention mechanism
- **Preprocessing**: Text cleaning and word-level tokenization
- **Vocabulary Handling**: Special tokens for padding, unknown words, and sequence control
- **Training Pipeline**: Full training loop with loss tracking
- **Inference**: Greedy decoding for translation generation
- **Hugging Face Integration**: Direct dataset loading from Hugging Face

## Dataset Details
- **OPUS100 English-French Parallel Corpus**
- Source: Hugging Face Datasets
- License: CC-BY 4.0
- Size: 1.1M sentence pairs

## Requirements

- Python 3.8+
- PyTorch 1.10+
- Hugging Face Datasets
- NLTK
- NumPy
- tqdm

