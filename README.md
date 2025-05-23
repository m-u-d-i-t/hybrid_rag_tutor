# Hybrid RAG AI Tutor for CBSE AI (Class 6–9)

This project provides an AI-based tutoring system designed to teach Artificial Intelligence as introduced in the CBSE curriculum for classes 6 to 9. It addresses the lack of trained teachers by implementing a Hybrid Retrieval-Augmented Generation (RAG) framework that combines semantic vector search and knowledge graphs for accurate, contextual, and syllabus-aligned AI learning.

---

## 🚀 Objective

To deliver accurate, simplified, and interactive explanations of AI topics for middle school students using CBSE-prescribed material—without the need for human teachers.

---

## 🧠 What It Does

- Parses official CBSE AI textbooks, handbooks, and in-use school books.
- Uses sentence-level parsing and embeddings for semantic vector search.
- Builds a knowledge graph to map interrelated AI concepts.
- Answers student queries using a hybrid retrieval mechanism (vector + graph).
- Uses prompt engineering to deliver student-friendly responses in simple language.

---

## ⚙️ Technologies Used

- **LlamaIndex** – Core framework for document parsing, retrieval, and orchestration.
- **Pinecone Vector DB** – Stores semantic embeddings for similarity search.
- **Neo4j** – Stores and retrieves concept relationships via a knowledge graph.
- **Groq LLaMA-4-Scout-17B** – Large language model for generating responses.
- **HuggingFace Embeddings** – Embeds document chunks using `dunzhang/stella_en_1.5B_v5`.
- **QueryFusionRetriever** – Combines vector and graph results for higher relevance.
- **RichPromptTemplate** – Custom prompt template designed for class 6–9 understanding.

---
