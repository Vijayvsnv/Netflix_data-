📺 Netflix Data Exploratory Data Analysis (EDA)

🔍 Overview

This project presents an **Exploratory Data Analysis (EDA)** on the publicly available **Netflix Titles dataset**. It reveals insights into the types of content, release trends, most frequent countries of production, and more. The analysis was done using Python in **Google Colab** with libraries like `Pandas`, `Matplotlib`, and `Seaborn`.

---

### 📁 Dataset

* 📦 **File:** `netflix_titles.csv`
* 📌 **Source:** [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* 🎯 **Total Records:** 6,000+ rows of Movies & TV Shows with metadata like director, cast, country, rating, etc.

---

### 🔧 Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas, Numpy**
* **Matplotlib & Seaborn**

---

### 🧹 Data Cleaning Steps

* Removed unnecessary columns like `show_id` and `description`.
* Handled missing values using `.fillna()` and `.dropna()` appropriately.
* Converted date fields like `date_added` to datetime format.
* Extracted features like `year_added`, `month_added`, `duration_int`, and `duration_type`.

---

### 📊 Key Insights Visualized

* 📈 Total Movies vs TV Shows count.
* 📆 Number of releases by year.
* 🌍 Top 10 countries by content production.
* 🎬 Top 10 directors with the most content.

> All visualizations are created using Matplotlib for clear and insightful representation.

---

### 🖼 Sample Visuals

📊 ![Sample Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Iconic_image_placeholder.png/640px-Iconic_image_placeholder.png)
*Add your own generated plots here as screenshots or save them from Colab.*

---

### 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `netflix_EDA.py` or use the `.ipynb` file in Google Colab.
3. Make sure the CSV file is in the correct path (`/content/netflix_titles.csv` or local path).
4. Run all cells or lines to reproduce the analysis and visualizations.

---

### 👨‍💻 Author

* **Name:** Vijay Bairagi
* **GitHub:** [@vijayvsnv](https://github.com/vijayvsnv)
* **LinkedIn:** *Add your LinkedIn link*
* **Website:** [smartstockadda.com](https://smartstockadda.com)

---

### 📜 License

This project is open-source and available under the [MIT License](LICENSE).
