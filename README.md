# My-Awesome-RAG-Reads

## 2025
- [Contextual Retrieval In AI systems](https://www.anthropic.com/engineering/contextual-retrieval)
- [Hybrid search in vespa series](https://www.youtube.com/watch?v=lfoOtjLhKh8)
- [HopRAG](https://arxiv.org/abs/2502.12442)
  - not able to implement it completely but it is in my backlog
- [Lumber chunker](https://arxiv.org/abs/2406.17526)
  - Effective way of dynamic chunking
  - I have optimized this approach to make production ready
- [Cohere Reranking](https://cohere.com/rerank)
  - later went with Qwen Reranking
- [LLM Embeddings Explained: A visual Guide](https://huggingface.co/spaces/hesamation/primer-llm-embedding?section=what_are_embeddings?)
- [SPLADE sparse vectors](https://qdrant.tech/documentation/fastembed/fastembed-splade/)

### Non RAG
This is one of the important concept I have learned while building the RAG pipeline. i,e., SAGA orchestration. A beautiful concepts.

## 2026

### Jan
- [Retrieval Augmented Generation (RAG) Course](https://www.deeplearning.ai/courses/retrieval-augmented-generation-rag/)
  - This is the best course to learn about RAG for production case.
  - 1st pass has been done, notes making under progress.
- On going work
  - Building the deep research kind of agents to do QnA on documents. still in exploration phase.
- [pageindex](https://pageindex.ai/blog/pageindex-intro)
  - **vectorless** reasoning based RAG
  - Very awesome idea, human like search, their demo page has really long documents.
- [37 insights from Weaviate Engineer on retrieval](https://www.leoniemonigatti.com/blog/what_i_learned.html)
- [very good read on RAG's blind spot](https://softwaredoug.com/blog/2025/05/16/rags-big-blindspot)
- [White-Paper: Applying embedding based retrieval to Airbnb search](https://arxiv.org/pdf/2601.06873)
  - I have completed the first pass of the paper. I found a very interesting approach where they used IVF and Euclidean distance.
  - This removed my bias toward always using cosine similarity. I still need to understand the exact usage, but it helped reduce my confirmation bias.
- [Production ready RAG pipeline substack](https://jamwithai.substack.com/p/the-infrastructure-that-powers-rag)
  - need to understand approach

### Feb
