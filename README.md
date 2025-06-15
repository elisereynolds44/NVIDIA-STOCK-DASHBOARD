# NVIDIA Stock Dashboard

An interactive multi-tab dashboard analyzing NVIDIA's stock performance, correlations with other major tech stocks, and key financial events. Built with Dash, Plotly, and Python, this app brings together clean data visuals and financial literacy for a user-friendly learning experience.

---

## Features

- **Stock Price Analysis (Price Trends Tab):**  
  Interactive time series plots for NVIDIA and its competitors with slider-based zoom, dropdown company selection, and growth normalized to 100 for easy comparison.

- **Earnings/Event Zoom (NVIDIA Focus Tab):**  
  Visualize NVIDIA’s raw stock price movements and zoom into specific earnings report weeks to examine volatility and market response. Includes a simulated volume chart to highlight trading activity.

- **Learn About Stocks Tab:**  
  Beginner-friendly markdown explanations and real-world examples of key stock terms such as closing price, volume, and adjusted close—designed to enhance financial literacy through interactivity.

- **Company Deep Dive Tab:**  
  Dropdown-based summaries of key companies in the tech sector, including what they do, what they sell, and why they matter—offering helpful context for interpreting stock trends and market influence.

---

## Tech Stack

- **Languages & Libraries:** Python, Dash, Plotly, Pandas  
- **Data Source:** CSV files downloaded from Yahoo Finance  
- **Tools:** VS Code, PyCharm, GitHub

---

## Project Structure

```
finalproject-take2/
├── app.py
├── callbacks.py
├── tabs.py
├── NVIDIA Project Write Up.pdf
├── visuals/
│   ├── price_plot.py
│   ├── heatmap.py
│   └── learn_content.py
├── data/
│   ├── AMD-2023.csv
│   ├── AMD-2024.csv
│   ├── DELL-2023.csv
│   ├── ...
│   ├── SPY-2024.csv
│   ├── time_series_backup.csv
│   ├── combine-data.py
│   └── data_downloader.py
├── correlation_matrix.csv
├── generate_correlation.py
├── README.md
```

---

## Getting Started

1. **Clone the Repository (SSH)**  
   `git clone 'git@github.com:elisereynolds44/NVIDIA-STOCK-DASHBOARD.git`

2. **Install Dependencies**  
   `pip install -r requirements.txt`

3. **Run the App**  
   `python app.py`

4. **Open in Browser**  
   Visit `http://127.0.0.1:8050`

---

## Future Improvements

- Add an earnings calendar and automated annotation markers  
- Expand to allow ticker symbol input and multi-company selection  
- Add a financial literacy quiz and/or market simulation game

---

## 👩‍💻 Author

**Elise Reynolds** – [@elisereynolds44](https://github.com/elisereynolds44)

---

Let me know if you want help writing your `requirements.txt`, adding screenshots, or deploying it online!