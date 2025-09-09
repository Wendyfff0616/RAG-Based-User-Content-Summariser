# RAG-Based-User-Content-Summariser
## Abstract
User-generated content (UGC) platforms are key sources for tasks ranging from product recommendations to technical problem-solving. However, users often encounter scattered, disorganized, and sometimes contradictory information. To address this, we propose the RAG-Based User Content Summarizer (RBUCS), a system designed to aggregate and distill UGC into coherent responses.

RBUCS leverages Retrieval-Augmented Generation (RAG) with Large Language Model (LLM). Upon receiving a user query, the system performs text classification to select the optimal information processing strategy and output template. For recommendation queries, it extracts candidate items, synthesizes user opinions, and outputs ranked recommendations with supporting evidence. For general queries, it generates comprehensive summaries of the most relevant sources. RBUCS employs a hybrid retrieval mechanism, combining vector-based semantic search (FAISS), traditional text matching (BM25), and content quality signals (e.g., user votes/likes) to identify relevant documents across platforms like Reddit, Stack Overflow, and Rednote.

To evaluate the retrieval effectiveness of our RAG module, we labeled 150 query-document samples. Each sample contains a short user query and five relevant Rednote posts. The result shows that our approach achieves 100% Recall@5 and 89.44% Precision@5, suggesting that users, in the Rednote ecosystem, can expect to consistently find all relevant posts within the top results.

Overall, RBUCS effectively streamlines the process of reviewing and analyzing UGC, offering concise and targeted summaries to mitigate information overload on modern UGC platforms.

## Poster
[Coding Fest 2025_RBUCS.pdf](https://github.com/user-attachments/files/22231366/Coding.Fest.2025_RBUCS.pdf)
<img width="720" height="1018" alt="Coding Fest 2025_RBUCS" src="https://github.com/user-attachments/assets/d553bfc9-6906-4e0d-be54-9ebbf31ef99f" />

## Demo
Coming soon...
