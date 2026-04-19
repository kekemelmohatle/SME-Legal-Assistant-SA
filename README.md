# SME Legal & SARS Multilingual Assistant
**A Generative AI Mastery Project (Phase IV - Portfolio Prototype)**
## Overview
Navigating SARS tax compliance and CCMA labor laws is a major barrier for small business owners in South Africa, especially when information is only available in complex legal English. This project uses (Generative AI) to bridge that gapby providing grounded legal advice in "isiZulu, Sesoth, and Afrikaans".
## Technical Architecture
**This system is build as a " Retrieval-Augmented Generation (RAG)" pipeline to ensure 100% accuracy and zero hallucinations.**
**(Intent classification): a neural Nertwork identifies if a query is about "tax"(SARS) or "labor"(CCMA).**
**Knowledge Retrieval (RAG): The system searches official South African government PDFs (stored in the "\data" folder).**
## Tech Stack
**Language:** Python (Google Colab)
**AI Frameworks:** Langchain, Sentence-Transformers 
**Vector Database:** ChromaDB for storing legal embeddings
**Translation Model:** Meta NLLB-200
**Data Sources:** Official SARS SMME guides and CCMA Discriplinary codes
## Ethical Governance & POPIA 
**Transparancy**: Every answer includes a legal disclaimer.
**Data Privacy**: No sensitive SME financial data is stored; only public legal guides are used for retrieval.
**Inclusion**: Supporting 11 official language languages to promote digital equity in the SA economy
## Project Structure
"sme_Legal_Assistant_SA.ipynb" : Main AI Logic and RAG Pipeline.
"/data": Official SARS and CCMA PDF knowledge base.
"docs": Final Project report and skill-to-role Matrix

**Developed by:** [Your Name/GitHub Username]
**Program:** Mentenc Innovations - Generative AI 
