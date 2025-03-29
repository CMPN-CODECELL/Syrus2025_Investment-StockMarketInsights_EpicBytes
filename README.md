# Syrus2025_Investment-StockMarketInsights_EpicBytes
 #      InvestWise AI : Intelligent Wealth Creation Platform

Updated PPT Link: https://docs.google.com/presentation/d/1-J-YSC8bgAJRmUE6IRYJ5xgH-BPZ3rqQYuxBrHFEhYE/edit?slide=id.g345f657ae46_2_61#slide=id.g345f657ae46_2_61


Video Link: https://drive.google.com/file/d/1klVxo34kC1TRl5NCajS5tGiTJtDdxcHB/view

# Updated after Mentoring Session:

# 1. Sentiment Analysis Using RAG

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
Datastore
![WhatsApp Image 2025-03-28 at 22 27 13_4d2766ae](https://github.com/user-attachments/assets/35b28094-db93-4270-84f3-4558859202b0)
Vector Store
![WhatsApp Image 2025-03-28 at 22 27 31_44a7cc56](https://github.com/user-attachments/assets/7db72aad-4c8a-4d3e-8b14-3b787007f2b5)
RAG Container
![WhatsApp Image 2025-03-28 at 22 27 53_507a6c6d](https://github.com/user-attachments/assets/1e06c3f5-c0da-405a-aecb-27e1abff57cd)
Overview of Agent
![WhatsApp Image 2025-03-28 at 22 47 37_61df9050](https://github.com/user-attachments/assets/ed72319d-0148-4ace-b9c1-b1ac93898a03)
Chatbot
![WhatsApp Image 2025-03-28 at 22 53 31_6a0d645c](https://github.com/user-attachments/assets/81bd790b-2418-488d-b070-7ac11cbdbca5)

# 2. Beginner Support Chatbot

The "Beginner Financial Support Chatbot" assists users with financial management by providing basic budgeting tips and personalized financial advice. It uses a conversational workflow to capture user queries (e.g., "How do I budget?" or user provides monthly income, expenses, saving and on that basis agent suggests further investment decisions), processes them through an LLM to generate simple, actionable advice, and displays the response in a user-friendly manner. The chatbot focuses on beginner-friendly guidance, covering budgeting, saving, and money management while adapting to 2025 economic trends like inflation. It aims to empower users with clear, step-by-step financial tips tailored to their needs.


## Screenshots
![image](https://github.com/user-attachments/assets/200ce9e4-e200-4d23-95dc-5d398d5f531e)
### WorkFlow
![image](https://github.com/user-attachments/assets/cc85cf51-2ab3-4b42-9fe2-16605e4a21ff)
![WhatsApp Image 2025-03-29 at 12 01 06_265bbbbe](https://github.com/user-attachments/assets/cacf6536-a006-4f2e-88a6-6020056b53b4)
### Chatbot
![image](https://github.com/user-attachments/assets/b2f8f295-f363-4a35-90d0-5188f6413b1d)
![WhatsApp Image 2025-03-29 at 09 47 28_e3c105b4](https://github.com/user-attachments/assets/36fef01d-db98-465e-8e0b-24611b86b406)


# 3. AI Powered Investment Assistant

## Screenshots
![WhatsApp Image 2025-03-28 at 23 04 53_dae5827e](https://github.com/user-attachments/assets/e9518439-9b78-4198-8bcb-557d038ffdc5)
![WhatsApp Image 2025-03-28 at 23 05 41_ace4b657](https://github.com/user-attachments/assets/6fdf98fb-7794-4f3c-87cd-158fbe4a2486)
Workflow diagrams
![WhatsApp Image 2025-03-29 at 13 55 53_7a7a6194](https://github.com/user-attachments/assets/fc6c928d-d7f4-414d-9ad6-c5e42d154cb0)
Chatbot
![image](https://github.com/user-attachments/assets/e9315893-645b-4a5c-b277-2596b50e8f43)


# 4. Goal Based Investment Agent

## Screenshots
![Screenshot 2025-03-28 231838](https://github.com/user-attachments/assets/9d9ca7e1-b073-4321-a792-38471c2f689b)
### chatbot
![image](https://github.com/user-attachments/assets/3b2a0cc1-4651-44cc-88ec-520e2211335a)


# 5. Behavioral Analysis

## Screenshots
![image](https://github.com/user-attachments/assets/fda2b3d2-da9d-4051-a461-a7821f9aa493)
### Workflow
![image](https://github.com/user-attachments/assets/904340af-cf50-41cf-8ccb-bcd56e13e1d1)

### Chatbot
![Screenshot 2025-03-29 141634](https://github.com/user-attachments/assets/07921993-f8cc-43fc-925b-fd6d0a256d94)

