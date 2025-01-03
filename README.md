# GraphRAG-Neo4j


## Steps

1. Pre-processing the raw data (notebooks\data_preprocessing.ipynb)
2. Data ingestion into Neo4j AuraDB (notebooks\data ingestion.ipynb)
3. Chat with Graph DB using In-context Learning (notebooks\Chatbot In-Context learning.ipynb)
4. Generating Cypher queries using LLM for fine tuning (notebooks\Cypher Queries LLM.ipynb)


## Drawbacks

1. This approach works best with a high-quality LLM model (preferably a paid one) for generating accurate Cypher queries.
2. Better results can be achieved if the dataset used to train the model is large.
3. This is an experimental project; use it as a reference and avoid directly replicating it.