# Cloud Cost Visibility Report – Power BI
**Overview**
This Power BI report provides a comprehensive overview of cloud resource consumption and associated costs, enabling stakeholders to optimize cloud spending and manage resource usage effectively.

**📊Key Metrics** 
- Total Cost
- Total Resources
- Total Sevices Running
- Avg. number of resources per service
- Inbound and Outbound Traffic
- Cost by Service:
- Interactive bar chart showing cost and number of resources by service name (e.g., Cloud Tasks, Dialogflow, BigQuery, etc.)
- Resource-Level Costing
    - Detailed cost breakdown per resource including usage units and quantity
- Sales Over Time: It helps to identify cost spikes, anomalies, and trends

**⚙️Technical Details:**
- Built with Power BI, offering intuitive, interactive visuals and detailed drill-down capabilities.
- DAX (Calculate, Filter, All, Usage of Var, IF Statements)
- Interactive Elements (Filtes, Slicers, Parameters, Bookmarks)

**🔄 Data Source**
- This report uses data pulled via a Python script, showcasing how Power BI can integrate with Python for dynamic data processing.
- The script fetches cloud billing cost data from a public dataset hosted on Hugging Face.
- Power BI supports Python scripting, making it possible to ingest, transform, and visualize data using Python inside the Power BI environment.

## 🐍 Python Code
```python
import pandas as pd
df = pd.read_csv("https://huggingface.co/datasets/sairamn/gcp-cloud-billing-cost/resolve/main/data.csv")
```

**📸 report Preview**

![image](https://github.com/user-attachments/assets/e3ff39f9-9811-4f8d-b2f8-674daec61875)
![image](https://github.com/user-attachments/assets/9ec6c343-4c61-4681-a060-9cf4e1748ed9)

**💼 About Me**
I'm a Data Analyst & Power BI Developer with 3+ years of experience building reports that drive strategic decision-making. This project reflects my skills in data visualization, business storytelling, and actionable insight delivery.









