# AI Interview Questions

## 1. Machine Learning

### Easy

- What is the difference between supervised and unsupervised learning?
- What is the difference between classification and regression?
- What are training, validation, and test datasets?
- What is overfitting, and how can you prevent it?

### Medium

- Explain the bias-variance trade-off.
- How do you handle missing values and imbalanced datasets?
- What is the difference between L1 and L2 regularization?
- How do you choose the right evaluation metric for a classification problem?

### Hard

- Your model performs well in training but poorly in production. How would you investigate?
- How would you detect and handle data drift and concept drift?
- How would you design an ML experiment to determine whether a new model is genuinely better?
- How would you improve a model when collecting additional labeled data is expensive?

## 2. Deep Learning

### Easy

- What is a neural network, and how does it learn?
- What is an activation function? Why do we need one?
- What are epochs, batches, and learning rates?

### Medium

- Explain backpropagation and gradient descent.
- What is the vanishing gradient problem?
- What is the difference between CNNs, RNNs, and Transformers?

### Hard

- How would you diagnose unstable training or a model whose loss stops decreasing?
- How do batch normalization and layer normalization differ?
- How would you train a deep learning model with limited GPU memory?

## 3. Generative AI and LLMs

### Easy

- What is a Large Language Model (LLM)?
- What are tokens, tokenization, and context windows?
- What is the difference between pretraining and fine-tuning?
- What are hallucinations in LLMs?

### Medium

- What is the difference between prompting, RAG, and fine-tuning?
- What do temperature and top-p control during text generation?
- What are embeddings, and how are they used in semantic search?
- How would you evaluate the quality of an LLM's answers?

### Hard

- An LLM gives incorrect answers despite having the correct information in its context. How would you debug it?
- How would you reduce hallucinations without fine-tuning the model?
- How would you select between a small, self-hosted model and a large, hosted model?
- How would you optimize an LLM application for latency, cost, and answer quality simultaneously?

## 4. RAG (Retrieval-Augmented Generation)

### Easy

- What is RAG, and why do we use it?
- What is a vector database?
- What is the difference between keyword search and semantic search?

### Medium

- Explain the complete RAG pipeline, from document ingestion to answer generation.
- How do chunk size and chunk overlap affect retrieval quality?
- What is the difference between dense retrieval, sparse retrieval, and hybrid search?
- How does reranking improve retrieval?

### Hard

- Your RAG system retrieves irrelevant chunks. How would you identify the root cause?
- How would you evaluate retrieval quality separately from answer quality?
- How would you build RAG over millions of documents with access-control requirements?
- When would you choose long-context prompting over RAG?

## 5. AI Agents, Agentic AI and Frameworks

### Easy

- What is an AI agent?
- What is the difference between an AI agent and a traditional chatbot?
- What are tools and function calling in LLM applications?

### Medium

- What is the difference between an AI agent and agentic AI?
- How does an agent decide which tool to call?
- What is the difference between LangChain and LangGraph?
- When would you use a multi-agent system instead of a single agent?

### Hard

- An agent repeatedly calls the same tool and never finishes. How would you fix it?
- How would you design an agent that can recover from tool failures and resume interrupted tasks?
- How would you prevent an agent from executing dangerous or unauthorized actions?
- How would you decide which steps should be deterministic code versus LLM-driven decisions?

## 6. MCP, Tool Integration and AI Protocols

### Easy

- What is the Model Context Protocol (MCP)?
- What problem does MCP solve?
- What are MCP clients, servers, and tools?

### Medium

- What is the difference between MCP and RAG?
- How does an LLM application discover and invoke MCP tools?
- How would you integrate an MCP server with an existing AI application?

### Hard

- How would you secure an MCP server that can access internal business data?
- How would you debug intermittent failures in tool execution?
- How would you handle authentication, permissions, timeouts, and retries when integrating multiple tools?

## 7. Python, SQL and Coding

### Easy

- What is the difference between a list, tuple, set, and dictionary in Python?
- What are mutable and immutable objects?
- Write Python code to count the frequency of words in a string.
- Explain SQL JOIN, GROUP BY, and HAVING.

### Medium

- How do generators differ from lists, and when would you use them?
- Write SQL to find the second-highest salary in each department.
- Given actual and predicted labels, implement precision, recall, and F1-score.
- How would you process a dataset that does not fit into memory?

### Hard

- Design a Python pipeline that processes millions of records while handling errors and retries.
- How would you identify and fix a memory leak in a long-running Python service?
- Write a concurrent API-calling pipeline with rate limits, timeouts, and failure handling.

## 8. AI System Design and Architecture

### Easy

- What are the main components of a production AI application?
- What is the difference between batch inference and real-time inference?
- Why would you expose an ML model through an API?

### Medium

- Design a customer-support chatbot using company documentation.
- How would you handle concurrent requests to an LLM API?
- How would you cache AI responses, and what are the risks?
- How would you implement authentication, logging, and rate limiting?

### Hard

- Design a scalable RAG application for thousands of concurrent users.
- Design a multi-tenant AI platform that prevents one customer's data from appearing in another customer's responses.
- How would you achieve high availability when an LLM provider experiences an outage?
- Design an AI system under strict latency, reliability, and budget constraints.

## 9. MLOps, Deployment and Monitoring

### Easy

- What is MLOps, and why is it important?
- What is the difference between Docker and a virtual machine?
- What is CI/CD?

### Medium

- How would you deploy an ML model using FastAPI and Docker?
- What metrics would you monitor for a production LLM application?
- How do you version datasets, models, and prompts?
- How would you roll back a problematic model deployment?

### Hard

- How would you detect a silent degradation in an AI application?
- How would you deploy a new model without disrupting existing users?
- How would you investigate rising latency and API costs after deployment?

## 10. LLM Evaluation, Security and Responsible AI

### Easy

- What is the difference between model accuracy and LLM answer quality?
- What is prompt injection?
- Why is human evaluation important for generative AI?

### Medium

- What are LLM-as-a-judge evaluations?
- How would you create a test dataset for a RAG application?
- How do you measure faithfulness, relevance, and retrieval quality?
- How would you protect sensitive information in LLM inputs and outputs?

### Hard

- Your evaluation scores improve, but users report worse answers. How would you investigate?
- How would you test an agent that can execute actions across multiple enterprise systems?
- How would you build an evaluation framework that detects regressions across model and prompt versions?
