# Conversational Agent for Microsoft Products

## Overview

In today's fast-paced digital era, accessing information quickly is paramount. This project aims to develop an intelligent conversational agent designed to handle inquiries about Microsoft's products. The primary objective is to construct a model proficient in discerning user intent, extracting essential information, and suggesting relevant queries that seamlessly integrate into the ongoing conversation.

## Task Importance

This project directly addresses the crucial requirement of furnishing users with meaningful and valuable follow-up queries, thereby enhancing the efficiency and productivity of the search experience in conversational settings. Ultimately, it aims to contribute to a more seamless and user-centric interaction with Microsoft's products.

## User Queries

User queries can vary widely but generally revolve around seeking information, assistance, or clarification regarding Microsoft products. Examples include queries about product features, technical support, comparisons between products, purchase assistance, updates, how-to queries, and compatibility issues.

## Relevant Results

Relevant results should include detailed product information, troubleshooting steps, product comparisons, purchase assistance, updates, general information, how-to guides, and compatibility information. Typically, one highly relevant result is displayed per query, along with two to five potential follow-up queries.

## Implementation Details

### Dataset
The MS Dialog dataset is leveraged, containing labeled dialog interactions from Microsoft Community forums. The dataset comprises over 2,000 multi-turn conversations with 10,000 utterances, annotated with user intent on the utterance level.

### Model Evaluation Metrics
- Precision@1:  Precision of the top-ranked result.
- Mean Reciprocal Rank (MRR):  Average reciprocal of the rank of the first relevant document retrieved for a set of queries.

### Models Implemented
1. Query-likelihood with Dirichlet smoothing
2. TF-IDF Vector Space Model
3. BM25 (Best Matching 25)

### Results
BM25 outperformed other models, demonstrating superior performance in relevance ranking and follow-up query suggestion.

## Future Work and Enhancements

- Deploying a scalable chatbot using BM25 and optimizing for user-specific customization.
- Implementing robust data security measures and regulatory compliance.
- Continuous monitoring, analytics, and iterative improvements for performance enhancement and user satisfaction.
