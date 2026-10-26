[Polski](README.md) | **English**

# Summer Challenge 2026: AI/ML

<div align="center">
  | <a href="https://www.linkedin.com/events/wakacyjnewyzwanie20267477684591185530880/">👾 LinkedIn</a> | 
  <a href="https://www.facebook.com/events/1056808610636713/">📘 Facebook</a> |
</div>

<br>

## From zero to ML Engineer!
Welcome to the AI/ML course repository of the **KN Solvro** Summer Challenge (*Wakacyjne Wyzwanie*)! This is an intensive summer track that takes you through the most important topics in artificial intelligence and machine learning — from the absolute basics of working with data all the way to language models.

---

## My solutions

My homework is on the [`francesspot-dev`](../../tree/francesspot-dev) branch. The `main` branch contains the course materials.

| Week | Notebook | What I did |
|------|----------|------------|
| 1 | `01_przetwarzanie_wizualizacja_danych/EDA_zadanie.ipynb` | Exploratory data analysis of the **Titanic** dataset: missing values, visualisations, cleaning and preparing the data for a classifier |
| 2 | `02_podstawy_aiml/ML_zadanie.ipynb` | Predicting Titanic survival: train/test split before any preprocessing (no data leakage), a baseline `DummyClassifier`, a **decision tree** and **KNN** tuned with grid search — about 79–82% test accuracy vs 61% for the baseline |
| 3 | `03_sieci_neuronowe_wizja_komputerowa/03_computer_vision_hw.ipynb` | Building and training a **U-Net** in PyTorch for semantic segmentation on Pascal VOC, with visualisation of the predicted masks |
| 4 | `04_nlp_agenty/zad_agent.ipynb` | An **agentic RAG assistant** for cooking recipes: PDFs → chunks → HuggingFace embeddings → Chroma; a LangGraph agent (Gemini) with two tools — recipe search and portion scaling — plus automated evaluation of the retriever (hit rate, MRR) and an LLM judge for relevancy and faithfulness |

The notebooks were run in Google Colab.

---

## Format and structure of the course
We meet every week on **Discord**. Each week brings a new topic and new challenges.

The weekly cycle has three main parts:
- **Lectures on Discord (1h):** short, to-the-point meetings (at most an hour, including Q&A). They give a solid introduction to the topic from the basics and cover the most important concepts.
- **Introductory notebook:** step-by-step practical material. It introduces the lecture topic and gives you the tools you need to solve the homework.
- **Weekly task:** your main goal for the week. You get a notebook with clear requirements and references. Besides writing code, it contains questions that check your understanding of the topic.

> Lecture slides and notebooks will appear on the day of each lecture (after the lecture).

---

## Groups and task reviews
Each participant will have their own dedicated protected branch in the repository.

Because we value sharing knowledge and helping each other:
- **Small working groups:** every week you will be randomly divided into smaller teams.
- **Cross-review:** we review each other's tasks. It is the best way to learn from mistakes (your own and others') and to see different approaches to the same problem.
- **Discussion:** the review is also a space to talk through what didn't work and to answer the helper questions together.

> PS: The coordinators will also review your task, but cross-review is part of passing the course too :P.

---

## Final project
The Summer Challenge ends with a practical project:

- **Teams:** work is done in groups of **2–4 people** (preferably 4).
- **Topic:** completely up to you! Every participant can propose a topic to the coordinators, and we as coordinators will also suggest project topics.
- **Scope:** the project can extend the course material or be based on implementing research papers.

---

## Schedule

| No. | Topic | Date | Coordinator |
| :--- | :--- | :--- | :--- |
| **0** | **Environment setup** (no meeting, notebook) | 01.08 | Dominik |
| **1** | **Data processing and visualisation** | 05.08 | Julia, Grzegorz |
| **2** | **AI/ML basics** | 12.08 | Dominik, Damian, Jan |
| **3** | **Neural networks and image processing** | 19.08 | Marcel, Paweł |
| **4** | **NLP** | 26.08 | Jakub, Kamil, Aleksandra |
| **5-7** | **Final projects** | 7/14/21.09 | Dominik, Jakub |
| **8** | **Course summary** | 28.09 | Everyone |
