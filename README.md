#  🔍 Simple-RAG: Building a RAG System from Scratch

This tutorial demonstrates how to build a simple Retrieval-Augmented Generation (RAG) system using `LlamaIndex`, `Qdrant`, and an LLM like `OpenAI GPT`. The goal is to combine document retrieval with language generation to create a more informed and responsive AI system.

⚠️ While the tutorial is beginner-friendly, it also reflects my own learning process — so it may contain mistakes, rough edges, or room for improvement. Feedback and contributions are very welcome!

---
## Acknowledgment

This tutorial is adapted from [Datawhale China's wow-rag project](https://github.com/datawhalechina/wow-rag), with additional annotations and modifications for personal learning and experimentation.

All credits for the original structure and ideas go to the Datawhale open-source team.

---

##  Project Summary

This tutorial is organized as a step-by-step journey, covering:

-  **Chapter 1:** Minimal RAG – Build a basic retrieval + LLM pipeline from scratch  
-  **Chapter 2:** LLM Comparison – Try different embeddings and LLMs (OpenAI vs local)  
-  **Chapter 3:** Indexing – Play with chunking, retrievers, filters, and Qdrant integration  
-  **Chapter 4:** Document Management – Add, delete, and inspect text nodes  
-  **Chapter 5:** Deployment – Stream responses with FastAPI and Uvicorn  

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **Jupyter Notebook**
- [LlamaIndex](https://llamaindex.ai/)
- [Qdrant](https://qdrant.tech/)
- [OpenAI](https://platform.openai.com/) or [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- Optional: `Streamlit`, `FastAPI` for deployment

---

## 📌 To-Do & Roadmap

###  RAG System Enhancements

- 🔄 **Rebuild the same pipeline using [LangChain](https://www.langchain.com/)**  
  Compare design philosophy, modularity, and ease of use vs. LlamaIndex.

- 📊 **RAG Evaluation Framework**  
  Add tools or scripts to evaluate:
  - Retrieval accuracy (e.g., precision/recall of document chunks)
  - LLM response quality (e.g., faithfulness, hallucination rate)
  - Latency and cost benchmarks

- 📂 **Unstructured Data Handling**  
  Extend support beyond `.txt` files to:
  - PDFs, HTML, DOCX, CSV, etc.
  - Use multimodal inputs (e.g., images, OCR) as an advanced goal

---

###  Experiments & Prototypes

-  Few-shot and zero-shot prompt tuning for better responses  
-  Chunking strategy comparison: sliding window vs. sentence-level vs. fixed-size  
-  Embedding model comparison

---

###  Projectization

- 💬 Turn the POC into a modular, reusable RAG framework  

>  _This is a living list — feel free to suggest improvements or submit PRs if you're interested in collaborating!_

---
##  License

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
