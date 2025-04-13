# RAG-Based-User-Content-Summariser
## Abstract
In the digital era, user-generated content platforms are key sources for tasks ranging from product recommendations to technical problem-solving. However, users often face scattered, disorganized, and sometimes contradictory information. RAG-Based User Content Summariser (RBUCS) tackles this challenge by aggregating and analyzing content to transform disjointed data into coherent, targeted responses.

Our approach combines Retrieval-Augmented Generation (RAG) with Large Language Model (LLM) capabilities to form a powerful information processing pipeline. The system starts by classifying user queries to select the appropriate handling strategy, then employs a hybrid retrieval mechanism that integrates vector-based semantic search (FAISS), traditional text matching (BM25), and content quality signals (user votes/likes) to identify the most relevant documents across platforms such as Reddit, Stack Overflow, and RedNote.

For recommendation queries, our pipeline extracts candidate items, analyzes sentiment across posts, and synthesizes collective opinions to provide ranked recommendations with supporting evidence. For general information queries, the system contextualizes the retrieved content and generates comprehensive responses that preserve the accuracy and nuance of the original sources.

The architecture is built for scalability, featuring efficient web crawling, incremental indexing, and persistent memory to maintain context across interactions. Our evaluation—focused on query type classification—demonstrates strong performance across diverse queries, with particularly high scores in recommendation scenarios (F1 score: 0.98).

RBUCS enhances information accessibility by turning the tedious task of sifting through numerous posts into a streamlined process that delivers concise, targeted content. It highlights the power of advanced retrieval techniques combined with language models to effectively tackle information overload in user-generated content platforms.

## Poster
![Slide Final](https://github.com/user-attachments/assets/1195e110-be17-4575-a36a-247e20f08ca8)
