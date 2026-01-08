# TrackIt

## Problem Statement

Many individuals struggle to maintain discipline in managing their time and expenses. 
Although people generate data daily through activities and spending, this data often remains unstructured and unused.

Most existing tracking tools only store information.  
They fail to provide meaningful, personalized insights that help users understand *why* habits form and *how* they can improve over time.

In addition, generic AI assistants give advice without sufficient context. This leads to recommendations that are  
not grounded in the user’s actual behavior or history.

---

## Solution Overview

TrackIt addresses this problem by combining structured tracking with data-driven analysis and a context-aware AI assistant.

The application allows users to record daily activities and expenses in a categorized and time-stamped format. 
The backend processes this data to identify patterns, trends, and inconsistencies in behavior.

Instead of producing generic AI responses, TrackIt ensures that all feedback is grounded in the user’s own historical data.

---

## Use of Retrieval-Augmented Generation (RAG)

The AI assistant in TrackIt does not rely solely on a language model’s internal knowledge. Instead, it follows a Retrieval-Augmented Generation (RAG) approach.

1. Aggregated user data such as activity history, expense trends, and discipline goals is converted into structured documents.
2. These documents are transformed into embeddings and stored in a vector database.
3. When the user interacts with the AI assistant, the system retrieves the most relevant user-specific data.
4. This retrieved context is used to augment the AI prompt before generating a response.

This ensures that all AI feedback is personalized, relevant, and grounded in real user behavior.

---

## Outcome

By combining structured data tracking with RAG-based AI analysis, TrackIt transforms raw user data into actionable insights. 
Users are able to clearly understand their habits and receive context-aware guidance to improve discipline, productivity, and spending behavior over time.
