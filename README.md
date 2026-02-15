# RAG Architect Assignment 1 — Classic RAG System

**Course:** RAG Architect
**Week:** 1
**Total Marks:** 100
**Release Date:** Now
**Deadline:** **Sunday, 22 — End of Day (EOD)**

---

## 🧩 Problem Statement — Real-World Scenario

You are hired as an **AI Engineer** to build an internal knowledge assistant for a company.

The company has hundreds of documents such as:

* HR Policies
* Engineering Docs
* Internal Guides
* Product Manuals

Employees want to ask questions like:

* "What is our leave policy?"
* "How does deployment pipeline work?"
* "What are the coding standards?"

However, the company faces problems:

* Searching documents manually is slow
* Different versions of documents exist
* Employees want accurate, context-based answers

Your task is to build a **Classic RAG-based Knowledge Assistant** that:

1. Ingests documents
2. Converts them into embeddings
3. Stores them in a vector database
4. Retrieves the most relevant chunks when a user asks a question
5. Reranks the retrieved chunks for better relevance
6. Generates a final grounded answer using an LLM

**Goal:** Build a working foundational RAG system that can answer user questions based only on provided documents.

---

## 🚀 Assignment Objective

This assignment evaluates your **fundamental understanding of building a Classic RAG system** from scratch. You are expected to demonstrate:

* Understanding of RAG architecture
* Ability to implement a working pipeline
* Clarity of thinking and originality

This is a **foundational assignment**. Focus on correctness, clarity, and completeness rather than complexity.

---

## 📦 Submission Requirements

You must submit **ALL** of the following:

### 1. Architecture Document (PDF or DOC)

Explain your RAG system clearly. Include:

* Overall architecture diagram
* End-to-end data flow (User → Retrieval → Generation)
* How embedding works in your system
* How retrieval works
* Where reranking happens
* How generation is done

**Bonus (Optional):**

* Document lifecycle handling
* Namespace / user isolation design
* Update / version strategy

---

### 2. Code Submission (Mandatory)

You must write your **OWN implementation** of a Classic RAG pipeline.

Minimum features required:

* Document ingestion
* Chunking
* Embedding creation
* Storing vectors in Pinecone (or equivalent)
* Retrieval (Top-K)
* Reranking
* Final answer generation using LLM

The code should be **clean, readable, and runnable**.

---

## ❗ Academic Integrity Rule (Very Important)

* Do **NOT copy from GitHub, friends, internet, or AI-generated repositories**.
* Plagiarism will result in **ZERO marks**.
* You may take reference from class concepts, but implementation must be your own.
* Similar code across candidates will be flagged automatically.

---

## 🎯 Marking Scheme (100 Marks Total)

### Part A — Architecture & Explanation (40 Marks)

| Criteria                            | Marks |
| ----------------------------------- | ----- |
| Clear Architecture Diagram          | 10    |
| Correct RAG Flow Explanation        | 10    |
| Retrieval + Embedding Understanding | 10    |
| Reranker + Generation Clarity       | 10    |

---

### Part B — Code Implementation (50 Marks)

| Criteria                      | Marks |
| ----------------------------- | ----- |
| Document Ingestion & Chunking | 10    |
| Embedding & Vector Storage    | 10    |
| Retrieval Implementation      | 10    |
| Reranking Working             | 10    |
| Final Answer Generation       | 10    |

---

### Part C — Bonus (10 Marks)

Optional but rewarded if implemented:

* User-level document isolation (namespaces)
* Document lifecycle handling
* Version / update strategy
* Duplicate detection
* Multi-user architecture thinking

---

## 🧠 What We Are Testing

This assignment evaluates:

* Your real understanding of RAG
* Ability to build from scratch
* Engineering clarity
* Original thinking
* Code quality and correctness

Not required:

* UI
* Production deployment
* Advanced optimization

---

## 📧 Submission Method

Email your complete submission to **[admin@datasenseai.co.in](mailto:admin@datasenseai.co.in)**

**Subject format (MANDATORY):**
`RAG Week-1 Assignment — <Your Full Name> — <Your Email/Phone>`

Incomplete or wrongly formatted subjects may lead to missed evaluation.

---

## 📤 Submission Format

Submit in a single folder:

```
Assignment_1_<YourName>/
 ├── architecture.pdf
 ├── code/
 ├── requirements.txt
 └── README.md (How to run)
```

---

## ⏳ Deadline

**Sunday, 22 — End of Day (EOD)**
Late submissions may receive reduced marks.

---

## 💡 Final Note

Focus on building a **correct, working Classic RAG system**.
This assignment forms the **foundation for all future advanced RAG topics**.

Good luck. Build honestly. Think deeply.
