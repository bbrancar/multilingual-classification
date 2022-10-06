Transformers for Multi-Lingual Classification
______________________________________________

In this notebook, I employ HF's `xlm-roberta-large-xnli` for a multi-lingual classification task. The goal is classify sentences as agreeing with, disagreeing with, or being neutral toward one another. The notebook includes an example of mixed-precision training, a custom model that replaces the usage of the final [CLS] token in classification tasks with a mean pooling of the final hidden-state, and an example of Optuna's automated fine-tuning trial framework.
