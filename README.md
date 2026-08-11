# 🤖 n8n AI Data Analyst

An AI-powered Data Analyst workflow built using **n8n, OpenAI, Google Sheets, and Gmail**.

The AI agent can read sales data directly from Google Sheets, analyze it based on natural-language questions, generate useful insights, and send professional HTML reports through Gmail.

## 🚀 Features

- 💬 Natural-language chat interface
- 📊 Reads sales data directly from Google Sheets
- 🤖 AI-powered analysis using OpenAI
- 🧠 Conversation memory for contextual interactions
- 📈 Calculates sales metrics and rankings
- 💡 Generates key business insights
- 📧 Sends analysis reports automatically through Gmail
- 📝 Generates clean HTML-formatted email reports
- 🔄 Built as an automated n8n workflow

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **OpenAI** – AI analysis and natural-language processing
- **Google Sheets** – Sales data source
- **Gmail** – Automated email reporting

## ⚙️ Workflow

The workflow follows this process:

**User Message → AI Agent → Google Sheets → Data Analysis → Gmail Report**

The AI Agent uses Google Sheets as a tool to retrieve the latest sales data. It analyzes the requested information and can send the generated report through Gmail when requested.

## 📊 Example Queries

Users can ask questions such as:

- What are the total sales?
- Which product generated the highest revenue?
- Which region performed the best?
- Who are the top 3 salespersons by total sales?
- Give me key insights from the sales data.
- Send this analysis to my Gmail.

## 📧 Automated Email Reports

When an email report is requested, the AI Agent generates a structured HTML report containing:

- Report title
- Analysis summary
- Important metrics
- Key insights
- Recommendations

The report is then automatically sent using the Gmail integration.

## 🧩 Main Workflow Components

### Chat Trigger
Receives questions from the user through the n8n hosted chat interface.

### AI Agent
Understands the user's request, decides when to retrieve data, performs analysis, and generates the response.

### OpenAI Chat Model
Provides the AI capabilities used by the agent.

### Simple Memory
Maintains conversational context between messages.

### Google Sheets Tool
Retrieves the latest sales data used for analysis.

### Gmail Tool
Sends generated analysis reports directly through Gmail.

## 🔐 Security

Credentials and private information are not included in this repository.

The public workflow template uses placeholders for sensitive configuration such as:

- Google Sheet ID
- Gmail recipient
- n8n credential IDs
- Instance-specific identifiers

Users should configure their own credentials after importing the workflow into n8n.

## 📥 How to Use

1. Download the workflow JSON file from this repository.
2. Import the JSON workflow into n8n.
3. Connect your OpenAI credentials.
4. Connect your Google Sheets account.
5. Select your Google Sheet containing the sales data.
6. Connect your Gmail account.
7. Configure the recipient email address.
8. Test the workflow.
9. Publish the workflow.
10. Start asking questions through the chat interface.

## 💬 Example

**User:**

> Analyze the sales data and tell me the top 3 salespersons by total sales.

The AI Agent retrieves the spreadsheet data, calculates the results, and returns the analysis.

**User:**

> Now send this report over Gmail.

The workflow automatically generates and sends a formatted HTML email report.

## 📁 Workflow File

`AI-Data-Analyst-n8n-GitHub-Safe.json`

This is a sanitized version of the n8n workflow that can be safely shared publicly.

## 🎯 Project Purpose

This project demonstrates how **AI and workflow automation** can be combined to create a conversational data analysis system that can retrieve business data, generate insights, and automate reporting without requiring users to manually analyze spreadsheets.

## 👨‍💻 Author

**Nikhil Chetry**

Built as a hands-on project exploring **AI Agents, Data Analysis, and Workflow Automation using n8n**.

## 📄 License

This project is licensed under the MIT License.
