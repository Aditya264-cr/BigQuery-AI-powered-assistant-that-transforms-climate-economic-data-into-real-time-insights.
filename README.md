# 🌍 Climate–Economy Insight Assistant  

> 🏆 Built for the **Kaggle Competition: BigQuery AI – Building the Future of Data**

## 📖 Overview  

The **Climate–Economy Insight Assistant** is a **BigQuery AI-powered web application** that transforms **raw climate and economic data** into **actionable insights, forecasts, and visualizations**.  

This project demonstrates how **BigQuery’s Generative AI, Vector Search, and Multimodal capabilities** can go beyond traditional analytics to address real-world business and policy challenges.  

Judges will not just see a tool, but a **working system** that:  
- Delivers **real-time, region-specific insights**  
- Generates **AI-powered forecasts** using **BigQuery TimesFM**  
- Performs **semantic vector search** for global comparisons  
- Analyzes **satellite images** with multimodal AI  
- Produces **executive-ready reports with traceable sources**  

---

## ✨ Key Features  

### 🧠 Executive Insights  
- AI-generated **summaries, justifications, impacts, and recommendations**  
- Adapt dynamically to **region and indicator selected**  

### 📊 Forecasting  
- **10-year forecasts** generated with **BigQuery AI.FORECAST**  
- Results visualized in **charts + raw data tables**  
- Region and time-range specific  

### 🖼️ Image Analysis (Multimodal)  
- Fetches **real satellite/climate images** for the selected region  
- AI generates **context-aware insights** based on visual + numeric data  

### 🔍 Vector Search  
- **Semantic similarity search** using BigQuery VECTOR_SEARCH  
- Finds **countries with similar climate/economic patterns**  
- Restricted by **region and indicator**  

### 📑 Data Sources  
- Displays **real-time sources** (World Bank, NOAA, IEA, UNDP, NASA, etc.)  
- Ensures **transparency and credibility**  

### 📥 Report Export  
- Generate **professional PDF reports**  
- Includes insights, forecasts, charts, and data sources  

---

## 🛠️ Tech Stack  
- **Frontend:** React (Next.js), TailwindCSS, Chart.js  
- **Backend:** Node.js/Express (`reference-server.js`)  
- **AI/ML:** Google BigQuery AI  
  - `AI.FORECAST`, `AI.GENERATE_TABLE`, `ML.GENERATE_EMBEDDING`, `VECTOR_SEARCH`  
- **Multimodal:** BigQuery Object Tables + Image APIs (NASA EarthData, NOAA, Google Earth Engine)  
- **PDF Export:** jsPDF + html2canvas / Puppeteer (modular export)  

---

## ⚙️ Setup  

### 1. Clone Repository  
```bash
git clone https://github.com/your-username/climate-economy-insight.git
cd climate-economy-insight
