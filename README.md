# 🧠 NLP Specialization – Colab Companion Notebooks

This course is derived from DeepLearning.ai's Natural Language Processing Specialization, Course 1: Natural Language Processing with Classification and Vector Spaces ([Course link](https://www.coursera.org/learn/classification-vector-spaces-in-nlp/home/info).)
It reworks the open-source notebooks from [@amanchadha](https://github.com/amanchadha/coursera-natural-language-processing-specialization) [`amanchadha/coursera-natural-language-processing-specialization`](https://github.com/amanchadha/coursera-natural-language-processing-specialization), by making the core ideas of the course more intuitive with clear toy examples, markdown explanations, and **fully runnable Google Colab notebooks**.

This version is designed so you truly learn the *concepts* in the lessons. Assignments are optional: they often repeat the core material from the lessons, but let you implement parts yourself.

---

## 📘 Course 1: Classification and Vector Spaces

**Topics Covered:**
- Preprocessing tweets (tokenization, stemming, stopwords)
- Visualizing word frequencies
- Logistic regression for sentiment classification
- Naive Bayes classification
- Vector representations of words
- Word embeddings and analogies
- PCA & visualizing similarity
- Gradio apps for interactive learning
- Self-check quizzes

---

## 🗕️ Course 1 Roadmap

| Week | Topic                                   | Status     |
|------|-----------------------------------------|------------|
| 1    | Preprocessing & Logistic Regression     | ✅ Done     |
| 2    | Naive Bayes & Vector Representations    | ✅ Done       |
| 3    | Embeddings & Similarity                 | ✅ Done |
| 4    | Sentiment & Neural Networks             | 🔒 Not started |

---

## 🗕️ Week 1 — Natural Language Processing with Classification & Vector Spaces

| Day | Notebook | What you’ll build & learn | Open in Colab |
|-----|----------|----------------------------|----------------|
| L1  | `C1W1_L1_Preprocessing_Teaching.ipynb` | Clean & tokenise raw tweets, remove stop-words, apply stemming, then test everything on a toy sentence and an NLTK Twitter corpus. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week1/C1W1_L1_Preprocessing_Teaching.ipynb) |
| L2  | `C1W1_L2_Visualizing_Word_Frequencies_Teaching_v2.ipynb` | Turn tokens into frequency dictionaries, draw bar-plots & sentiment-split word-clouds. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week1/C1W1_L2_Visualizing_Word_Frequencies_Teaching_v2.ipynb) |
| L3  | `C1W1_L3_Logistic_Regression_Teaching_v4.ipynb` | Convert tweets to simple (pos, neg) feature vectors, train & visualise a Logistic Regression classifier, plot its decision boundary, print accuracy + confusion matrix, and deploy a Gradio sentiment tester. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week1/C1W1_L3_Logistic_Regression_Teaching_v4.ipynb) |
| A1  | `C1W1_A1_Logistic_Regression_Teaching.ipynb` | Course Assignment: Implement Logistic Regression from scratch with gradient descent. Includes guided TODOs, a cost-convergence plot, accuracy check, and a Gradio app that queries your very own model. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week1/C1W1_A1_Logistic_Regression_Teaching.ipynb) |



## 🗕️ Week 2 — Naive Bayes & Vector Representations 

| Day | Notebook | Description | Open in Colab |
|-----|----------|-------------|----------------|
| L1  | `C1W2_L1_Likelihoods_Teaching_v2.ipynb` | Compute Naïve Bayes log-likelihoods for tweets, plot them in (log Pₚₒₛ, log Pₙₑₘ) space, draw 95 % confidence ellipses, and explore any tweet live in a Gradio likelihood visualizer. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week2/C1W2L1_naive_bayes_likelihoods_lesson.ipynb) |
| A2  | `C1W2_A1_Naive_Bayes_Teaching_v2.ipynb` | Implement Naïve Bayes from scratch using Laplace smoothing. Preserves `### UNQ_Cx` autograder tags, includes local test assertions, and finishes with an interactive Gradio classifier. | [Open in Colab](https://colab.research.google.com/github/Joe-rini/nlp-specialization-colab/blob/main/week2/C1W2_A2_Naive_Bayes_From_Scratch_Teaching.ipynb) |


## 🗕️ Week 3 — Embeddings, Similarity, & PCA

| Day | Notebook | Description | Open in Colab |
|-----|----------|-------------|----------------|
| L1  | `C1W3_L1_Linear_Algebra_Colab.ipynb` | Learn the basics of vectors, dot product, and cosine similarity using NumPy, apply them to real and toy examples, and explore similarity with an interactive Gradio app. | [Open in Colab](https://colab.research.google.com/drive/1DFS9OpMkNf4DBfuhmwRxjbPtNnj9lqW0?hl=de#scrollTo=141e7227) |
| L2  | `C1W3_L2_Embeddings_Colab.ipynb` | Load pre-trained word embeddings and explore analogies like `king - man + woman = queen` using vector arithmetic. Try your own with a live Gradio explorer. | Coming soon |
| L3  | `C1W3_L3_PCA_Embeddings_Colab.ipynb` | Use PCA to project high-dimensional word embeddings into 2D. Visualize capital–country relationships as vector arrows, and build spatial intuition about semantic similarity. | Coming soon |

---

## 🧑‍💻 Attribution

This notebook is adapted from:  
[`amanchadha/coursera-natural-language-processing-specialization`](https://github.com/amanchadha/coursera-natural-language-processing-specialization)

All content © DeepLearning.AI. This is an educational adaptation only.

