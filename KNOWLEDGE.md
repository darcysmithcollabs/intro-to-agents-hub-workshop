---
title: Beginner's Guide to Building a Knowledge Base with Codex
summary: A quick-start guide for collecting information and turning it into an organised AI-readable knowledge base.
document_type: guide
status: active
last_updated: 2026-06-23
tags:
  - knowledge-base
  - codex
  - beginners
  - vibe-coding
read_when:
  - creating a new knowledge base
  - helping a beginner organise project or business information
---

# Beginner's Guide to Building a Knowledge Base with Codex

You do not need to organise everything yourself. Put all your existing information in one folder and let Codex help turn it into a structured knowledge base.

## 1. Create a `raw-knowledge` folder

Inside your project, create a folder called:

```text
raw-knowledge/
```

This folder is the collection point for your original, unorganised information.

## 2. Drop all your resources into it

Add anything that may help explain your business, project, or idea, including:

- Word documents and PDFs;
- rough notes and Markdown files;
- exported emails, FAQs, forms, or spreadsheets;
- meeting notes and transcripts;
- transcripts from voice memos;
- screenshots or photographs of handwritten notes;
- website copy and other useful text.

The files do not need to be neat. Do not include passwords, API keys, banking details, identity documents, private customer data, or anything you do not have permission to store.

## 3. Ask Codex to organise it

Open the project in Codex and use this prompt:

```text
Read everything inside the raw-knowledge folder and help me turn it into an organised knowledge base.

First, propose a clear folder and file structure. Separate confirmed facts, current projects, unapproved ideas, and external references. Include an INDEX.md that explains where each topic lives.

Do not change or delete anything inside raw-knowledge. Do not invent missing information. Flag contradictions, unanswered questions, and sensitive information for me to review.

Show me the proposed structure before creating the organised knowledge-base files.
```

Review Codex's proposed structure, correct anything inaccurate, and then ask Codex to create it.

Keep `raw-knowledge/` as the untouched source material. When you collect more information later, add it to that folder and ask Codex to review what should be added or updated in the organised knowledge base.
