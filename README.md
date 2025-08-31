📊 Trending Keyword Tracker → Hashtag Tweet

This project is an automated workflow built with n8n that fetches the latest trending keywords from Google Trends, filters for technology-related topics, and publishes the top trend to Twitter (X) while also storing the results in Google Sheets for record-keeping.

🚀 Features :

⏰ Automated scheduling – Runs daily at a set time.

🌐 Google Trends API – Fetches real-time trending search keywords.

🧠 Smart filtering – Extracts only technology-related trends.

🗑️ Duplicate removal – Ensures no repeated trends are posted.

🐦 Twitter (X) integration – Posts the top trending keyword automatically.

📑 Google Sheets logging – Stores the trend with date and time for analysis.

🛠️ Workflow Overview :

Schedule Trigger → Runs daily at 17:00.

HTTP Request → Calls Google Trends API (via SerpAPI).

Code Node → Filters and selects top technology trend.

Remove Duplicates → Prevents reposting old trends.

Create Tweet → Posts keyword to Twitter/X.

Edit Fields → Prepares metadata (Date, Time, Trend).

Google Sheets → Appends data to a tracking sheet.

📂 Technology Stack :

n8n – Workflow automation platform

SerpAPI – Google Trends API

Twitter API – Tweet automation

Google Sheets API – Data storage

⚙️ Setup Instructions :

Clone or import workflow into your n8n instance.

Configure credentials:

SerpAPI Key (for Google Trends).

Twitter OAuth2 API (for posting tweets).

Google Sheets OAuth2 (for appending records).

Update the Google Sheets document ID and sheet name in the workflow.

Set your preferred schedule time in the trigger node.

Activate the workflow. ✅
