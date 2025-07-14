# 🧠 NLP Specialization – Colab Companion Notebooks

This course is derived from DeepLearning.ai's Natural Language Processing Specialization Course 1: Natural Language Processing with Classification and Vector Spaces ([Course on Coursera](https://www.coursera.org/specializations/natural-language-processing)).
It uses reworks the open-source notebooks from [@amanchadha](https://github.com/amanchadha/coursera-natural-language-processing-specialization) for Google Colab and pedagogic optimization, so that beginners can run a completely self-contained course within the Google Colab environment.

This repository reorganizes and upgrades the original course notebooks into **Colab-ready notebooks** with:
- Clean markdown structure
- All lessons and assignments in one file per week
- Gradio-powered interactive tools
- Coursera-style quiz self-checks

---

## 📘 Course 1: Classification and Vector Spaces
**Topics Covered:**
- Preprocessing tweets (tokenization, stemming, stopwords)
- Visualizing word frequencies
- Logistic regression for sentiment classification
- Feature extraction from text
- Training & evaluating on `twitter_samples`
- Gradio interface for live prediction
- Self-check quizzes

## 📅 Course 1 Roadmap

| Week | Topic                                   | Status     |
|------|-----------------------------------------|------------|
| 1    | Preprocessing & Logistic Regression     | ✅ Done     |
| 2    | Naive Bayes & Vector Representations    | ✅ Done       |
| 3    | Embeddings & Similarity                 | 🔒 Not started |
| 4    | Sentiment & Neural Networks             | 🔒 Not started |

---


## 📅 Week 1 — Natural Language Processing with Classification & Vector Spaces

| Day | Notebook | What you’ll build & learn | Open in Colab |
|-----|----------|----------------------------|----------------|
| L1  | C1W1_L1_Preprocessing_Teaching.ipynb | Clean & tokenise raw tweets, remove stop-words, apply stemming, then test everything on a toy sentence and an NLTK Twitter corpus. Ends with an interactive Gradio preprocessing playground. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/C1W1_L1_Preprocessing_Teaching.ipynb) |
| L2  | C1W1_L2_Visualizing_Word_Frequencies_Teaching_v2.ipynb | Turn tokens into frequency dictionaries, draw bar-plots & sentiment-split word-clouds, and explore any text live in a Gradio word-frequency app. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/C1W1_L2_Visualizing_Word_Frequencies_Teaching_v2.ipynb) |
| L3  | C1W1_L3_Logistic_Regression_Teaching_v4.ipynb | Convert tweets to simple (pos, neg) feature vectors, train & visualise a Logistic Regression classifier, plot its decision boundary, print accuracy + confusion matrix, and deploy a Gradio sentiment tester. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/C1W1_L3_Logistic_Regression_Teaching_v4.ipynb) |
| A1  | C1W1_A1_Logistic_Regression_Teaching.ipynb | Implement Logistic Regression from scratch with gradient descent. Includes guided TODOs, a cost-convergence plot, accuracy check, and a Gradio app that queries your very own model. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/C1W1_A1_Logistic_Regression_Teaching.ipynb) |

## 📅 Week 2 — Naive Bayes & Vector Representations 

| Day | Notebook | Description | Colab |
|------|----------|-------------|--------|
| L1  | `C1W2_L1_Likelihoods_Teaching_v2.ipynb` | Compute Naïve Bayes log-likelihoods for tweets, plot them in (log Pₚₒₛ, log Pₙₑg) space, draw 95 % confidence ellipses, and explore any tweet live in a Gradio likelihood visualizer. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/C1W2_L1_Likelihoods_Teaching_v2.ipynb) |
| A2  | `C1W2_A1_Naive_Bayes_Teaching_v2.ipynb` | Implement Naïve Bayes from scratch using Laplace smoothing. Preserves `### UNQ_Cx` autograder tags, includes local test assertions, and finishes with an interactive Gradio classifier. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specializ)

---

## 🧑‍💻 Attribution

This notebook is adapted from:  
[`amanchadha/coursera-natural-language-processing-specialization`](https://github.com/amanchadha/coursera-natural-language-processing-specialization)

All content © DeepLearning.AI. This is an educational adaptation only.

