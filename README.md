📄 Policy Document Q&A Assistant

A simple LLM-powered Question & Answer system that allows users to ask questions from a policy PDF document. The system reads the PDF, splits it into meaningful chunks, and uses a Qwen LLM to generate accurate answers based on the document content.

🚀 Project Overview

Organizations often have long policy documents that are difficult to search manually. This project solves that problem by:

Extracting text from a policy PDF

Splitting the text into manageable chunks

Passing relevant content to a Large Language Model (LLM)

Returning clear, human-readable answers

🧠 Technologies Used

Python

Qwen2 (Qwen/Qwen2-1.5B-Instruct) – Large Language Model

LangChain – Text splitting and LLM orchestration

PyPDF – PDF text extraction

Transformers & Torch – Model loading and inference
