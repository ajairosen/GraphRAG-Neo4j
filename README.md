# Enhancing Text2Cypher with In-Context Learning and Fine-Tuning

## Introduction

Text-to-Cypher generation is a game-changer for working with graph databases. It translates natural language into Cypher queries, simplifying the process of accessing and exploring complex, connected data. This notebook walks you through methods like in-context learning and fine-tuning (PEFT) to enhance these models, making data retrieval faster and more accurate.

## Graph DB ScreenShots

![]([images\GraphDB SS-1.png](https://github.com/ajairosen/GraphRAG-Neo4j/blob/main/images/GraphDB%20SS-1.png))

## Steps

1. Pre-processing the raw data (notebooks\data_preprocessing.ipynb)
2. Data ingestion into Neo4j AuraDB (notebooks\data ingestion.ipynb)
3. Chat with Graph DB using In-context Learning (notebooks\Chatbot In-Context learning.ipynb)
4. Generating Cypher queries using LLM for fine tuning (notebooks\Cypher Queries LLM.ipynb)


## Drawbacks (Limitations)

1. This approach works best with a high-quality LLM model (preferably a paid one) for generating accurate Cypher queries.
2. Better results can be achieved if the dataset used to train the model is large.
3. This is an experimental project; use it as a reference and avoid directly replicating it.
