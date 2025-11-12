# Book Scraping Project

### Overview
This project focuses on **web scraping** data from the [Books to Scrape](https://books.toscrape.com/) website using **Python**, **BeautifulSoup**, and **Requests**.  
The goal is to extract detailed book information such as title, category, rating, price, stock, and description — then store it for further analysis or visualization.

---

### Objectives
- Automate the collection of book data from multiple pages.
- Extract and clean relevant information from each product page.
- Build a structured dataset suitable for data analysis or machine learning tasks.

---

### Technologies Used
- **Python 3.x**
- **BeautifulSoup4**
- **Requests**
- **Pandas**
- **Regex (re)**
- **Jupyter Notebook / Google Colab**

---

### Extracted Features
Each book entry contains the following attributes:
| Feature | Description |
|----------|-------------|
| Category | Book category from breadcrumb navigation |
| Code | Unique product code (UPC) |
| Title | Book title |
| Rating | Star rating (1–5) |
| Price (excl. tax) | Price before tax |
| Price (incl. tax) | Price including tax |
| Tax | Amount of tax applied |
| Stock Status | Availability information |
| Number of Stock Available | Numeric stock count extracted using regex |
| Description | Book description text |
| Number of Reviews | Total customer reviews |
| Cover | Full image URL of the book cover |

---

### Workflow Summary
1. **Collect URLs** of all books across multiple pages.
2. **Send GET requests** using `requests`.
3. **Parse HTML content** with `BeautifulSoup`.
4. **Extract key data** fields and clean text.
5. **Store results** in a Pandas DataFrame.
6. **(Optional)** Export dataset to `.csv` for analysis.

---

### Insights & Takeaways
- Practicing scraping teaches **HTML parsing, data cleaning, and automation**.
- Websites like “Books to Scrape” are great for safe, ethical scraping exercises.
- The resulting dataset can be used for **sentiment analysis**, **NLP modeling**, or **pricing analytics**.

---

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/cindypramudita/bookstoscrape.git
