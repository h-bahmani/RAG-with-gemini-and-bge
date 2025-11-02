📚 Gemini Rerank RAG Chatbot
This project implements an advanced, hybrid Retrieval-Augmented Generation (RAG) architecture. It utilizes best-in-class components for each stage of the RAG pipeline, specifically engineered to solve the common issue of external reranker instability by incorporating a Custom Reranker powered by the Gemini 2.5 Flash LLM.

🌟 Key Features
Hybrid RAG Architecture: Combines high-performance embedding with a powerful large language model (LLM) for context refinement.

Multilingual Embedding: Uses the robust BAAI/bge-m3 model via the Cloudflare Workers AI API for high-quality vector generation, ensuring strong performance for diverse languages, including Persian.

Custom Gemini Reranking: Replaces the often-unstable external reranker API with a bespoke function that leverages Gemini 2.5 Flash to intelligently select and prioritize the top 5 most relevant and comprehensive chunks from the initial retrieval pool.

Scalable Infrastructure: Uses Supabase (pgvector) for efficient and reliable vector storage and similarity search.

Interactive Interface: Built with Streamlit for a smooth, operational, and user-friendly chat interface.
