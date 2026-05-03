# Urdu Emotion Detection using XLM-RoBERTa

## Overview
Fine-tuned XLM-RoBERTa model that detects emotions in Urdu text.
Addresses the critical NLP gap for Urdu — spoken by 230 million people.

## Emotions Detected
| Emotion | Urdu | Confidence |
|---------|------|------------|
| 😊 Happy | خوشی | 95% |
| 😢 Sad | اداسی | 77% |
| 😠 Angry | غصہ | 85% |
| 😨 Fear | ڈر | 64% |
| 😐 Neutral | عام | — |

## Model Performance
- Overall Accuracy: 88.9%
- Best F1 Score: 0.88
- Trained on CPU — no GPU required

## Tech Stack
Python · HuggingFace Transformers · XLM-RoBERTa · PyTorch · Gradio

## How to Run
pip install transformers torch gradio pandas scikit-learn

## Key Research Findings
- Transfer learning works excellently for low-resource Urdu NLP
- Neutral emotion hardest to detect
- Dataset size is main bottleneck for improvement

## Author
Dawood Ali — BS Computer Science
