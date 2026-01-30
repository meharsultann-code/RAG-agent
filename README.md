
🤖 AI-Powered Psychological Interviewer & Growth Planner
This repository contains the professional n8n workflow for an advanced, multi-agent AI system designed to conduct psychological interviews and generate actionable 7-day growth plans.

🌟 Key Features
State-Managed Interviewing: Uses Google Sheets as a persistent database to track questionNumber and conversationHistory.

Automated Reminder System: A Schedule Trigger scans the database daily to identify inactive users and sends automated reminders via Telegram.

Multi-Agent Architecture: Includes a specialized Interview Agent for data collection and a Solution Architect for report generation.

Cultural & Language Intelligence: Supports English and Roman Urdu with a "Desi Mode" to understand cultural nuances like joint family systems.

Professional Reporting: Uses Markdown formatting to deliver clean, structured 7-day action plans directly to the user.

🛠️ Technical Workflow
Triggers: Dual-trigger system using Telegram Trigger (user-led) and Schedule Trigger (system-led).

Logic Engine: Filter Nodes with type-conversion logic ensure reminders are only sent to incomplete sessions.

Data Sync: Real-time updates to Google Sheets using $now expressions for accurate lastActive tracking.

📁 Files
CoreAnalyzer.json: The complete n8n workflow file ready for import.
