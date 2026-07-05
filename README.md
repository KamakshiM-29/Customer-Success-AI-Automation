# Customer Success AI Automation

## Overview

Customer Success AI Automation is an end-to-end workflow designed to help Customer Success teams efficiently manage customer feedback at scale. Built using n8n, Google Gemini, Google Sheets, Gmail, Slack, and Looker Studio, the solution automates the entire feedback management process—from collecting customer responses to generating actionable insights and enabling timely follow-up.

The workflow analyzes customer feedback using AI, identifies customer sentiment, calculates customer health, prioritizes cases based on business rules, sends personalized email responses, notifies internal teams of high-priority issues through Slack, and continuously updates a live operational dashboard for real-time visibility.

## Key Features

- AI-powered customer feedback analysis using Google Gemini
- Automated customer sentiment classification and summarization
- Customer health scoring and priority assignment
- Personalized email responses based on customer feedback
- Automatic Slack notifications for high-priority customer cases
- Centralized customer feedback repository in Google Sheets
- Live Looker Studio dashboard with real-time insights
- End-to-end workflow automation built using n8n
## Business Problem

Customer Success teams often manage customer feedback across multiple tools, making it difficult to respond quickly, identify at-risk customers, and maintain a consistent follow-up process. Manual analysis of feedback can delay decision-making, increase operational effort, and make it challenging to prioritize customer issues effectively.

Organizations also struggle to consolidate customer insights into a single source of truth, limiting visibility into customer sentiment, recurring issues, and overall customer health.
## Solution Overview

This project automates the customer feedback management lifecycle using AI and workflow automation.

Customer feedback submitted through Google Forms is captured in Google Sheets and processed by Google Gemini to extract sentiment, summarize responses, determine customer health, assign priority levels, recommend next actions, and route cases based on predefined business rules.

The processed data is automatically stored in Google Sheets, personalized customer emails are generated, high-priority cases are escalated to Slack, and all insights are visualized in a live Looker Studio dashboard that updates automatically as new responses are received.
## Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation |
| Google Gemini | AI-powered feedback analysis |
| Google Forms | Customer feedback collection |
| Google Sheets | Centralized data storage |
| Gmail | Automated customer communication |
| Slack | Internal escalation and notifications |
| Looker Studio | Live operational dashboard |
