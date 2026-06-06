# Project AI Email Secretary

AI-assisted email prioritization and draft response workflow built in Python/Colab.

## Repository Contents

- [Notebook summary](docs/notebook-summary.md)
- [Notebook source](notebooks/ai_email_secretary_solution.ipynb)
- [Notebook HTML report](docs/ai_email_secretary_solution.html)
- [Architecture overview](docs/architecture-overview.md)
- [Sample email dataset](sample-data/sample_emails.csv)
- [Example configuration](config.example.json)

## Overview

Project AI Email Secretary explores how artificial intelligence can support email management by classifying incoming messages, identifying priority items, summarizing context, and generating draft responses for human review.

The project is designed as a decision-support workflow. It does not send emails automatically.

## Business Problem

Email overload can make it difficult to identify urgent messages, deadlines, follow-ups, and requests that require immediate action.

This project focuses on reducing manual review time and improving response consistency by using AI to support email triage, prioritization, summarization, and draft preparation.

## Objective

The main objective of this project is to demonstrate how AI can assist in email management while keeping the human user in control of final decisions and communications.

This solution is especially useful for scenarios where users need to:

- Review large volumes of email
- Identify urgent or important messages
- Prepare consistent draft responses
- Reduce manual processing time
- Improve follow-up visibility
- Support executive or administrative workflows

## Main Capabilities

- Classifies emails by priority and intent
- Identifies urgent or deadline-driven messages
- Summarizes email context
- Generates professional draft responses
- Supports executive-level email review
- Helps identify follow-up actions
- Keeps humans in control before any response is sent

## Technical Context

This project is currently developed as a Python/Colab-based workflow.

Main technical elements:

- Python
- Google Colab
- Pandas
- Prompt engineering
- AI-assisted text classification
- AI-generated summarization
- AI-generated draft responses
- LLM-as-a-Judge evaluation approach

## Workflow

```text
Email dataset
      ↓
Data preprocessing
      ↓
AI classification
      ↓
Priority detection
      ↓
Summary generation
      ↓
Draft response generation
      ↓
Human review
```

## Responsible AI Approach

This project is designed with a human-in-the-loop approach. The AI generates suggestions, but final decisions and communications remain under human supervision.

The system is intended to support decision-making, not replace human judgment.

Key responsible AI principles considered in this project:

- Human review before sending any response
- No automatic email sending
- Clear separation between suggestion and final decision
- Protection of sensitive information
- Use of fictional or sanitized sample data
- Awareness of possible AI errors or hallucinations

## Privacy Notice

This repository does not include real emails, private credentials, API keys, access tokens, or sensitive personal information.

Any sample data included in this repository is fictional, anonymized, or sanitized and used only for demonstration purposes.

Files that should never be committed to this repository include:

```text
.env
credentials.json
token.json
client_secret.json
API keys
access tokens
real email datasets
private customer data
```


## Current Status

The repository has been prepared as part of a public professional portfolio. Sample data is fictional, and sensitive information has been excluded from the project.

The notebook source and HTML report are included as project artifacts. If GitHub cannot render them directly, they can be downloaded and reviewed locally or in Google Colab.

## Roadmap

- Review and sanitize notebook before public release
- Add architecture diagram
- Add sample outputs
- Refactor notebook logic into reusable Python modules
- Add evaluation examples
- Add clearer prompt documentation
- Add limitations and improvement notes
- Prepare repository for public portfolio visibility

## Portfolio Purpose

This repository is part of my professional GitHub portfolio.

The goal is not only to showcase code, but also to document how a software initiative can be structured, explained, reviewed, and connected to business value.

This project reflects interest in:

- AI-assisted workflows
- Business process automation
- Software delivery practices
- Technical documentation
- Responsible use of artificial intelligence
- Human-centered productivity tools

## Author

**Anibal Arias**  
Software Development Manager focused on technical leadership, software delivery, process improvement, and business-oriented technology solutions.

- GitHub: [anibal-tech](https://github.com/anibal-tech)
- LinkedIn: [anibal-arias](https://www.linkedin.com/in/anibal-arias)
- Website: [tambormayor.com](https://tambormayor.com)
