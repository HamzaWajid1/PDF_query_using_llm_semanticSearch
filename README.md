# ✨ LangChain Document Retrieval and Question Answering Project ✨

🔍 **Analyzing PDF Documents with LangChain and Answering Questions** 📚

## 🌐 Overview

- Leveraging LangChain for insightful analysis of content from PDF documents.
- Emphasizing document loading, text splitting, embeddings, vector storage, and intuitive question-answering with a language model.

## 📖 Document Loading and Text Splitting

- Loaded the PDF document "linear_algebra_for_machine_learning.pdf" using LangChain's `PyPDFLoader`.
- Employed `RecursiveCharacterTextSplitter` to gracefully split text based on separators, chunk size, and overlap.

## 📜 Text Splitting Example

- Applied `CharacterTextSplitter` with finesse, specifying separators, chunk size, and overlap.
- Splendidly split documents into chunks, setting the stage for further processing.

## 🎨 Embeddings and Vector Storage

- Utilized embeddings from Hugging Face's "sentence-transformers/all-MiniLM-L6-v2" for a touch of magic.
- Crafted unique IDs for each document based on content, then stored unique documents in a vector wonderland using Chroma.

## ❓ Question Answering

- Engineered a RetrievalQA chain for an enchanting question-answering experience.
- Conjured up a prompt template for generating answers based on the context.
- Posed an intriguing question: "How is probability related to machine learning."

## 🙌 Acknowledgments

- Heartfelt gratitude to LangChain for weaving the magic of NLP tasks.
- A tip of the hat to OpenAI for their enchanting language models.

Feel free to explore and contribute to the magical world of LangChain! 🚀
