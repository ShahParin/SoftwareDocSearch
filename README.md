# Structured Search for Software Documentation

This project introduces an intelligent information retrieval (IR) system tailored for software documentation, addressing the common issues of dense, unstructured, and inconsistent content. The system processes documents in various formats (HTML, Markdown, Javadoc, Jsdoc), extracts and segments meaningful sections (e.g., code blocks, explanations, API references), and indexes them to enable effective search and retrieval.  It is designed to help developers quickly find the information they need.

**Key Features:**

* **Type-Aware Retrieval:** The system categorizes and labels retrieved segments as "Code Example," "Explanation," or "Troubleshooting," providing users with immediate context for the information.
   
* **Hybrid Ranking Model:** Employs a combination of keyword-based ranking (TF-IDF/BM25) and semantic similarity (Sentence-BERT) to ensure both precise and contextually relevant search results.
   
* **Developer-Centric Design:** Specifically designed to support developer queries related to implementation ("how-to" questions), conceptual understanding ("why" or "what" explanations), and debugging/troubleshooting (error resolution).

* **Evaluation Metrics:** The system’s performance is evaluated using several metrics, including classification accuracy (for segment categorization), manual relevance judgments, and standard information retrieval metrics such as Precision, Recall, F1 Score, and Mean Reciprocal Rank (MRR).

**Benefits:**

* Reduces the time developers spend searching for specific information within documentation.
   
* Improves the efficiency of understanding complex concepts and debugging software issues.
   
* Increases overall development productivity by providing quick access to relevant and well-organized information.

This project aims to streamline the process of navigating software documentation, making it more efficient and user-friendly for developers.
