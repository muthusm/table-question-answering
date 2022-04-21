# table-question-answering

## About 

TAPAS, the model learns an inner representation of the English language used in tables and associated texts, which can then be used to extract features useful for downstream tasks such as answering questions about a table, or determining whether a sentence is entailed or refuted by the contents of a table.

1. It is a BERT-based model specifically designed (and pre-trained) for answering questions about tabular data
2. TAPAS uses relative position embeddings and has 7 token types that encode tabular structure.
3. It is pre-trained on the masked language modeling (MLM) objective on a large dataset comprising millions of tables from English Wikipedia and corresponding texts.


The model has been fine-tuned on several datasets
* SQA (Sequential Question Answering by Microsoft)
* WTQ (Wiki Table Questions by Stanford University)
* WikiSQL (by Salesforce).

## Architecture

![alt text](https://github.com/muthusm/table-question-answering/blob/main/tapas_architecture.png)

## Huggingface space

## Huggingface modelcard

## Code Demo

## Video

## Resource Links


