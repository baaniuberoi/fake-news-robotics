# fake-news-robotics
Research on detecting fake news using robotics, AI, and behavioural signals.

This project works using the following architecture:

1) Text Preprocessing - to remove the stop words, punctuations, and irrelevant metadata to pass the cleaned tokens into the classification model.

2) Curriculum Learning Classifier - based on curriculum learning, this model has DistilBERT as its backbone, initially focusing on simple binary classifications (real vs fake)
   and gradually incorporates more nuanced layers such as satire detection, bias identification, and emotional framing.
   
3) Explainability layer - to establish a user-friendly, transparent format, we use LIME and SHAP to highlight the most influential features in each decision.
   
4) Image and Bias Modules - AI image detection tools like FakeCatcher have also been incorporated into the model.
