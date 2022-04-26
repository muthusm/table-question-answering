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

## Analysis

For question answering, TAPAS has 2 heads on top: a cell selection head and an aggregation head, for (optionally) performing aggregations (such as counting or summing) among selected cells. TAPAS has been fine-tuned on several datasets: SQA (Sequential Question Answering by Microsoft), WTQ (Wiki Table Questions by Stanford University) and WikiSQL (by Salesforce). It achieves state-of-the-art on both SQA and WTQ, while having comparable performance to SOTA on WikiSQL, with a much simpler architecture. TAPAS outperforms or rivals semantic parsing models by improving state-of-the-art accuracy on SQA from 55.1 to 67.2 and performing on par with the state-of-the-art on WIKISQL and WIKITQ, but with a simpler model architecture.



## [Huggingface space](https://huggingface.co/spaces/Meena/table-question-answering-space)

## [Huggingface modelcard](https://huggingface.co/Meena/table-question-answering-tapas)

## [Code Demo](https://github.com/muthusm/table-question-answering/blob/main/2%20Train%20Model.ipynb)

## [Video](https://github.com/muthusm/table-question-answering/blob/main/video1864411241.mp4)

## Resource Links

[TAPAS Model Summary ](https://huggingface.co/docs/transformers/model_doc/tapas)
[Documentation](https://huggingface.co/transformers/v4.9.2/model_doc/tapas.html)
[Model revisions](https://huggingface.co/models?search=tapas)



