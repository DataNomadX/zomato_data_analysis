# zomato_data_analysis
The project focuses on data cleaning, transformation, and exploratory data analysis (EDA) using Python. this is purely data-focused, aimed at uncovering patterns in ratings, cost, and services like online ordering and table booking.

---

## 📊 Project Objectives

- Clean and preprocess the raw Zomato dataset.
- Explore the data visually to find patterns and trends.
- Understand how different features like `online_order`, `book_table`, `rest_type`, and `city` affect ratings and popularity.

---

## 🔧 Data Cleaning Steps Performed

1. Removed unnecessary columns like `url`, `phone`, `address`, etc.
2. Replaced missing and inconsistent values in:
   - `rate` (e.g., "NEW", "-") replaced with numeric mode.
   - `approx_cost(for two people)` cleaned and converted to integers.
   - `rest_type` and `cuisines` filled with mode values.
3. Removed duplicate entries.
4. Cleaned text-based noise in restaurant names.
5. Converted categorical columns like `online_order` and `book_table` to binary (Yes/No → 1/0).
6. Extracted and analyzed frequent dishes mentioned in `dish_liked`.

---

## 📈 EDA Highlights

Some questions we explored through visualizations:

- How does online ordering affect restaurant ratings?
- Do restaurants that allow table booking have higher ratings?
- Which areas (`city`) receive the most customer votes?
- What are the most common restaurant types?
- How does average cost relate to ratings?

All charts are stored in the `/charts` folder and generated via Seaborn and Matplotlib.

---

## 📁 Dataset Info

The original dataset was sourced from [Zomato's public listing in Bangalore] and contains ~43,000 rows with the following attributes:

- Restaurant name
- Location
- Online ordering (Yes/No)
- Table booking availability
- Average rating
- Cuisines served
- Cost for two
- Votes received
- And more...

---

## 🛠️ Tools & Libraries Used

- **Python 3.x**
- **Pandas** for data manipulation
- **NumPy** for numerical handling
- **Matplotlib** & **Seaborn** for visualization
- **Jupyter Notebook** for interactive development

---


