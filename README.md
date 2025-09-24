# Scrapeme Web Scraping Project

This repository contains a **Google Colab notebook** and the resulting **CSV dataset** for scraping product data from [Scrapeme.live](https://scrapeme.live/shop). The project demonstrates a step-by-step web scraping workflow, data extraction, and basic exploratory data analysis (EDA).

---

## 📋 Project Overview

**Goal:** Scrape product information including:

- Name  
- Price  
- Description  
- Category  
- SKU  
- Tags  
- Stock Status  

from all pages of [Scrapeme Shop](https://scrapeme.live/shop) and save it in a CSV file.

---

## 🛠 Tools Used

- **Python 3**  
- **Libraries:** `requests`, `BeautifulSoup` (`bs4`), `pandas`, `matplotlib`  
- **Google Colab** for notebook execution  

---

## 💻 Files in this Repository

| File | Description |
|------|-------------|
| `scraping_notebook.ipynb` | The Colab notebook with the scraping code and EDA |
| `scrapeme_products_full.csv` | The resulting dataset of all products |

---

## 📈 Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset overview (`.head()`, `.info()`, `.describe()`)  
- Checking missing values  
- Using `.loc` and `.iloc` for selection  
- Category and tags frequency analysis  
- Stock status summary  
- Price distribution and top 10 most expensive products visualization  

---

## 🚀 How to Use

1. Open the notebook in **Google Colab**:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/REPO/blob/main/scraping_notebook.ipynb)

2. Run the cells step by step to:  
   - Scrape all products  
   - Create a CSV dataset  
   - Perform basic EDA  

3. CSV dataset will be saved as `scrapeme_products_full.csv`.

---

## ⚠️ Notes

- SSL warnings are ignored (`verify=False`) to allow scraping without certificate errors.  
- The code is designed for educational purposes and works with [Scrapeme.live](https://scrapeme.live/shop) only.  

---

## 📝 Author

**Your Name**  
- GitHub: [github.com/USERNAME](https://github.com/USERNAME)  
- Email: your.email@example.com  

---

