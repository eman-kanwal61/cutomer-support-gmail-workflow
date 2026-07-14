
# AI Gmail Customer Support Automation using n8n

## Overview
This project is an AI-powered Gmail customer support automation workflow built using n8n, Groq LLM, Pinecone Vector Database, and Google Gemini Embeddings.

The workflow automatically monitors incoming Gmail messages, classifies customer emails, retrieves relevant business information from a knowledge base, and processes support requests intelligently.

---

## Features

- Automatic email monitoring using Gmail Trigger
- AI-based email classification
- Customer support query detection
- Retrieval Augmented Generation (RAG) using Pinecone
- Context-aware responses using vector search
- AI-powered processing using Groq Llama 3.3 70B model
- Automatic email labeling in Gmail
- Support for FAQs related to AI Automation services

---

## Workflow Architecture

### 1. Gmail Trigger
Monitors incoming Gmail messages in real time.

### 2. Text Classification
Classifies emails into two categories:

- **Customer Support AI**
  - AI Automation inquiries
  - Chatbot questions
  - FAQ requests
  - Service-related questions

- **Other**
  - Emails unrelated to AI automation services

### 3. AI Agent
Processes customer emails and:
- Understands user intent
- Extracts important information
- Generates contextual responses
- Retrieves knowledge from vector database

### 4. Pinecone Vector Store
Acts as the knowledge base containing:
- Services information
- FAQs
- AI automation details
- Business information

### 5. Google Gemini Embeddings
Generates vector embeddings for semantic search.

### 6. Groq LLM
Uses:
- `llama-3.3-70b-versatile`

for email understanding and response generation.

### 7. Gmail Labeling
Automatically labels processed emails for organization and tracking.

---

## Tech Stack

- n8n
- Gmail API
- Groq API
- Llama 3.3 70B
- Pinecone Vector Database
- Google Gemini Embeddings
- RAG Architecture
- AI Agents

---

## Use Cases

- AI Agency Customer Support
- Lead Qualification
- FAQ Automation
- Client Inquiry Management
- AI Service Support Automation

---

## Business Applications

This workflow can be used by:

- AI Automation Agencies
- SaaS Businesses
- Customer Support Teams
- Digital Agencies
- Consulting Firms

---

## Future Improvements

- Automatic email reply generation
- CRM integration
- Lead scoring
- Sentiment analysis
- Meeting scheduling
- Human handoff system
- Multi-language support

---

## Author

**Eman Kanwal**

BS Computer Science Student | AI Automation Enthusiast | Agentic AI Developer

---

## License

This project is available for educational and portfolio purposes.
