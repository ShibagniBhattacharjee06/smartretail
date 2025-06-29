## 🧾 Project Summary

### 🏷️ **Project Title**  
**Smart Retail AI Platform**

---

### 📄 **Project Description**  
Smart Retail AI Platform is a modern, AI-integrated web application designed to empower retail professionals with advanced data insights. The platform brings together two core machine learning solutions deployed via Hugging Face Spaces — a **Trend Analyzer** and a **Price Optimizer** — into a unified, interactive frontend.

- The **Trend Analyzer** allows users to upload CSV files containing chronological retail data (e.g., stock prices, sales figures) and dynamically visualize trends over time.
- The **Price Optimizer** takes retail input variables like demand forecast, current inventory, perishability, and expiry days, and predicts optimized product pricing to maximize profits or accelerate stock clearance.

This platform is built for clarity, accessibility, and real-world usability — making retail AI not only powerful but also intuitive for non-technical users.

---

### 🎯 **Project Vision**  
To create a seamless bridge between artificial intelligence and real-world retail operations by offering a clean, interactive frontend that enables anyone — from store managers to supply chain analysts — to use AI tools without coding expertise.

---

### 🔮 **Future Scope**
- 🛍️ Integrate live e-commerce data feeds from platforms like Flipkart, Amazon, and Shopify  
- 📈 Build a complete dashboard for multiple time-series visualizations  
- 🔄 Add downloadable reports and export options (PDF/CSV)  
- 📦 Introduce additional AI tools like Inventory Predictor, Seasonal Sales Forecaster, etc.  
- 📲 Extend platform functionality into a mobile-first PWA or native app  

---

### ✨ **Key Features**

#### 📊 Trend Analyzer  
[🔗 Try Model on Hugging Face](https://huggingface.co/spaces/shibagni/walmart-demand-forecast)  
- Uploads user-provided CSV files with date-based datasets  
- Processes and parses using `pandas`  
- Renders dynamic line charts with `matplotlib`  
- Allows column selection for multi-dimensional plotting  
- Built with Gradio for a clean, interactive interface  
- Ideal for spotting retail trends and anomalies quickly  

#### 💰 Price Optimizer  
[🔗 Try Model on Hugging Face](https://huggingface.co/spaces/shibagni/dynamic-pricing-engine)  
- Inputs: demand forecast, stock quantity, expiry days, and perishability flag  
- Trained ML regression model for smart price prediction  
- Recommends real-time pricing to clear stocks or maximize margins  
- Includes visual feedback (charts and results) in Gradio interface  
- Built for accessibility — no need for technical users to understand ML internals  

---

### 🚀 **Live Frontend Demo**  
🌐 [Launch Smart Retail AI Platform](https://smartretail.vercel.app/)

> This demo integrates both AI models into an interactive cyberpunk-themed frontend built using HTML, CSS, and JavaScript.

---

💡 *Note: The frontend is entirely static and lightweight, while the machine learning intelligence is hosted via Hugging Face Spaces. All model computations happen securely and independently through those endpoints.*
