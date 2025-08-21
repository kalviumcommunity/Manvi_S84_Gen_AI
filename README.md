# Manvi_S84_Gen_AI

🌍 AI Travel Planner - TripGenie

📌 Project Overview

The AI Travel Planner is a smart travel assistant powered by Large Language Models (LLMs) and external APIs. It helps users create personalized travel itineraries based on their destination, preferences, budget, and travel dates. Instead of browsing through multiple travel blogs or guides, the user can simply interact with the planner in natural language, and the AI generates a customized day-by-day travel plan with recommendations for places to visit, food options, accommodations, transport routes, and local experiences.

This project demonstrates the practical application of prompt engineering, embeddings, vector databases, and similarity search in building intelligent, user-centric applications.

🎯 Objectives

Provide personalized travel recommendations using AI.

Allow users to specify preferences (budget-friendly, cultural, adventure, food, luxury).

Demonstrate LLM prompting techniques (zero-shot, one-shot, multi-shot, chain-of-thought, etc.).

Integrate AI concepts like embeddings, similarity search, structured output, and function calling.

Build a working prototype that can serve as a base for future travel-related applications.

Technical Implementation
1. Frontend (User Interface)

React.js + Tailwind CSS

User inputs: destination, dates, preferences, budget.

Displays generated itinerary in a user-friendly way (cards, maps).

2. Backend (API Layer)

Node.js + Express.js

Routes for handling:

AI requests (itinerary generation)

Travel data fetching (via APIs)

Vector DB operations (store & retrieve embeddings)

3. AI & Prompt Engineering

OpenAI / LLM Integration for natural language responses.

Prompt types used:

Zero-shot, One-shot, Multi-shot, Dynamic, Chain-of-thought.

RTFC Framework for prompt design (Role, Task, Format, Context).

4. Data & Knowledge Base

Vector Database (Pinecone / FAISS / Weaviate / ChromaDB) to store attraction/restaurant embeddings.

Embeddings Model to convert text data into vectors.

Similarity Search for fetching the best matching destinations & activities.

5. Testing & Evaluation

Evaluation dataset of 5+ test cases (different user inputs).

Judge prompt compares AI-generated itinerary with expected output.

Logging tokens usage after every AI call.