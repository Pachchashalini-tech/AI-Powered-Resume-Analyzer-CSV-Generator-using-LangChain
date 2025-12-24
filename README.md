# AI-Powered-Resume-Analyzer-CSV-Generator-using-LangChain
**Project Overview**
- Recruiters and HR teams often receive resumes in bulk, typically as compressed (ZIP) files     containing multiple resumes in PDF or DOCX format.
  Manually reviewing each resume and extracting key details is time-consuming, repetitive, and   error-prone.
- This project aims to automate resume understanding and information extraction using LangChain, Prompt Templates, and Structured Output Parsers.
  
**What this system does:**
- Accepts a ZIP folder containing multiple resumes
- Automatically reads each resume
- Extracts structured information using LLMs
- Stores the output in a CSV file
- Allows users to download the CSV directly from a Streamlit app
  
**Problem Statement**
- HR teams struggle to analyze large volumes of resumes efficiently
- Resume formats vary widely (PDF, DOCX, layouts, fonts)
- Manual extraction of skills, links, and summaries is inconsistent
- No structured output for easy filtering or analysis

**Solution Approach**
- We build an LLM-powered pipeline using LangChain that:
- Reads resumes from a ZIP file
- Converts unstructured resume text into structured data
- Enforces a fixed schema using TypedDict Output Parser
- Aggregates all resume outputs into a **CSV
