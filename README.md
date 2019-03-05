# test-repo
Document Retrieval
google knowledge graph
Doing graph search over structured knolwedge rather than traditional search


Approaches to Question Answering:

1.Knowledge Based Approach
-Build a semantic representation of the query : Times, Dates, locations, entities, numeric quantities
-Map from this semantics to query structured data or resources
Eg: Geospatial databases, Ontologies(Wikipedia Infoboxes, dbPedia, WordNet, Yago)

2. Text Based(Mainly Factoid) QA
-Question Processing: Detect question type, answer type, focus, relations. Formulate queries to send to a search engine
-Passage Retrieval: Retrieve ranked documents. Break into suitable passages and rerank
-Answer Processing: Extract candidate answers(as named entities). Rank candidates(using evidence from relations in the text and external sources)


3. Hybrid Approaches
-Build a shallow representation of the query
-Genearte answer candidates using IR methods: Augmented with ontologies and semi-structured data
-Score each candidate using richer knowledge sources



Document Retreival Research Papers


Improving Document Ranking with Dual Word Embeddings
https://www.microsoft.com/en-us/research/publication/improving-document-ranking-with-dual-word-embeddings/?from=http%3A%2F%2Fresearch.microsoft.com%2Fpubs%2F260867%2Fpp1291-nalisnick.pdf

A Dual Embedding Space Model for Document Ranking
https://arxiv.org/abs/1602.01137
