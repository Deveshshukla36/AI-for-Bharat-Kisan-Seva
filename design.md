# Design Specification: Kisan-Seva Agent

## 1. User Story
As a small-scale farmer in Bharat, I want to ask questions in my local language so that I can understand government schemes without reading 50-page English PDFs.

## 2. Technical Architecture (AWS Stack)
- **Model:** Amazon Bedrock (Claude 3.5 Sonnet) - Best for Indian regional reasoning.
- **RAG Engine:** Bedrock Knowledge Bases - To process official Govt PDFs.
- **Voice Interface:** Amazon Transcribe (Speech-to-Text) & Amazon Polly (Hindi/Neural accents).
- **Backend:** AWS Lambda (Serverless) - Keeps costs low for rural deployment.

## 3. Implementation Plan
- **Phase 1:** Define specs in Kiro (requirements.mmd & design.md).
- **Phase 2:** Connect Bedrock to indexed Government agriculture PDFs.
- **Phase 3:** Deploy voice-first interface via WhatsApp API.
