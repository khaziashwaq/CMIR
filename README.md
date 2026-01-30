# CMIR – Code-Mixed Information Retrieval 🇧🇩🇬🇧

This repository contains our submission for the **CMIR (Code-Mixed Information Retrieval)** shared task conducted as part of **[FIRE 2025](https://fire.irsi.org.in/fire/2025/home)**.

The goal of this project is to build an **Information Retrieval (IR) system for code-mixed social media data**, with a specific focus on **Banglish** (Bengali + English).


## 🔍 Problem Overview

Code-mixed languages are extremely common on social media platforms, especially in multilingual regions. Traditional IR systems struggle with such data due to:

- Mixed scripts and languages  
- Informal grammar and spellings  
- Phonetic transliterations (e.g., Bengali written in Roman script)

This project explores methods to **retrieve relevant information from Banglish queries and documents**, addressing these challenges.


## 🧠 Approach (High Level)
We proposed a hybrid retrieval framework that integrates BM25 and a triplet-tuned Sentence Transformer model using Reciprocal Rank Fusion (RRF). the approach leverages the complementary strengths of sparse and dense retrieval, ensuring robust performance on noisy Banglish social media data.


## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Installation

Clone the repository:
```bash
git clone https://github.com/your-username/CMIR-FIRE2025.git
cd CMIR-FIRE2025
