# Syrus2025_Investment-StockMarketInsights_EpicBytes

Updated PPT Link: https://docs.google.com/presentation/d/112qYhwDDzaAgb8gZtyJwTjZuCZdfv-aob2ks2W-bSBo/edit?usp=sharing

# Updated after Mentoring Session:

# Sentiment Analysis Using RAG

## Overview
We have implemented a **Retrieval-Augmented Generation (RAG)** system for **Market Sentiment Analysis** using **UPTIQ AI Workbench**. It retrieves relevant financial news and social media data, processes it using **vector search**, and generates sentiment-based insights using **GPT-3.5 Turbo (Azure)**.

## Features
- **RAG Query & Vector Search**: Retrieves financial news, social media posts, and analyst opinions.
- **Sentiment Evaluation**: Uses indexed embeddings to analyze sentiment (positive, neutral, or negative).
- **Actionable Insights**: Displays results like “Positive sentiment for AAPL due to strong earnings.”

## Tech Stack
- **Vector Store**: MongoDB with OpenAI `text-embedding-3-large`
- **LLM**: GPT-3.5 Turbo (Azure)
- **Storage**: NewsDataStore (Processed)
- **Platform**: UPTIQ AI Workbench

## Current Progress
- ✅ **Vector Store Created** (Indexed using OpenAI embeddings)
- ✅ **RAG Container Running** (Handles sentiment analysis with five retrieval candidates)
- ✅ **Data Store Processed** (Functional, but PII masking disabled)

## Improvements from Mentoring Feedback
- 🔹 Optimized vector search for better retrieval
- 🔹 Improved data structuring in MongoDB
- 🔹 Enhanced query response time with indexing optimizations

## How to Use
1. Input a stock symbol (e.g., `AAPL`, `S&P 500`).
2. System retrieves and analyzes relevant data.
3. Sentiment results are displayed with insights.

## Screenshots
![WhatsApp Image 2025-03-28 at 22 27 13_4d2766ae](https://github.com/user-attachments/assets/35b28094-db93-4270-84f3-4558859202b0)
![WhatsApp Image 2025-03-28 at 22 27 31_44a7cc56](https://github.com/user-attachments/assets/7db72aad-4c8a-4d3e-8b14-3b787007f2b5)
![WhatsApp Image 2025-03-28 at 22 27 53_507a6c6d](https://github.com/user-attachments/assets/1e06c3f5-c0da-405a-aecb-27e1abff57cd)
![WhatsApp Image 2025-03-28 at 22 47 37_61df9050](https://github.com/user-attachments/assets/ed72319d-0148-4ace-b9c1-b1ac93898a03)
![WhatsApp Image 2025-03-28 at 22 53 31_6a0d645c](https://github.com/user-attachments/assets/81bd790b-2418-488d-b070-7ac11cbdbca5)







---
📌 **Future Enhancements:** Enable PII masking and refine search accuracy!
