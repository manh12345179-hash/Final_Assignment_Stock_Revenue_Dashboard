# Analyzing Historical Stock/Revenue Data and Building a Dashboard

IBM Data Science / Python Project for Data Science final assignment.

## Contents

- `Final_Assignment_Stock_Revenue_Dashboard.ipynb` — complete notebook for Questions 1–6.
- `requirements.txt` — Python dependencies.
- `.gitignore` — common notebook/editor artifacts.

## Run in Google Colab

1. Upload `Final_Assignment_Stock_Revenue_Dashboard.ipynb` to Google Colab.
2. Choose **Runtime → Run all**.
3. Wait for all stock-data requests and both Plotly charts to finish.
4. If no cell reports an error, use **File → Save** (or **Download → Download .ipynb**) so the submitted notebook includes real outputs and both charts.
5. Submit the executed `.ipynb` rather than the unexecuted template.

The notebook uses Yahoo Finance (`yfinance`) for stock history and the IBM Skills Network teaching page for the quarterly revenue tables. The latter preserves the source table order used by the course, so `tesla_revenue.tail()` ends with a Revenue value of 27 (million USD). Revenue is not sorted in-place before `.tail()`; chronological sorting is done only inside the chart function.

## Dependencies

Python 3.10+ recommended. Install the dependencies using:

```bash
pip install -r requirements.txt
```

## GitHub

From a terminal opened in this directory:

```bash
git init
git add .
git commit -m "Complete stock and revenue dashboard assignment"
```

Then create a GitHub repository and push with its remote URL, or use GitHub CLI (`gh repo create`).
