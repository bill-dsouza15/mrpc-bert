# mrpc-bert

BERT model fine-tuned for the Microsoft Research Paraphrase Corpus (MRPC) task under the GLUE benchmarks.

## Model

- Base Pre-trained Model - 'bert-base-uncased'
- Training Model - BertForSequenceClassification (BERT with single linear layer on top for classification)

## Training Setup

Fine-tuned on a T4 GPU using Google Colab. See notebook for package dependencies.
