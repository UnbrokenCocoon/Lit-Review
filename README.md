# Literature Review Toolkit for Researchers

This repository provides a modular, extensible set of tools for conducting literature reviews using Python. It is designed to support both new and experienced researchers by automating tedious tasks, enabling semantic search, and making research more reproducible and transparent.

Whether you're mapping keywords across a corpus, performing semantic retrieval, or preparing documents for NLP pipelines, this toolkit helps you move from raw PDFs and eBooks to structured, searchable content — fast.

---

## What is a Systematic Literature Review?

A **systematic literature review (SLR)** is a methodical approach to identifying, evaluating, and synthesising all relevant research on a specific topic. Unlike informal reading, an SLR is:

- Comprehensive: it aims to include **all relevant items**, not just what is familiar
- Transparent: it documents the process of how items were found and included
- Reproducible: others should be able to follow the same process and reach similar results

This toolkit is designed to help students and researchers perform **keyword-based and semantic searches** across a body of academic texts, enabling them to:

- Retrieve all texts relevant to a certain topic
- Identify how concepts are used across the literature
- Write **comprehensive and justifiable reviews**

---

## 🚀 Quick Launch (Google Colab + Local Use)

| Notebook | Description | Launch |
|----------|-------------|--------|
| **Lit_Pre_Processing.ipynb** | Processes academic **PDFs**, cleaning the text and extracting it by filename into a structured DataFrame. Prepares the corpus for frequency or semantic search. | _Run locally_ |
| **epub_conversion.ipynb** | Processes `.epub` files in the same format as the PDF processor — producing a DataFrame with clean text and filenames. | [Open in Colab](https://colab.research.google.com/drive/1-3tF12vGAJNc60W_h_5XgnKMdeI6zE7V?usp=sharing) |
| **Citation_Search_Colab.ipynb** | Searches for and enriches citation metadata using article titles and first-page content via Google Scholar. | [Open in Colab](https://colab.research.google.com/drive/1AghtEN0k6fqzv1ugODXwqQEKUwciPGIp?usp=sharing) |
| **lit_count.ipynb** | Performs **keyword frequency searches** across the pre-processed text corpus. Helps identify how often key terms appear and in which documents. | [Open in Colab](https://colab.research.google.com/drive/1BEGQjYDSdWBjhvc-83NwcMmjuTIsOXyc?usp=sharing) |
| **Lightweight_similarity.ipynb** | Uses sentence embeddings to find semantically similar sentences across the corpus. Anchors interpretation to key ideas or prompts. | _Run locally or adapt for Colab_ |
| **RAG_Literature_Helper.ipynb** | Retrieval-Augmented Generation (RAG) tool for querying your corpus semantically. Helps locate the most relevant sentences for any question. ⚠️ *Advised to run locally for speed.* | [Open in Colab](https://colab.research.google.com/drive/1oPYMbsCNTS4MggtTSBr_6UG_YIORvw1Y?usp=sharing) |

---

##  Workflow Summary

The core goal of this toolkit is to create a single **searchable DataFrame** containing the cleaned text of all your PDFs and EPUBs, structured by filename.

This combined text corpus can then be:

- Queried semantically (using sentence similarity or RAG)
- Searched for keyword frequencies across documents
- Used to build systematic, evidence-based literature reviews

This approach supports **rigorous and justifiable review writing**, where every included item and concept can be traced and verified.

---

## Example Use Cases

- Build a **literature matrix** from 30+ academic sources
- Identify **who is using which terms** and how often
- Use semantic search to support **narrative synthesis**
- Justify your inclusion/exclusion criteria in a formal review
- Automate citation lookup and metadata verification

---

## 🧠 Philosophy

This toolkit assumes that **meaningful literature review involves both frequency and function**. Not all sentences are equal. We prioritise relevance, reproducibility, and interpretability — using tools from NLP to support, not replace, careful reading.

---

## 🤝 Contributing

Contributions welcome! If you’ve built tools for entity recognition, topic mapping, citation deduplication, or visualisation, feel free to submit a PR or open an issue.

---

## 📜 License

This project is licensed under the MIT License.

---

Made with ❤️ to support open, accessible, and rigorous research.


