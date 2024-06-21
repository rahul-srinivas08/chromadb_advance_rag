# chromadb_advance_rag
advance rag with querry expanding and query recomposition of ranks,pitfall of rag and retrieval distractor 
- querry expansion 1. expansion with generated answer 2. expansion with multiple generated querries
  - querry pass to get llm hypothetical answer and original querry + llm hypothetical answer do vector retrval and pass revrival + querry for llm to generate response
  -  create multiple querries from llm by given original query, do retival on vector db on original and generated querry by llm and pass retrival documents to llm to create response
