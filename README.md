
# 📚 Knowledge-Enhanced QA with Harry Potter Dataset

## 🚀 Getting Started

### Step 1: Clone This Repository

```bash
git clone https://github.com/your-org/harrypotter-qa-rag.git
cd harrypotter-qa-rag
```

### Step 2: Open in Google Colab (Recommended)

- Open the main notebook (`notebook.ipynb`) via: [https://colab.research.google.com](https://colab.research.google.com/)
- Alternatively, paste this link into your browser and replace `<username>` and `<repo>`:

```
https://colab.research.google.com/github/<username>/<repo>/blob/main/notebook.ipynb
```

### Step 3: Enable GPU in Colab

1. Go to **Runtime > Change runtime type**
2. Set **Hardware accelerator** to **GPU**
3. Click **Save**

> If you prefer running locally, ensure Python ≥ 3.8 and install the requirements:
```bash
pip install -r requirements.txt
```

---

## 🎯 Task Overview

You are provided with:
- A **training set** (used as a source of domain knowledge)
- A **validation set** (used for evaluation)
- A **pretrained model** of your choice from Hugging Face 🤗

Your goal is to explore and implement **knowledge integration** strategies that improve performance on a QA task about the Harry Potter universe.

---

## 📊 Step 0: Plot Key Dataset Metrics

Explore and visualize:
- Question and answer length distributions
- Vocabulary size
- Named entity frequency (e.g., characters, spells, places)

Use plots (e.g., histograms, word clouds) to illustrate insights.

---

## 🧠 Step 1: Present Two Methods for Knowledge Integration

You must implement and compare **two approaches**:

1. **Fine-tuning** a pretrained language model using the training dataset.
2. **Retrieval-Augmented Generation (RAG)** using the training set as a knowledge base.

Use Hugging Face tools (e.g., `Trainer`, `pipeline`, `sentence-transformers`) where possible.

---

## 🧪 Step 2: Explain the Knowledge Integration Process

For each approach, provide a clear explanation:
- How knowledge from the training data is used
- Any preprocessing or architectural adjustments
- Hyperparameter choices (e.g., learning rate, top-k retrieval)
- Justification of model selection and design decisions

---

## 📈 Step 3: Evaluate and Justify Model Choice

Use the validation set to compare the models:
- Compute **BLEU score** (for surface accuracy)
- Compute **BERTScore** (for semantic similarity)
- Optionally include qualitative examples or error analysis

Clearly state which model you would choose and why.

---

## 🤖 Use of AI Assistants

You are allowed to use AI tools (e.g., **ChatGPT**, **Claude**, **Copilot**) to support your implementation.

Please include in your notebook:
- Which assistant(s) you used
- Why you chose them
- How they helped you (e.g., debugging, exploring strategies)

This helps us understand your problem-solving process.

---

## 📤 Submission Instructions

- Push your completed `notebook.ipynb` to your own GitHub repository
- Include in your repo:
  - This README (with your final design notes)
  - Any visualizations, outputs, or utility scripts

**Deadline:** _[insert deadline here]_

---

## 🙌 Tips

- Prioritize **clarity**, **reasoning**, and **well-structured code**
- Simplicity is appreciated—don’t over-engineer
- Thoughtful analysis and documentation matter more than maxed-out metrics

Good luck, and enjoy the journey through the wizarding world of QA! 🧙‍♂️🧙‍♀️
