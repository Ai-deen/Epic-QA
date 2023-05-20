# Epic-QA
## Information retrieval based project.

### Data Link:
https://bionlp.nlm.nih.gov/epic_qa/#collection

https://drive.google.com/drive/folders/1uRNmVaipV2HoYNcMP6VA7Nc68wvaszD3?usp=sharing

### Description:
EPIC-QA is a project made to answer questions about COVID-19 in a passage.
There are two tasks: Task A provides expert-level answers to questions asked by
researchers, scientists, or clinicians, while Task B provides simpler, consumer-friendly
answers for the general public. The goal is to make reliable information more accessible.
The system uses several models, including TfidfVectorizer, BERT, Universal Sentence
Encoder, and Doc2Vec, for ranking the documents and generating answers. These models
are used to calculate the similarity between the query and the sentences in the
documents. The top 5 most relevant sentences are then extracted and merged into a
paragraph to form the passage answer.

### Task Link:
https://bionlp.nlm.nih.gov/epic_qa/#objective

### Working:
There are 2 ipynb files ->
1. comsumer.ipynb - for documents and queries related to the consumer part
2. expert.ipynb - for documents and queries related to the expert part
Comments and results are already there in the files.

### Conclusion:
The system was able to extract satisfactory answers from these passages based on the input queries.
Both Consumer and Expert Data sets were explored to extract answers as required.
Overall, the project was successful in using different models to find and extract relevant
information.


