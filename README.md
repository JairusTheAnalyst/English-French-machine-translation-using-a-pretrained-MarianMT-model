# English-French Machine Translation using MarianMT

This project demonstrates how to perform English to French machine translation using the pretrained MarianMT model from Hugging Face Transformers.

## Overview

The notebook showcases:

- Loading a pretrained MarianMT model for English to French translation
- Tokenizing input text
- Generating translations
- Evaluating the quality using BLEU score

## Requirements

- Python 3.7+
- transformers
- torch
- sentencepiece
- datasets
- evaluate
- sacrebleu

## Installation

Install the required packages:

```bash
pip install transformers torch sentencepiece datasets evaluate sacrebleu
```

## Usage

1. Open the notebook `notebook.ipynb` in Google Colab or Jupyter.
2. Run the cells in order.
3. The notebook will translate sample English sentences to French and compute a BLEU score.

## Model

Uses `Helsinki-NLP/opus-mt-en-fr` model.

## License

MIT