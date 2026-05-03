---

title: "One Piece RAG Chatbot"
date: 2026-04-27
draft: false
------------

# One Piece AI Chatbot

This project demonstrates how I built a Retrieval-Augmented Generation (RAG) chatbot using structured data.

<div style="border-radius: 12px; overflow: hidden;">
  <iframe
    src="https://udify.app/chatbot/FXBFTE2CBYAAvXps"
    style="width: 100%; height: 700px"
    frameborder="0"
  ></iframe>
</div>

---

## Problem

How can we build a chatbot that answers domain-specific questions accurately without hallucinating?

---

## Solution

I built a RAG system using:

* Structured Markdown data
* Vector embeddings
* Semantic retrieval
* Large Language Model (LLM)

---

## How it works

1. Data was collected and structured into Markdown
2. Content was split into smaller chunks
3. Each chunk was embedded into a vector database
4. User queries are matched with relevant chunks
5. The LLM generates answers based on retrieved context

---

## Data structure

The dataset is divided into:

* Characters
* Arcs
* Devil Fruits

Example:

```
# Character: Monkey D. Luffy

## Role
Captain

## Abilities
- Rubber powers
- Haki
```

---

## Results

The chatbot can answer:

* Character information
* Story arcs
* Abilities and powers

With improved accuracy compared to a standard LLM.

---

## What I learned

* Structuring data for AI systems
* Importance of chunking
* Prompt engineering basics
* Retrieval optimization

---

## Improvements

* Custom frontend instead of iframe
* More data sources
* Metadata filtering

---
