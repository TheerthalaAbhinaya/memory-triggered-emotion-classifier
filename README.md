library_name: transformers
license: mit
datasets:
  - Abhinayathir/memory_emotion_dataset
language:
  - en
metrics:
  - accuracy
  - precision
  - recall
base_model:
  - distilbert/distilbert-base-uncased-finetuned-sst-2-english
  - google-bert/bert-base-uncased
