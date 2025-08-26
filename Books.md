# Mining of Massive Datasets

Link - [Mining of Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/book.pdf)

Relevant Topics -

> **Source**: "Mining of Massive Datasets" by Leskovec, Rajaraman & Ullman

## 1. Scalable Computation & Distributed Systems

- MapReduce systems and algorithms

## 2. Similarity Estimation & High-Dimensional Techniques

- Locality-Sensitive Hashing (LSH)
  - Shingling
  - Min-hashing
  - Banding and LSH mechanisms

## 3. Data Stream Algorithms (Counting, Sketching, etc.)

- Algorithms for data streams

## 4. Graph & Link Analysis

- PageRank and Web-link analysis

## Summary of Relevant Topics

| GATE DA 2025 Syllabus Area    | Corresponding MMDS Topics                                  |
| ----------------------------- | ---------------------------------------------------------- |
| Algorithms & Optimization     | MapReduce algorithms, scalable counting, stream algorithms |
| Probabilistic Methods & Stats | LSH (min-hashing approximates Jaccard similarity)          |
| Machine Learning / ML Tools   | PageRank (graph-based ranking), stream processing          |
| Database & Warehousing        | Handling of massive datasets, distributed computation      |

---

**Recommendation for Study:**

1. **MapReduce & distributed algorithms**: Understand the MapReduce model, how algorithms are adapted to it, and its relevance to large-scale data processing in ML workflows.

2. **Similarity estimation with LSH**: Key for approximate nearest neighbors and scalable similarity search—fundamental in clustering, recommender systems, and more.

3. **Data stream mining techniques**: Crucial for analyzing real-time or continuous data with limited memory (e.g., sketching, counting, sampling algorithms).

4. **PageRank and link analysis**: Integrates graph theory and matrix analysis—ties to eigenvalues, iteration methods, graph structures.

---

# INTRODUCTION TO PROBABILITY AND STATISTICS FOR ENGINEERS AND SCIENTISTS

Link - [INTRODUCTION TO PROBABILITY AND STATISTICS FOR ENGINEERS AND SCIENTISTS](https://minerva.it.manchester.ac.uk/~saralees/statbook3.pdf)

## Table of Contents (Fifth/Sixth Edition)

1. **Introduction to Statistics**
2. **Descriptive Statistics**
3. **Elements of Probability**
4. **Random Variables and Expectation**
5. **Special Random Variables**
6. **Distributions of Sampling Statistics**
7. **Parameter Estimation**
8. **Hypothesis Testing**
9. **Regression**
10. **Analysis of Variance**
11. **Goodness of Fit Tests and Categorical Data Analysis**
12. **Nonparametric Hypothesis Tests**
13. **Quality Control**
14. **Life Testing**
15. **Simulation, Bootstrap Methods, and Permutation Tests**
16. **Machine Learning and Big Data** _(Sixth Edition only)_  


## Alignment with GATE DA 2025 Syllabus

| GATE DA 2025 Topic Area                          | Relevant Chapters from Ross's Book                         |
| ------------------------------------------------ | ---------------------------------------------------------- |
| **Probability Theory & Statistics Fundamentals** | Chapters 1, 2, 3, 4, 5, 6                                  |
| **Sampling, Estimation & Hypothesis Testing**    | Chapters 6, 7, 8                                           |
| **Regression & ANOVA**                           | Chapters 9, 10                                             |
| **Tests and Categorical Data**                   | Chapter 11                                                 |
| **Nonparametric & Quality Control**              | Chapters 12, 13                                            |
| **Life Testing (Exponential Models, CLT, etc.)** | Chapter 14                                                 |
| **Advanced Inference & Simulation Methods**      | Chapter 15                                                 |
| **(Emerging Techniques: ML/Big Data)**           | Chapter 16 — optional, but growing in relevance to GATE DA |



## Suggested Focus for GATE DA 2025 Preparation

- **Foundational Understanding**  
  Grasp probability axioms, random variables, expectation, and common distributions from Chapters 3–5.

- **Statistical Inference & Testing**  
  Build strong competence in parameter estimation and hypothesis testing from Chapters 7–8, supplemented by sampling theory from Chapter 6.

- **Regression & Variance Analysis**  
  Chapters 9 and 10 develop core models for prediction and variation—key in ML-oriented questions.

- **Categorical and Nonparametric Techniques**  
  Chapters 11 and 12 cover chi-square tests, contingency analysis, and nonparametric testing—aligned with GATE’s testing topics.

- **Life Testing & Quality Control**  
  Chapters 13 and 14 offer useful methods and distributions (e.g., exponential, control charts) frequently appearing in engineering exams.

- **Simulation & Resampling Techniques**  
  Chapter 15 introduces bootstrap and permutation methods—useful for understanding sampling variability and modern inference.

- **Optional Extensional Reading**  
  Chapter 16 (Machine Learning & Big Data) appeals to the advanced GATE DA learner seeking to integrate probability/statistics with AI and large-scale data analysis.

---
