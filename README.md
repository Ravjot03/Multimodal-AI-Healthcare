# Multimodal AI Agent for Automated Medical Report Analysis

## Project Overview

This project leverages Multimodal AI Agents to analyze medical reports from various specialist perspectives, including cardiology, psychology, pulmonology, neurology, endocrinology, and immunology. Using LangChain, OpenAI's GPT models, and PyMuPDF, the system extracts insights from a PDF medical report, processes it through multiple AI-powered agents, and generates a comprehensive multidisciplinary diagnosis.

## Features
- Multimodal AI Agents for different medical specialties.
- Automated PDF medical report extraction using PyMuPDF.
- Parallel processing of multiple AI agents using ThreadPoolExecutor.
- Final diagnosis generation by a Multidisciplinary AI Agent.
- Structured output storage for easy reference.

## Tech Stack
- Python (for core logic and parallel processing)
- LangChain (for AI agent orchestration)
- OpenAI GPT-3.5 Turbo (for AI-powered diagnosis)
- PyMuPDF (fitz) (for extracting text from PDF medical reports)
- ThreadPoolExecutor (for concurrent agent execution)
- JSON & File Handling (for structured result storage)

## How It Works
1. Extract Text from PDF: The system reads a medical report from a PDF file.
2. Run AI Agents: Each agent analyzes the report based on its specialization.
3. Generate Specialist Insights: AI provides specialist-specific findings.
4. Multidisciplinary Analysis: The final AI agent synthesizes all responses into a structured diagnosis.
5. Store the Output: The final diagnosis is saved as a text file for review.
