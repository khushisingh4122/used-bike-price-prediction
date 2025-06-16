# 🚲 Used Bike Prices Prediction with EDA and Machine Learning

Hi there! 👋  
This project is all about understanding how different factors influence the **resale prices of used bikes** and using that understanding to predict those prices using machine learning. It's built with 💛 and the intention to learn and help others learn too.

---

## 📁 What's Inside This Project

- `Used_Bike_Prices.ipynb` – This is the main Jupyter Notebook where all the magic happens: data cleaning, EDA (Exploratory Data Analysis), feature engineering, and modeling.
- `bikes.csv` – This is the dataset used. It contains real-world data of bikes, including model names, years, kilometers driven, mileage, power, location, owner info, and prices.

---

## 📊 What This Project Does

Here’s what you’ll find in this notebook:

1. **Data Cleaning**  
   🧼 The dataset contains messy values like "35 kmpl", "50,000 Km", and "19.8 bhp". These are cleaned using regular expressions and converted into proper numbers so we can work with them.

2. **Feature Engineering**  
   🏗️ I created new columns like:
   - `bike_age` → How old the bike is (2025 - model year)
   - `cc` → Extracted from the model name like "350cc"
   - Converted categorical columns using one-hot encoding

3. **EDA (Exploratory Data Analysis)**  
   📈 I used beautiful plots to visualize:
   - Price distribution
   - Correlation between features
   - Price based on model year
   - Scatter plots showing how CC or bike age affects price

4. **Machine Learning Models**
   - **Linear Regression** (simple but interpretable)
   - **Random Forest Regressor** (strong performance, better for this case)

5. **Feature Importance**  
   🌟 I visualized which features matter most for price prediction.

---

## ⏱️ How Long It Takes to Run

- **On a normal laptop** (with 4-8 GB RAM):  
  ⌛ It takes **less than 30 seconds** to run the entire notebook.

- **No GPU is needed** – it's a light ML model, ideal for beginners.

---

## ⏳ Time Complexity & Performance

- **Data Cleaning & Preprocessing:**  
  Linear in nature — O(n), where n is the number of rows.

- **One-Hot Encoding:**  
  Linear with respect to number of rows and unique categories.

- **Linear Regression:**  
  Time complexity: O(n * d²) where:
  - n = number of records (rows)
  - d = number of features (columns)

- **Random Forest Regressor:**  
  Time complexity: O(t * m * log n), where:
  - t = number of trees (100 in this case)
  - m = number of features
  - n = number of samples

But don't worry — with this dataset, it runs fast. 🚀

---

## ❤️ Why I Made This

I created this project as part of my learning journey in Data Science and Machine Learning. I wanted to apply my skills to a real dataset, explore patterns, and share something meaningful with others.

If you're someone new to data science, this project is perfect to explore how to:
- Handle real-world messy data
- Visualize and tell stories with charts
- Build simple yet effective prediction models

---

## 🔧 Tools and Technologies Used

- Python (Jupyter Notebook)
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualizations)
- scikit-learn (for ML)

---

## 💬 How to Use It

1. Download or clone this repository
2. Open `Used_Bike_Prices.ipynb` in Jupyter Notebook
3. Make sure `bikes.csv` is in the same folder
4. Run all the cells one by one
5. Enjoy the journey from raw data to smart predictions 🚲📈

---

## ✨ Final Thoughts

Thank you for visiting this project. If it helped you learn something new or made you curious about bikes or machine learning — that means the world to me 💛

Feel free to **star ⭐ this repo**, give feedback, or reach out. Let’s keep learning and growing together!

---

Made with 💻, ☕, and a lot of curiosity.  
— *K*
