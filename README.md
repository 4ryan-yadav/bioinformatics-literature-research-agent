# Bioinformatics Literature Research Agent

An AI-powered **n8n workflow** that automates literature research for bioinformatics and computational biology topics.

The workflow takes a research topic through an n8n form, searches the web for relevant sources, uses Google Gemini to synthesize the findings, generates a structured research brief, converts it into a PDF, and uploads the result to Google Drive.

## Workflow

```text
User enters research topic
          ↓
      n8n Form
          ↓
    Serper Web Search
          ↓
    Search Result Filtering
          ↓
    Google Gemini AI Agent
          ↓
    Report Formatting
          ↓
      HTML Report
          ↓
       PDFMonkey
          ↓
      PDF Download
          ↓
      Google Drive