# 🎬 Netflix 1990s Movie Analysis

This project explores **Netflix movies released during the 1990s**, as part of a research task for a nostalgic production company. The goal is to gain insights into movie duration, genre trends, and other interesting patterns from that decade using exploratory data analysis (EDA).

---

## 📌 Background

Netflix, founded in 1997 as a DVD rental service, has grown into one of the world’s largest media platforms. With its vast catalog of content, Netflix offers a great opportunity for data-driven research.

As a data analyst for a production company focused on nostalgic media, your task is to analyze **movies from the 1990s** and uncover insights using real Netflix data.

---

## 📂 Project Structure

```

Netflix\_90s\_Movie\_Analysis/
├── Netflix\_90s\_Movie\_Analysis.ipynb   # Jupyter Notebook with full analysis
├── data/
│   └── netflix\_data.csv               # Original dataset
├── README.md                          # This file

````

---

## 📥 Dataset Description

- **File:** `netflix_data.csv`
- **Source:** Provided for analysis
- **Scope:** All Netflix content, filtered to include only movies released from **1990 to 1999**

| Column Name     | Description                     |
|------------------|---------------------------------|
| show_id          | Unique ID for the show          |
| type             | Type of content (Movie/TV Show) |
| title            | Name of the title               |
| director         | Director name                   |
| cast             | Main cast                       |
| country          | Country of origin               |
| date_added       | When it was added to Netflix    |
| release_year     | Year it was released            |
| duration         | Duration in minutes             |
| description      | Short summary                   |
| genre            | Primary genre                   |

---

## 📊 Key Insights

- 📅 **Movies filtered:** All movies released between **1990 and 1999**
- ⏱️ **Most common duration:** `94 minutes`
- 🔫 **Short action movies (< 90 mins):** `7` identified
- 📈 **Visualized distribution** of movie durations using a histogram

---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- pandas
- matplotlib

---

## 🚀 How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/AbdooMatrix/Netflix_90s_Movie_Analysis.git

2. Open `Netflix_90s_Movie_Analysis.ipynb` in Jupyter Notebook or VS Code.

3. Run all cells to reproduce the analysis and visualizations.

---

## 💡 Possible Next Steps

* Explore cast and director frequency in 1990s content
* Compare Netflix’s 1990s movie library to other decades
* Create a Streamlit app or dashboard for interactive exploration

---

## 👤 Author

**Abdelrahman Mostafa**
GitHub: [@AbdooMatrix](https://github.com/AbdooMatrix)
```
