# Awesome-Invoice-AI-Extraction

Top Invoice AI Extraction Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Intelligent Document Processing, OCR, Structured Data Extraction & Accounts Payable Automation
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Invoice AI Extraction. These tools help businesses automatically extract structured data—vendor names, invoice numbers, dates, line items, totals, taxes—from PDFs, scans, and images, eliminating manual data entry and accelerating AP workflows.

Examples include Veryfi, Rossum, Nanonets, Docsumo, Klippa, Parseur, Affinda, Mindee, Extracta.ai, and Google Document AI (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom model fine-tuning, and transparent document processing — ideal for privacy-conscious finance teams, developers building AP automation, and organizations that need full control over sensitive invoice data without per-document pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Veryfi
Real-time OCR and document extraction API for invoices, receipts, and checks. Uses proprietary computer vision and LLM-based parsing with sub-second processing -
2
.

Rossum
Cloud-based document gateway for automated invoice processing. Uses AI with human-in-the-loop validation for touchless AP automation.

Nanonets
AI-powered document processing platform for invoice extraction, expense management, and workflow automation. Offers no-code model training -
2
.

Docsumo
Intelligent document processing platform specializing in invoice and bank statement extraction with 99%+ accuracy claims.

Klippa
Document automation platform with OCR and AI for invoice processing, receipt extraction, and ID verification.

Parseur
AI-powered document parser for invoices, emails, and PDFs. Automates data extraction with webhook and integration support.

Affinda
Document AI platform with pre-trained and custom invoice extraction models. Supports multi-language and complex layouts.

Mindee
Developer-first document parsing API with invoice, receipt, and financial document extraction capabilities.

Extracta.ai
AI-powered data extraction platform for invoices, receipts, and other business documents with customizable extraction templates.

Google Document AI
Google Cloud's enterprise document processing platform with pre-trained invoice parsers, OCR, and custom model training.

Open-Source GitHub Projects

InvoiceNet
Deep neural network for extracting intelligent information from invoice documents. One of the most starred open-source invoice extraction projects with ~2.5k stars and 400 forks. Python-based -
2
.

invoice2data
Python library for extracting structured data from PDF invoices using template-based parsing. Highly popular (~1.8k stars) with extensive template library for common invoice formats -
16
.

AIDocumentExtractorPro
Offline intelligent document parser using OCR + AI models (FLAN-T5, LayoutLM). Extracts structured data from invoices and receipts, exports to JSON, Excel, and SQLite. Includes PyQt6 GUI and no-code trainer for fine-tuning -
5
.

Invoice-Data-Extractor
Combines PaddleOCR for text extraction with Mistral-7B LLM for intelligent invoice parsing. Extracts invoice number, date, customer details, line items, taxes, and totals. Outputs structured JSON and CSV -
4
.

OACA Invoice Extraction Pipeline
End-to-end intelligent document processing pipeline using LayoutLMv3 and Tesseract OCR. Fine-tuned for named entity recognition on invoices with preprocessing, annotation tools, and training scripts -
12
-
19
.

Invoice Image Analyzer Agent
Full-stack FastAPI + React application for invoice extraction. Uses Tesseract OCR with optional layout-parser heuristics and Groq LLM for field parsing. Dockerized and deployable -
3
.

Sparrow
Open-source AI document data extraction tool with modular architecture. Supports invoices, statements, and forms. Can run locally on Mac with MLX or in cloud with GPU. Free for commercial use under $5M revenue -
15
.

eye-drop-accountant
Modern web app for receipt and invoice analysis using OpenAI GPT-4 Vision API. Drag-and-drop interface with vendor, total, and line item extraction. React/TypeScript frontend -
7
.

Donut Receipt Extraction
Streamlit application for receipt information extraction using Donut (Document Understanding Transformer). OCR-free approach using vision encoder-decoder. Fine-tuned on CORD dataset. Docker support -
6
.

Invoice Parser (eliashossain001)
Demonstrates end-to-end structured extraction from PDF invoices using Tesseract OCR + LayoutLMv3 or Donut. Script-first, no notebooks, designed for quick iteration and customization -
13
.

ocrbase
Self-hostable document OCR and structured data extraction API. Uses PaddleOCR-VL-1.5 for text extraction and LLM-powered parsing. Type-safe TypeScript SDK, real-time WebSocket updates, Docker deployment -
11
.

InvoSync
AI-powered invoice and purchase order reconciliation system using Tesseract OCR and RapidFuzz. Detects mismatches, corrects inconsistencies, and exports standardized CSV reports. React + Flask stack -
10
.

Q-Invoice-50M-Sovereign
53.5M-parameter sovereign specialist model for invoice JSON extraction. Runs on CPU, no closed-source dependencies. Extracts total_value, currency, line_count, vendor, due_date with strict schema conformance. Apache 2.0 -
8
.

PDF Table Extraction Tools
Community collection including Camelot, tabula-java, and other libraries for extracting tabular data from PDF invoices -
16
.

Additional Strong Open-Source Options

OCR Engines: Tesseract (Google's OCR engine, widely used as foundation), PaddleOCR (high-accuracy OCR with layout analysis), EasyOCR (ready-to-use OCR with 80+ language support) -
4
-
18
.

Layout-Aware Models: LayoutLMv3 (Microsoft, combines text + layout + visual features), Donut (OCR-free document understanding) -
6
-
13
.

LLM-Based Extraction: Mistral-7B, FLAN-T5, and GPT-4 Vision integrations for intelligent field parsing -
4
-
5
.

Post-Processing: RapidFuzz for fuzzy matching and reconciliation, Pandas for data manipulation -
10
.

Frameworks for building custom systems: Combine PaddleOCR for text extraction, LayoutLMv3 or Donut for document understanding, Mistral-7B or FLAN-T5 for field parsing, and FastAPI + PostgreSQL for the API layer. Add Docker for deployment and Redis + Celery for async processing.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Invoice extraction tools process sensitive financial data; ensure compliance with SOC 2, GDPR, and relevant accounting regulations.

Self-hosted open-source solutions require proper security hardening, model versioning, and regular accuracy validation.

Made for finance teams, AP automation engineers, document AI researchers, and developers building accounting workflows.
Let's make invoice extraction more open, accurate, and accessible.
