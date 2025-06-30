# MySql_Streamlit_Dashborad
Live sales dashboard using Python, MySQL, and Streamlit with real-time updates, Plotly charts, and dynamic insights.

# Real-Time Sales Dashboard with MySQL, Python & Streamlit

This beginner-friendly project shows you how to build a real-time interactive sales dashboard using:

✅ **MySQL** as the database  
✅ **Python** for backend logic  
✅ **Streamlit** to create the dashboard interface  
✅ **Plotly** for bar and pie charts  
✅ **Auto-refresh** and **AI-style insights**

---

## 💡 Features

- Live connection to a MySQL database using `mysql-connector-python`
- Bar chart for sales by product
- Pie chart for sales by region
- Smart auto-generated insight messages
- Refreshes every 60 seconds or manually with a button

---

## 📁 Folder Structure
mysql_dashboard/
├── app.py # Streamlit dashboard
├── insights.py # Auto-generated sales insights
├── requirements.txt # Python dependencies

---


## 📦 Install Requirements

```bash
pip install -r requirements.txt

## Run the Dashboard
#Run this line of code in your terminal:

streamlit run app.py

# Then open the app in your browser at:
http://localhost:8501
