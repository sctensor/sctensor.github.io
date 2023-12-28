---
title: "Case Study: Streamlining HOA Operations with Chatbots"
date: 2023-12-18
weight: 2
---

[//]: # (![ChatBot]&#40;/images/chatbot.jpg&#41;)
![ChatBot](/images/chatbot.jpg){:width="50%"}

## Problem Statement

A homeowners association (HOA) with a significant number of units faced a challenge of handling a high volume of
queries. The limited board members struggled to keep up with the influx, and even outsourcing management didn't always
guarantee timely responses. As homeowner complaints grew due to non-responsiveness and a lack of transparency, the board
sought a solution to outsource services to a more efficient and responsive platform.

## Proposed Solution

Our proposed solution involved the development of an advanced chatbot using Large Language Model (LLM) techniques. The
idea was to train the chatbot on a vast corpus of HOA documents, including meeting notes, financial statements,
expenditures, financial transaction data, and all previous communications available in their repository. The trained
model would be stored in a vector database, and a Retrieval Augmentation Generator (RAG) based chatbot interface would
be created. This interface would comprehend context-based questions, query the vector database for accurate answers, and
cite the relevant documents and sections within them.

## Technical Implementation

The project's scope was deliberately kept focused. The key components included:

- **Vector Database (Vector DB):** A dedicated database for storing vector representations of documents.
- **RAG-based Chatbot Interface:** An interface that leverages the Retrieval Augmentation Generator for intelligent
  responses.
- **Training Pipeline:** A pipeline for training the model on the corpus of documents and storing the trained model in
  the vector database.

After an initial loading phase involving Extract, Transform, Load (ETL) processes, model training, and storage in the
vector database, the model was deployed. Subsequently, the chat interface was developed, deployed in the cloud, and
connected to the vector database. The chatbot was powered using a simple sentence transformer utilizing MiniLM-L6.

## Results

Homeowners can now seamlessly inquire about fees, owner responsibilities, CC&R, and more, receiving immediate responses
through the chatbot. This has notably freed up valuable resources for property managers, enabling them to focus more on
efficient property management.

Although the precise impact of the chatbot couldn't be quantified due to a lack of historical data on management
communications, the system currently handles an average of 40 to 50 user queries per day. The near-instantaneous
response contrasts sharply with the traditionally slower email responses from management. In summary, it represents a
substantial overall improvement in user experience.

*For more details on our approach and methodologies, please contact our team.*

