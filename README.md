# Lit-Review

# 🧠 Literature Review Toolkit for Researchers

This repository provides a modular, extensible set of tools for conducting literature reviews using Python. It is built to support both beginner researchers and advanced analysts by automating tedious tasks, enabling semantic search, and making research more reproducible and transparent.

Whether you're mapping keywords across a corpus, performing semantic retrieval, or preparing documents for NLP pipelines, this toolkit helps you move from raw PDFs and eBooks to structured, analyzable content — fast.

---

## 🚀 Quick Launch (Google Colab + Local Use)

| Notebook | Description | Launch |
|----------|-------------|--------|
| 🧹 **Lit_Pre_Processing.ipynb** | Cleans and structures raw text from PDFs or EPUBs. Includes heading-based segmentation and string cleaning. First step before frequency/similarity analysis. | _Run locally_ |
| 🔍 **Citation_Search_Colab.ipynb** | Searches for and enriches citations using article titles and first-page content via Google Scholar. Helpful for incomplete or informal citations. | [Open in Colab](https://colab.research.google.com/drive/1AghtEN0k6fqzv1ugODXwqQEKUwciPGIp?usp=sharing) |
| 📊 **lit_count.ipynb** | Performs keyword and n-gram frequency analysis on pre-processed texts. Useful for thematic mapping and term trend analysis. | [Open in Colab](https://colab.research.google.com/drive/1BEGQjYDSdWBjhvc-83NwcMmjuTIsOXyc?usp=sharing) |
| 💡 **Lightweight_similarity.ipynb** | Uses sentence embeddings to find semantically similar sentences across your corpus. Anchors interpretation to high-value textual cues. | _Run locally or adapt for Colab_ |
| 🧠 **RAG_Literature_Helper.ipynb** | Retrieval-Augmented Generation (RAG) tool for querying your corpus semantically. Ideal for exploratory research and question answering. ⚠️ *Advised to run locally for faster indexing and retrieval.* | [Open in Colab](https://colab.research.google.com/drive/1oPYMbsCNTS4MggtTSBr_6UG_YIORvw1Y?usp=sharing) |
| 📚 **epub_conversion.ipynb** | Extracts text from `.epub` files and structures it into clean paragraphs or chapters for review. Integrates with pre-processing and analysis tools. | [Open in Colab](https://colab.research.google.com/drive/1-3tF12vGAJNc60W_h_5XgnKMdeI6zE7V?usp=sharing) |

---


---

## 🔧 Setup Instructions

To use locally:

```bash
git clone https://github.com/UnbrokenCocoon/LiteratureReviewToolkit.git
cd LiteratureReviewToolkit
pip install -r requirements.txt
