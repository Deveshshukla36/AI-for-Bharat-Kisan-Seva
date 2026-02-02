# 🌾 Kisan-Seva Agent: AI for Bharat

**Empowering Bharat’s Farmers with Specification-Driven AI**

## 📖 Overview
Kisan-Seva Agent is an intelligent assistant designed for the "Next Billion" users in rural India. Most farmers struggle with language barriers and the complexity of government documentation. Our solution uses **Agentic AI** to simplify these hurdles through a simple voice-based interface.

### The Problem
* **Language Gap:** Official documents are often in English or complex formal Hindi.
* **Information Overload:** Thousands of government schemes exist, but farmers don't know which ones they qualify for.
* **Price Volatility:** Lack of data-driven insights on when to sell crops.

### The Solution
A voice-enabled AI Agent that:
1. **Analyzes Gov PDFs:** Uses RAG (Retrieval-Augmented Generation) to answer questions about schemes.
2. **Predicts Prices:** Analyzes market trends to suggest the best time to sell.
3. **Speaks Local:** Operates in regional dialects using AWS neural text-to-speech.

---

## 🛠️ Technical Architecture
This project is built using **Specification-Driven Development (SDD)** with the following stack:

* **Orchestration:** [Kiro](https://kiro.ai) (for defining requirements and design specs).
* **LLM (The Brain):** **Amazon Bedrock (Claude 3.5 Sonnet)** for superior reasoning and Hinglish support.
* **Knowledge Retrieval:** **Amazon Bedrock Knowledge Bases** (RAG) for scanning official PDFs.
* **Voice Interface:** **Amazon Transcribe** (Speech-to-Text) & **Amazon Polly** (Text-to-Speech).
* **Compute:** **AWS Lambda** for a scalable, serverless backend.

---

## 📂 Project Structure
Following the AI for Bharat submission guidelines, this repo contains:
* `requirements.mmd`: A Mermaid logic flow of the user journey.
* `design.md`: Technical specification and AWS service mapping.
* `README.md`: Project overview and impact.

---

## 🚀 Impact & Future Roadmap
* **Phase 1 (Current):** Concept and Specification-Driven Design.
* **Phase 2:** Prototype development with AWS Bedrock integration.
* **Phase 3:** Integration with WhatsApp API for even easier access in villages.

## 🤝 Team Code Homeboys 
* **Project Lead:** Devesh Shukla 
* **Submission for:** AI for Bharat Hackathon 2026
