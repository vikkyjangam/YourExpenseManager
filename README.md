<h1 style="font-size: 2.5em; font-weight: 800;">📊 Personal Expense Manager</h1> 

> *An intelligent, AI-powered expense tracking app built using **Power Apps, Copilot, and Microsoft Dataverse**.*  
> Track expenses, visualize trends, and interact with an AI assistant for data-driven insights.  

---

## 🔧 Built With  
| Technology | Purpose |  
|------------|---------|  
| **Microsoft Power Apps** | Low-code platform for building the app |  
| **Microsoft Copilot (Preview)** | Embedded AI assistant for natural language queries |  
| **Dataverse** | Cloud storage for structured expense data |  
| **Power Automate** *(Optional)* | Email reminders/automation |  
| **Power BI** *(Optional)* | Advanced analytics/visualizations |  

---

## 💡 Key Features  

### ✨ Core Functionality  
- **Add/Edit/Delete Expenses**  
  Input category, amount, date, and payment method.  
- **Category-wise Breakdown**  
  Pie chart visualization of spending by category (Food, Utilities, Transport, etc.).  
- **Cost Trend Analysis**  
  Line chart to track spending habits over time.  

### 🤖 AI-Powered Insights  
- **Copilot Integration**  
  Ask questions like:  
  - *“What was my highest expense last month?”*  
  - *“Which payment method did I use most?”*  
- **Search & Filter**  
  Quickly find expenses by description or category.  

### 📧 Optional Extras  
- **Email Summaries** (via Power Automate)  
  Send expense reports directly to your inbox.  

---

## 🚀 Getting Started  

### 1️⃣ Clone & Import  
- Download the `.msapp` file (provided separately).  
- In **Power Apps**, go to *Apps > Import Canvas App* and select the file.  

### 2️⃣ Configure Dataverse  
- Create/import the **Expense table** in Dataverse.  
- Ensure column names match the app’s schema (e.g., `Category`, `Amount`, `Date`).  

### 3️⃣ Enable Copilot  
- Open the app in **Power Apps Studio**.  
- Turn on *Copilot Preview* and connect it to your dataset.  
- Provide a short description (e.g., *"This dataset tracks personal expenses by category, date, and payment method."*).  

---

## 🧠 Sample Copilot Queries  
- *“Show all travel-related expenses.”*  
- *“Which category exceeded my budget?”*  
- *“Compare spending between January and February.”*  

---

## 📸 Screenshots  
![App Screenshot 1](app1.png)
![App Screenshot 2](app2.png)
![App Screenshot 3](app3.png)
![App Screenshot 4](app4.png)

---

## 🔒 Security & Best Practices  
- **Role-based access**: Configure permissions in the Power Apps environment.  
- **Verify AI suggestions**: Cross-check Copilot’s responses before acting on them.  
- **Regular backups**: Export Dataverse data periodically.  

---

> **Note**: For advanced features (Power Automate/Power BI), additional setup may be required.  


