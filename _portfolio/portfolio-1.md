---
title: "Bayesian and Partition-Based Optimization for Hyperparameter Optimization of LLM Fine-Tuning"
#excerpt: "End-of-studies internship under the guidance of Prof. El-ghazali Talbi <br/><img src='/images/500x300.png'>"
excerpt: "End-of-studies internship under the guidance of Prof. El-ghazali Talbi"
collection: portfolio
---

**Abstract**

Large Language Models (LLMs) have revolutionized natural language processing (NLP) by achieving state-of-the-art performance across diverse tasks. However, fine-tuning these models for domain-specific applications is significantly constrained by the computational costs associated with their training. In this paper, we propose two complementary approaches to address the Hyperparameter Optimization (HPO) challenge in LLM fine-tuning: Bayesian Optimization based on Gaussian Process (BO-GP) and Partition-Based Optimization (PBO). On the one hand, BO efficiently exploits historical knowledge to achieve optimal results within a limited number of evaluations, but its inherently sequential nature poses scalability challenges. On the other hand, PBO enables massive parallelization, making it more scalable but requiring significantly more evaluations to converge. To leverage their complementary strengths for optimizing expensive objective functions, we investigate these methods and propose a hybrid BO-PBO algorithm. This work represents a foundational step toward harnessing the potential of parallel Bayesian Optimization-based algorithms for solving expensive optimization problems in exascale computing environments.

Available on [GitHub](https://github.com/Kiwy3/BO_PBO_HPO_LLM)
