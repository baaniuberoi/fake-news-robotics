# fake-news-robotics
Research on detecting fake news using robotics, AI, and behavioural signals.

This project works using the following architecture:

1) Text Preprocessing - to remove the stop words, punctuations, and irrelevant metadata to pass the cleaned tokens into the classification model.

2) Curriculum Learning Classifier - based on curriculum learning, this model has DistilBERT as its backbone, initially focusing on simple binary classifications (real vs fake)
   and gradually incorporates more nuanced layers such as satire detection, bias identification, and emotional framing.
   
3) Explainability layer - to establish a user-friendly, transparent format, we use LIME and SHAP to highlight the most influential features in each decision.
   
4) Image and Bias Modules - AI image detection tools like FakeCatcher have also been incorporated into the model.

# 🤖 Fake News Detection with Robotics

This project explores how robotics and computer science can be combined to detect and respond to fake news or misinformation in real-time environments.

## 🧠 Goal

Design a system (simulated or physical) where a robot can identify fake news using AI and respond behaviorally, for example, through signals, movement, or alerts.

## 📚 Areas Explored

- Natural Language Processing (NLP)
- Robotics behavior (Arduino or simulated)
- Explainable AI (XAI)
- Human–AI collaboration
- Ethics and disinformation

## 📁 Folder Overview

- paper/: Research paper drafts, references, and outline
- code/: Scripts for detection, robot behavior, and data
- images/: Concept art, architecture, or data visuals
- logs/: Daily thoughts, progress, and planning notes

## 🛠️ Status

🚧 In Research Phase – Currently designing project framework and gathering resources.

## 🧾 To-Do

- [ ] Write problem statement and hypothesis
- [ ] Research similar projects (benchmarks)
- [ ] Define tools (Python, Arduino, etc.)
- [ ] Start writing research paper outline

---

> This project is part of my STEM research portfolio for university admissions, exploring how young innovators can ethically design AI systems for social impact.
