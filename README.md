# TATTVA-RAG
TATTVA-Transcendental Assistance Through Textual Verse Augmentation

TATTVA (_"Truth" in Sanskrit_) is a spiritually inspired Retrieval-Augmented Generation (RAG) system that harnesses the eternal wisdom of the Bhagavad Gita to provide context-rich, insightful responses to user queries. By combining semantic search via FAISS and the power of Meta's LLaMA 3 model, TATTVA bridges ancient spiritual guidance with modern AI.

Features

#Verse Retrieval Engine

Uses SentenceTransformers (paraphrase-multilingual-MiniLM-L12-v2) to encode Gita verses.

Employs FAISS for high-performance semantic similarity search.

#Knowledge Base Construction

CSV-based verse dataset is preprocessed to extract meaningful content (translation or meaning).

Verses are formatted and stored alongside their vector representations.

#Query Engine

Natural language queries are encoded and matched to top relevant verses.

Returns the most semantically aligned chunks.

#LLM-Powered Summarization

Integrates meta-llama/Meta-Llama-3-8B-Instruct through HuggingFace's InferenceClient.

Generates spiritually styled answers using the top-k retrieved verses.
