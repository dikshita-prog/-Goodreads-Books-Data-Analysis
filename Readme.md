# 📚 Goodreads Books Data Analysis

This project explores the **Goodreads books dataset** using **SQLite, pandas, and seaborn**. It performs data cleaning, exploratory data analysis (EDA), and visualization to uncover key insights into book popularity, ratings, genres, and trends.

---

## 🧠 Objectives

- Clean and structure raw Goodreads data
- Understand book popularity by ratings and tags
- Explore genre-based trends
- Visualize relationships between tags, ratings, and publication year
- Answer business-like questions with SQL + Python

---

## 🔍 Dataset Overview

The dataset contains:

- `books.csv`: Book titles, ratings, genres, counts, and metadata  
- `tags.csv`: Mapping of tag IDs to tag names  
- `book_tags.csv`: Relationship between books and their tags 
- `ratings.csv`: Contains ratings by a users for different books as {user_id,book_id,rating} set
- `to_read.csv`: Provides IDs of the books marked "to read" by each user, as {user_id,book_id} pairs.

---

## 🧠 Tools & Technologies

- Python (pandas, seaborn, matplotlib)  
- SQLite (for querying)  
- Jupyter Notebook  

---

## 📊 Key Insights

- 📈 **Top-rated books** tend to have thousands of reviews and belong to popular genres like fiction, fantasy, and young adult.  
- 🔖 **Most common tags**: Fiction, Fantasy, Romance, Young Adult.  
- 🏆 **Genres with highest average ratings**: Books tagged with "poetry", "historical-fiction", and "science" scored highly.  
- 🧠 Books with **more tags tend to have slightly higher average ratings**—suggesting tagging improves discoverability and popularity.

---

## 📌 Project Structure

```
📁 Goodreads-Books-Analysis/
│
├── Goodreads_Analysis.ipynb   			     # Final notebook with EDA and visualizations
├── README.md                                # Project overview
├── 📁 data/								 # Folder for all datasets
	├──books.csv                             # Main dataset
	├── tags.csv                             # Tag reference data
	├── book_tags.csv                        # Book-to-tag mapping
	├── to_read.csv							 # Books marked as to_read by users
	└── ratings.csv 						 # Ratings of individual books by each user


```

---

## ✅ How to Run

1. Clone this repo  
2. Open `Goodreads_Analysis.ipynb` in Jupyter  
3. Install dependencies:  
```bash
pip install pandas matplotlib seaborn sqlite3
```  
4. Run all cells and explore the visuals!

---

## 📌 Author

Made with ❤️ by [Dikshita Aggarwal]  
_This project was part of my Data Analytics portfolio using real-world book data._
