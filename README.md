# chromadb_advance_rag
an advanced rag with query expanding and query recomposition of ranks, the pitfall of rag, and retrieval distractor 
- query expansion 1. expansion with generated answer 2. expansion with multiple generated queries
  - query pass to get llm hypothetical answer and original query + llm hypothetical answer do vector retrieval and pass retrieval + query for LLM to generate a response
  -  create multiple queries from llm by giving original query, do retrieval on vector db on original and generated query by llm, and pass retrieval documents to llm to create a response
