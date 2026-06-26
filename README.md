# Task 4 - Geospatial Data Analysis

## 📌 Internship
VirtualWorks Lab by Emogi — Data Analytics Internship

## 📝 Task Overview
Analyzed location-based data to identify optimal areas for business expansion.
Visualized sales data geographically and detected regions with high demand
but low store presence using mapping tools.

## 🛠️ Tools & Libraries Used
| Tool | Purpose |
|---|---|
| Python 3 | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Static charts |
| Seaborn | Statistical visualization |
| Folium | Interactive map generation |
| Jupyter Notebook | Development environment |

## 📂 Dataset
- 20 Indian cities, 13 features
- Key columns: City, Region, Latitude, Longitude, Monthly_Sales,
  Num_Stores, Demand_Score, Expansion_Opportunity

## 🔍 Analysis Performed
1. Loaded and inspected geospatial dataset (20 cities)
2. Monthly sales analysis by region
3. Demand Score vs Store Presence scatter plot
4. Expansion opportunity detection (High demand + Low stores)
5. Interactive Folium map with city-wise sales bubbles
6. Top 5 cities by monthly sales
7. Region-wise average demand scoring

## 📊 Key Findings

### 1. Top 5 Cities by Monthly Sales
| City | Monthly Sales | Stores | Demand Score |
|---|---|---|---|
| Pune | ₹4,31,490 🥇 | 12 | 94 |
| Surat | ₹4,22,654 | 3 | 53 |
| Guwahati | ₹4,01,279 | 7 | 62 |
| Bangalore | ₹3,79,365 | 5 | 41 |
| Visakhapatnam | ₹3,51,648 | 8 | 74 |

### 2. Expansion Opportunity Detected
| City | State | Demand Score | Stores | Monthly Sales |
|---|---|---|---|---|
| Coimbatore | Tamil Nadu | 83 🔴 | 1 | ₹1,70,151 |

> High demand (83/100) but only 1 store — immediate expansion recommended!

### 3. Region-wise Avg Demand Score
| Region | Avg Demand Score |
|---|---|
| North | 79.25 🥇 |
| West | 68.75 |
| Central | 66.33 |
| South | 65.17 |
| Northeast | 62.00 |
| East | 59.00 |

## 💡 Recommendations
1. **Expand in Coimbatore** — demand score 83 with only 1 store
2. **Invest in North region** — highest avg demand score (79.25)
3. **Scale up Surat** — ₹4.22L sales with only 3 stores, high opportunity
4. **Review East & Northeast** — lowest demand, focus on retention not expansion
5. **Visakhapatnam** — demand score 74, only 8 stores, good expansion candidate

## 📂 Files
| File | Description |
|---|---|
| `geospatial_dataset.csv` | Raw city-wise sales dataset |
| `geospatial_final.csv` | Final analyzed dataset |
| `geospatial_analysis.ipynb` | Jupyter Notebook with full code |
| `sales_by_region.png` | Monthly sales by region chart |
| `demand_vs_stores.png` | Demand vs store presence scatter plot |
| `india_sales_map.html` | Interactive Folium map of India |

## 📈 Results Summary
- Analyzed **20 cities** across **6 regions** of India
- Identified **Coimbatore** as top expansion opportunity
- **North region** has highest demand at 79.25 avg score
- **Pune** leads with ₹4.31L monthly sales
