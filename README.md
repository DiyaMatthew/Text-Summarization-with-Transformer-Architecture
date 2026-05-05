# Text-Summarization-with-Transformer-Architecture
This project makes an investigation into Deep Learning based Text summarization using Transformer Architecture. 


There has been a rapid increase in the volume of text data in recent years. It is necessary to summarize this data in order to retrieve valuable knowledge within a reasonable period. In addition to saving valuable time, summarizing conveys the essence from which the reader can decide if they wish to investigate further. Text summarization involves the creation of concise and meaningful summaries of text from a variety of sources, including books, news articles, blog posts, and research papers. The process of manually converting the report to a summarized version is too time-consuming. As a result of enormous amounts of textual data being readily available, demand for automatic text summarization systems is on the rise. In almost every aspect of the internet, summaries are used to give readers a summary of an article, such as in e-commerce sites, search engines, and news sites. <br><br>
Text summarization approaches can be divided into two categories: Extractive summarization and Abstractive summarization. In extractive summarization, important sentences or phrases from the source documents are extracted and grouped to generate a summary without changing the original document. During abstract summarization, words and sentences are constructed, and assembled in a clear, comprehensible fashion, and then only the key facts from the source text are added. In this way, abstract summarizing approaches are more sophisticated, accurate and computationally costly than extractive summarizing approaches.<br><br>
In this project, I am planning to investigate abstractive text summarization transformer models to find out the best transformer model by analyzing and comparing the results of Transformer-based summarization models T5, BART and PEGASUS. Recall-Oriented Understudy for Gisting Evaluation (ROUGE) scores (ROUGE-1, ROUGE-2, ROUGEL and ROUGELSUM) are used as the evaluation metric. PEGASUS and BART provide good rouge scores and quality summaries, but BART performs better in different scenarios when compared with PEGASUS.



# 🚀 Transformer-Based Text Summarization System

An end-to-end **abstractive & extractive text summarization system** built using state-of-the-art transformer models, including T5, BART, and PEGASUS, fine-tuned on the CNN/DailyMail dataset.

This project investigates how different transformer architectures perform across **multiple real-world text scenarios** such as news articles, emails, reviews, and reports.

---

## 🎯 Key Highlights

- Fine-tuned **5 transformer models** (3 abstractive + 2 extractive)
- Trained on **300K+ samples** from CNN/DailyMail dataset  
- Performed **hyperparameter optimization (Optuna)**  
- Evaluated using ROUGE (ROUGE-1, ROUGE-2, ROUGE-L, ROUGE-Lsum)  
- Built and deployed an **interactive Streamlit web app**  
- Tested on **10+ real-world use cases**  

---

## 🧠 Problem Statement

With the rapid growth of textual data, extracting meaningful insights quickly is challenging.  
This project builds an **automated summarization system** that generates concise, human-like summaries from long-form text.

---

## ⚙️ System Architecture
