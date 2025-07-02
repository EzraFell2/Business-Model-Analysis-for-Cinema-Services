# 🎬 Cinema Business Intelligence & Customer Clustering

This project explores business intelligence and machine learning techniques to analyze and propose business models for a cinema enterprise. Using real-world ticketing data from CGV Đà Nẵng (May 2019), our team developed a customer segmentation system and interactive dashboards to support decision-making in cinema operations and marketing strategy.

## 📌 Project Overview

- **Course**: Business Process Analysis  
- **Tools Used**: Python, Power BI, Excel  
- **Main Focus**: Customer segmentation using KMeans & DBSCAN, Business KPIs dashboard  

---

## 📁 Project Structure

### 📊 Business Intelligence (BI)
- **EDA**: Ticket & Customer data visualization
- **KPI Tracking**: Total revenue, ticket sales, screening schedules, popcorn sales, and online booking rates
- **Dashboard**: Power BI dashboard for operational insights

### 🧠 Machine Learning
- **Data Cleaning & Feature Engineering**:
  - RFM Analysis: Recency, Frequency, Monetary
  - Genre preferences, seating behavior, time-of-day analysis
- **Clustering Models**:
  - `KMeans`: 4-cluster segmentation using Elbow Method
  - `DBSCAN`: Automatic cluster detection with anomaly recognition
- **Evaluation Metrics**:
  - Silhouette Score
  - Customer behavioral summaries per cluster

## 🛠 Technologies & Libraries

| Tool        | Use Case                          |
|-------------|-----------------------------------|
| **Python**  | Data analysis & ML                |
| Pandas      | Data wrangling                    |
| Numpy       | Numerical operations              |
| Scikit-learn| Clustering models (KMeans, DBSCAN)|
| Power BI    | Dashboard creation                |
| Excel       | Preprocessing                     |

## 📌 Dataset

The dataset includes real ticket sales data from CGV Đà Nẵng:

- `CUSTOMER.csv`: 4,479 records with demographic attributes  
- `TICKET.csv`: 35,508 transactions including ticket details  
- `MOVIE_TABLE.csv`: 19 movies with metadata (genre, duration, rating, etc.)


## 📈 Dashboard Highlights

- **Overview Dashboard**: Tracks key metrics and revenue trends by date  
- **Customer Dashboard**: Shows demographics, segmentation, and behavior  
- **Scheduling Dashboard**: Analyzes popular time slots and genres  
- **Insights**:  
  - Popcorn sales were low (~0.35%)  
  - Website booking was underutilized (~0.27%)  
  - Top-viewed movies include _La Llorona_, _Avengers_, _Ngôi Đền Kỳ Quái_  
  - High engagement from student demographics  

## 🤖 Clustering Results

### KMeans:
- **Cluster 0**: Inactive users – target for reactivation  
- **Cluster 1 & 2**: High-spending outliers – potential VIP customers  
- **Cluster 3**: Loyal, moderate spenders – ideal for upselling

### DBSCAN:
- Identified **VIP outliers** with very high purchase frequency  
- More flexible than KMeans for irregular customer behavior  

## 📂 Files in Repository

| File | Description |
|------|-------------|
| `dashboard.pbix` | Power BI file with interactive KPIs |
| `preprocessing.py` | Data cleaning and feature engineering script |
| `clustering.py` | Customer segmentation models (KMeans & DBSCAN) |
| `README.md` | Project documentation |
| `data/` | Folder containing raw and cleaned CSVs |

## 🧠 Key Learning Outcomes

- Applied real BI & ML methods to a business context  
- Extracted valuable business insights from noisy data  
- Built an interactive Power BI dashboard for strategic decisions  
- Identified customer segments to guide marketing and operations  
