# BudgetBuddy: Intelligent Personal Finance Assistant

## 1. Problem Statement and Target Users

Managing personal finances is a challenge for many individuals, especially when it comes to tracking spending, setting goals, and making informed decisions. Traditional budgeting apps often require manual data entry and lack personalized, actionable advice. Our target users are young professionals and students who want an intelligent, interactive, and easy-to-use tool to help them manage their finances, set goals, and receive tailored recommendations.

## 2. Proposed Solution and Key Features

BudgetBuddy is an AI-powered personal finance assistant that leverages LLMs and real-time data to provide:
- **Automated Statement Parsing:** Users can upload credit card statements for automatic parsing and categorization.
- **Goal Setting & Tracking:** Users set financial goals and track progress.
- **Cost-of-Living & Financial Data Integration:** Real-time data from external APIs for personalized insights.
- **Conversational Agent:** An animal character provides chat-based financial advice and reminders.
- **Calendar Integration:** Events and reminders for bill payments and financial milestones.
- **Multimodal Capabilities:** Image upload/vision for receipts and statements.
- **CRUD Operations:** Manage income, expenses, and goals.
- **Real-Time Metrics:** Visual dashboards and analytics.
- **Agent-Based Recommendations:** Personalized suggestions using LLMs.

## 3. Technical Stack
- **Frontend:** Android App (Kotlin/Jetpack Compose)
- **Backend Orchestration:** Python (FastAPI), LangChain
- **LLM Support:** OpenAI GPT-4o, Anthropic Claude 3.5
- **Database:** PostgreSQL (for user data, transactions, goals)
- **Vector Store:** ChromaDB (for RAG and semantic search)
- **APIs:**
  - Cost-of-Living API
  - Financial Data API
  - External APIs for enrichment
- **Deployment:** Google Cloud Platform (App Engine, Cloud SQL)

## 4. System Architecture Diagram

![System Architecture Diagram](system_architecture.png)

*Diagram created using Draw.io. See attachments for the original file.*

## 5. Success Criteria and Evaluation Metrics
- **User Engagement:** Number of active users and session frequency.
- **Accuracy:** Correct parsing and categorization of statements (target: >95%).
- **Goal Achievement:** Percentage of users meeting their financial goals.
- **Response Quality:** User ratings of LLM-generated advice (target: >4/5).
- **System Reliability:** Uptime and error rates (target: >99% uptime).
- **Deployment Readiness:** Successful deployment on Google Cloud and/or Streamlit Cloud.

## 6. Feasibility
The project leverages existing APIs, cloud services, and LLM platforms to ensure rapid development and deployment within the course timeline. The modular architecture allows for incremental feature delivery and testing.

---

*For more details, refer to the attached system architecture diagram.*
