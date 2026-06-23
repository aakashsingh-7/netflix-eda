# 🎬 Netflix EDA — Content & User Analysis

> Exploratory Data Analysis of Netflix's content library and user behaviour using Python, Pandas, and Plotly.

---

## 📌 About the Project

This project performs end-to-end EDA on two Netflix datasets — one covering the content catalogue (~8,800 titles) and another covering user behaviour (~25,000 users). The goal is to uncover patterns in content trends, audience segmentation, and genre gaps.

---

## 📊 Analysis Covered

| Section | What it answers |
|---|---|
| 🎥 Movies vs TV Shows | What type of content dominates Netflix? |
| 📈 Netflix Growth | How has content volume changed over the years? |
| 🌍 Top Countries | Which countries produce the most content? |
| 🎭 Genre Analysis | What genres are most available? |
| 👤 User Behaviour | Watch time distribution, subscription types, favorite genres |
| 🧩 Audience Segmentation | Casual / Regular / Binge watchers |
| 👶 Age Analysis | Average watch time across age groups |
| 📉 Content Gap Analysis | Genres Netflix should invest more in (demand vs supply) |
| 🤝 Correlation Heatmap | Relationships between numeric user features |
| 🔍 Recommendation System | Filter content by country + genre |

---

## 🗂️ Datasets

| File | Rows | Key Columns |
|---|---|---|
| `netflix_titles.csv` | ~8,800 | title, type, director, country, release_year, rating, listed_in |
| `netflix_users.csv` | ~25,000 | Age, Country, Subscription_Type, Watch_Time_Hours, Favorite_Genre |

> ⚠️ Datasets are not included in this repo. Download from Kaggle and place in the root folder before running.

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly
- Jupyter Notebook

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/aakashsingh-7/netflix-eda.git
cd netflix-eda

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook netflix.ipynb
```

---

## 📁 Project Structure

```
netflix-eda/
├── netflix.ipynb       # Main analysis notebook
├── requirements.txt    # Dependencies
├── README.md
└── .gitignore
```

---

## 💡 Key Insights

- **Movies outnumber TV Shows** significantly on Netflix
- **Content peaked** in the late 2010s and has plateaued
- **USA, India, UK** are the top 3 content-producing countries
- **Drama and Comedy** are oversupplied; niche genres are underserved
- **Binge watchers** form a distinct high-value segment

---

## 👤 Author

**Aakash Singh**  
B.Tech AIML — GGSIPU  
[GitHub](https://github.com/aakashsingh-7)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
