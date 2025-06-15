# NVIDIA Stock Dashboard

An interactive multi-tab dashboard analyzing NVIDIA's stock performance, correlations with other major tech stocks, and key financial events. Built with Dash, Plotly, and Python, this app brings together clean data visuals and financial literacy for a user-friendly learning experience.

---

## Features

- **Stock Price Analysis:**  
  Interactive time series plots for NVIDIA and competitors with slider-based zoom and date range selection.

- **Earnings/Event Zoom:**  
  Focus on key market dates like earnings reports to explore how price trends shift around them.

- **Learn About Stocks Tab:**  
  Beginner-friendly markdown explanations and examples to teach core investing and market concepts.

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

1. **Clone the Repository**  
   `git clone https://github.com/your-username/nvidia-stock-dashboard.git`

2. **Install Dependencies**  
   `pip install -r requirements.txt`

3. **Run the App**  
   `python app.py`

4. **Open in Browser**  
   Visit `http://127.0.0.1:8050/`

---

## Future Improvements

- Add an earnings calendar and automated annotation markers  
- Expand to allow ticker symbol input and multi-company selection  
- Add a financial literacy quiz and/or market simulation game

---

## 👩‍💻 Author

**Elise Reynolds** – [@your-github](https://github.com/your-github)

---

Let me know if you want help writing your `requirements.txt`, adding screenshots, or deploying it online!