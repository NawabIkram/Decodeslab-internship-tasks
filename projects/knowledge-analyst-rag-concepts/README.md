# Knowledge Analyst: RAG Concepts

## Overview

This project simulates a Retrieval-Augmented Generation (RAG) workflow for a law firm that needs to analyze long contracts quickly. The prototype shows how an AI assistant can summarize key clauses and answer specific questions using only evidence from the document.

The sample source is a fictional contract, but the workflow is designed to represent how a real PDF contract could be processed.

## Problem Statement

Law firms often review long contracts manually. This takes hours and increases the chance of missing important risks, deadlines, or obligations. A RAG-based document intelligence workflow can reduce review time by retrieving the relevant contract sections first, then generating answers that cite the exact page and section.

## RAG Workflow

1. **Document ingestion**: Upload or provide a legal PDF/document.
2. **Text extraction**: Extract text while preserving page numbers and section headings.
3. **Chunking**: Split the document into searchable chunks by page and section.
4. **Retrieval**: Match the user's question to the most relevant chunks.
5. **Grounded generation**: Generate the answer using only retrieved chunks.
6. **Citation validation**: Require every claim to include a page/section citation.
7. **Fallback behavior**: If the answer is not found, respond with `Not found in the provided document`.

## Deliverables

| File | Purpose |
| --- | --- |
| `sample-contract.md` | Fictional legal document used as the source text |
| `RAG_PROMPTS.md` | Prompt engineering templates for citation-first RAG |
| `summary-dashboard.md` | Extracted risks, dates, stakeholders, and clauses |
| `sample-qa-with-citations.md` | Example document Q&A with citations |

## How Hallucination Is Reduced

- The assistant is instructed to answer only from retrieved document chunks.
- Every factual answer must cite a page and section.
- Missing information must be reported as `Not found in the provided document`.
- The model is not allowed to use outside knowledge or assumptions.
- Dashboard entries and Q&A responses both include evidence references.

## Tools / Concepts Used

- PDF-to-AI workflow simulation
- Retrieval-Augmented Generation concepts
- Prompt engineering
- Citation-based answering
- Legal document summarization
- Risk/date/stakeholder extraction

## Example Citation Format

```text
Answer text. [Page 3, Section 4.2]
```

If unavailable:

```text
Not found in the provided document.
```
