# AI Annual Report Consultant

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yusra7947/AI-Annual-Report-Consultant/blob/main/notebooks/RELIANCE_ANNUAL_REPORT.ipynb)

A RAG based AI tool for analyzing complex financial reports using LangChain and FAISS.
Nobody actually wants to read a 200 page annual report from cover to cover. Whether you’re an investor in Mumbai or a data analyst, hunting for one specific number in a massive PDF is a waste of your time.

I built this tool to change that. Using Retrieval Augmented Generation (RAG), this project allows you to "talk" to a financial report. You ask a question in plain English and the AI finds the exact context, reads the data and gives you a precise answer without hallucination.

The Problem & My Solution
The Problem: Financial reports are unstructured, dense, and intentionally long.

The Solution: A custom Python class (ReportConsultant) that uses LangChain to break down the PDF and FAISS to index the information. When you ask a question, the tool only looks at the relevant pages to give you an answer that is technically accurate not just a lucky guess.It also provides the sources(page no.) for the information it gives.

Here is the tech I used to make it happen:

LangChain: The brain that manage the conversation and document logic.

FAISS: My vector database of choice for lightning fast similarity searches.

OpenAI / Gemini: The language models that provide the final, human like reasoning.

PyPDF: To handle the messy work of processing complex financial tables and text.

How to Get Started
If you want to try this out,:

Clone the repo and install the basics:

pip install -r requirements.txt

Add your API Key: Create a .env file and drop your key in there (don't worry, my .gitignore will keep it secret!).

Run the analysis: Use the script in the src/ folder or play around with the notebook in notebooks/.

 If you're in a hurry, I've included a "Open in Colab" link in the above so you can run it in the cloud without installing anything
 
 Let’s Connect
 
I’m currently based in Mumbai and looking for new challenges in FinTech and Data Science. If you’re building something cool in AI or need a hand automating your data workflows, let’s talk!

LinkedIn:  linkedin.com/in/yusra-khan79 
