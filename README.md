# 📄 AI Text Summarizer

An NLP-based text summarization project that extracts important information from documents and generates a concise summary.

## 📌 Project Overview

**AI Text Summarizer** is a Natural Language Processing (NLP) project designed to reduce lengthy documents into shorter, meaningful summaries.

The system accepts a **PDF document**, extracts its text, processes the content, identifies important words and sentences, and generates an **extractive summary** based on sentence importance.

The project also provides useful text statistics and important keywords.

---

## 🎯 Objectives

* Extract text from PDF documents
* Preprocess and clean the extracted text
* Split the document into sentences
* Remove common stopwords
* Calculate word frequencies
* Identify important sentences
* Generate an extractive summary
* Display important keywords
* Calculate summary statistics
* Allow users to download the generated summary

---

## 🔄 Project Workflow

```text
PDF Document
     ↓
Text Extraction
     ↓
Text Preprocessing
     ↓
Sentence Tokenization
     ↓
Stopword Removal
     ↓
Word Frequency Analysis
     ↓
Sentence Importance Scoring
     ↓
Important Sentence Selection
     ↓
Generated Summary
     ↓
Keywords + Statistics
     ↓
Download Summary
```

---

## 🧠 Methodology

The project uses an **extractive text summarization** approach.

### 1. PDF Text Extraction

The uploaded PDF is processed using `pypdf`, and the available text is extracted from its pages.

### 2. Text Preprocessing

The extracted text is cleaned by:

* Converting text to lowercase
* Removing unnecessary whitespace
* Extracting words using regular expressions

### 3. Sentence Tokenization

The document is divided into individual sentences using **NLTK**.

### 4. Stopword Removal

Common English words such as articles and other frequently occurring words are removed to focus on meaningful terms.

### 5. Word Frequency Analysis

The frequency of the remaining words is calculated using Python's `Counter`.

### 6. Sentence Scoring

Each sentence receives an importance score based on the frequency of the meaningful words it contains.

### 7. Summary Generation

The highest-scoring sentences are selected and arranged according to their original order to produce the final summary.

---

## 🛠️ Technologies Used

| Technology | Purpose |
| ---------- | ------- |
| Python     |         |
