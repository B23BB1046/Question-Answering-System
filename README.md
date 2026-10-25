# Question Answering System with PyTorch

A learning project that explores question answering with an LSTM-based neural network in PyTorch. The workflow covers preparing question–answer pairs, converting text into numerical representations, batching examples, and training a sequence model.

## Features

- Text cleaning and tokenization.
- A custom PyTorch dataset and DataLoader workflow.
- LSTM-based model training.
- Question-to-answer prediction experiments.
- A small question–answer dataset included in the repository.

## Repository contents

| File | Purpose |
|---|---|
| `Question_Answering_system_using_pytorch.ipynb` | Model and training notebook |
| `100_Unique_QA_Dataset.csv` | Example question–answer data |
| `Question_Answering_System_README (1).md` | Additional project notes |
| `README.md` | Main documentation |

## Getting started

```bash
git clone https://github.com/B23BB1046/Question-Answering-System.git
cd Question-Answering-System
```

Open the notebook in Jupyter or Google Colab, install the packages imported by its cells, and run the workflow from top to bottom.

## Approach

1. Load and clean the question–answer pairs.
2. Tokenize text and build vocabulary/index mappings.
3. Convert text into numerical sequences.
4. Create batches with a custom Dataset and DataLoader.
5. Train the LSTM model and inspect prediction examples.

## Important limitations

This is an experimental LSTM-based approach, not a production-grade conversational or retrieval-augmented QA system. A small dataset may limit generalization. For a stronger evaluation, use held-out data, compare exact-match/F1 where appropriate, inspect failure cases, and document the split strategy.

## Future improvements

- Add a pinned `requirements.txt` and one-command setup.
- Save/load the vocabulary and trained model for inference.
- Compare against a retrieval baseline.
- Include sample inputs, outputs, and error analysis.
