# MCQ-Generator-using-Hugging-Face

This project demonstrates how to generate multiple-choice questions (MCQs) from a given text using the Hugging Face Transformers library, specifically the `fill-mask` pipeline. The core idea is to mask important terms or concepts in a sentence and generate possible answer options using a pre-trained language model.

## Features

- Generates MCQs by masking key terms in input sentences.
- Uses a pre-trained model (`epfl-ml4ed/LernnaviBERT`) to predict plausible options.
- Dynamically creates a question with one correct answer and multiple distractors.
- Shuffles the options to ensure randomness in question formatting.

## Requirements

To run this project, you'll need the following libraries:

- Python 3.x
- [transformers](https://huggingface.co/docs/transformers/index) (Hugging Face library)
- torch (PyTorch)
- random (Python standard library)

You can install the required dependencies using `pip`:

```bash
pip install transformers torch
