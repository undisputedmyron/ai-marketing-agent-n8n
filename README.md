# AI Marketing Performance Agent (n8n) 🚀

A no-code/low-code AI-powered system that transforms raw Google Sheets marketing data into polished, client-ready email reports — automatically.

## 🔍 What It Does

- Fetches campaign data from Google Sheets (ad spend, impressions, clicks, conversions, revenue, etc.)  
- Uses Gemini AI to compute key metrics: CTR, conversion rate, ROI, revenue breakdowns, and performance insights  
- Generates a clean, human-readable summary report with analysis and recommendations  
- Sends the report automatically via Gmail  
- Maintains context with memory to allow consistent, coherent follow-up reporting  

## ✔️ Why It Matters

Manual marketing reporting is tedious, error-prone, and repetitive. This automation reduces:

- 📉 Manual work & copy-paste errors  
- 🕒 Time spent on weekly or monthly reports  
- 📑 Spreadsheet overload  
- 📧 Last-minute email scramble  

Instead, you get:

- ⚡ Faster, consistent reporting  
- 📈 Immediate insight into performance and ROI  
- 📊 Professional-quality output — ready to send to clients or stakeholders  

## 🛠️ Tech Stack

| Component | Role |
|----------|------|
| **n8n** | Workflow automation and orchestration |
| **Gemini AI** | Data analysis, metric computation, natural-language report generation |
| **Google Sheets API** | Source of marketing data |
| **Gmail API** | Automatic delivery of reports |
| **Memory node** | Context management for sequential reporting |

## 🚀 Getting Started

1. Clone or download this repo  
2. Import `ai-marketing-agent.json` into your n8n workspace  
3. Configure API credentials:  
   - Gemini  
   - Google Sheets  
   - Gmail  
4. Update Sheet ID and column mappings according to your data structure  
5. Activate the workflow — you’re live  

## 🎯 Use Cases

- Marketing agencies and consultants  
- Freelancer or in-house marketers  
- Clients needing weekly/monthly performance reports  
- Small businesses wanting automated analytics without building dashboards  

## 📈 Future Improvements (Roadmap)

- Add support for multiple clients (multi-sheet / multi-account)  
- Add scheduling or webhook triggers (e.g. run weekly automatically)  
- Include additional data sources (Facebook Ads, Google Ads, etc.)  
- Add optional export formats (PDF, CSV, HTML)  
- Integrate customization options (client name, branding, email templates)  

## 📄 License & Contribution

This project is open for contributions. Feel free to fork or raise issues.  
(You may want to add a LICENSE file accordingly.)

---

*Built by: Segun*  
