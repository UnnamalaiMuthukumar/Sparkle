# Sparkle — Data Visualization Web App

An interactive data visualization web application built with Python and Streamlit. Upload any CSV file and instantly explore your data through multiple chart types with built-in preprocessing tools.

## Live Demo
> Run locally using the steps below

## Features
- Upload any CSV file and auto-generate summary statistics
- Data preprocessing tools:
  - Handle missing values (auto drop)
  - Convert columns to numeric types
  - Standardize / normalize features
- Interactive charts:
  - Bar Chart
  - Scatter Plot (Plotly)
  - Line Chart (Plotly)
  - Box Plot
  - Pie Chart
- Clean, minimal UI built with Streamlit

## Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Streamlit | Web app framework |
| Pandas | Data loading & preprocessing |
| Plotly | Interactive charts |
| Matplotlib / Seaborn | Static visualizations |
| NumPy | Numerical operations |

## How to Run Locally
```bash
# 1. Clone this repo
git clone https://github.com/YOUR_USERNAME/sparkle-data-viz.git
cd sparkle-data-viz

# 2. Install dependencies
pip install streamlit pandas matplotlib seaborn plotly numpy

# 3. Run the app
streamlit run sparkle.py
```

## What I Learned
- Building interactive web apps without HTML/CSS using Streamlit
- Handling real-world data preprocessing (missing values, type conversion, normalization)
- Creating dynamic, interactive charts with Plotly
- Connecting UI inputs to backend data logic in Python

## Author
Unnamalai Muthukumar 
BVoc AI & ML | MS-CSDA @ IIT Patna (Pursuing)  
[LinkedIn] www.linkedin.com/in/unnamalai-muthukumar | [GitHub] https://github.com/UnnamalaiMuthukumar
