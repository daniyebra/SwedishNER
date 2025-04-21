# SwedishNER
Participated in a huggingface competition, performing an NER task on ancient Swedish text.
Obtained 3rd place out of 120 participants, with a nervaluate f1 score of 0.766

The code in the repository demonstrates and explains:
1. Domain-adapting an XLM Large Roberta model for the task
2. Fine-tuning it with the competition dataset, including the following steps:
- Preprocessing steps
- Data augmentation and stratification
- Text windowing
- Model training 
- Prediction confidence implementation and optimization
- Entity reconstruction
