# 🏢 Real Estate Investment Automation (n8n)

Enterprise-grade real estate investment analysis and workflow automation built using **n8n**.  
This project automates property discovery, financial analysis, portfolio insights, and AI-driven reporting using API integrations, Google Sheets, and LLM agents.

---

## 🚀 Key Features

- 📋 **Dynamic Property Intake Form**
  - Location, price range, beds, baths, property type, and filters
- 🔍 **Automated Property Search**
  - Fetches real estate listings via external APIs (RapidAPI / Zillow-like sources)
- 📊 **Investment Metrics Calculation**
  - Down payment, mortgage, expenses
  - Cash flow, cap rate, cash-on-cash ROI
- 📈 **Portfolio Aggregation**
  - Consolidates results across multiple properties
- 🤖 **AI-Powered Market Insights**
  - Daily market sentiment summary
  - Top properties ranked by ROI and cap rate
- 📤 **Automated Reporting**
  - Appends structured data to Google Sheets
  - Sends HTML email reports via Gmail

---

## 🧠 Architecture Overview


---

## 🧮 Investment Metrics Calculated

- Monthly & annual cash flow
- Cap rate (%)
- Cash-on-cash ROI (%)
- Mortgage payment
- Property tax, insurance, maintenance
- Price vs Zestimate comparison
- Rent-to-price ratio

---

## 🛠️ Tech Stack

- **n8n** – Workflow orchestration & BPA
- **JavaScript** – Custom financial calculations
- **Google Sheets API** – Portfolio storage
- **Gmail API** – Automated reporting
- **LLM (Gemini / LangChain)** – AI market analysis
- **RapidAPI** – Real estate data source

---

## 🔐 Environment Variables

Set the following environment variables in n8n:

```env
GOOGLE_SHEET_ID=your_google_sheet_id
ALERT_EMAIL=your_email@example.com
RAPIDAPI_KEY=your_api_key
