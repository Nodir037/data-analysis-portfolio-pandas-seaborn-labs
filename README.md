# 📊 DataViz & Analysis Portfolio

> A collection of hands-on data analysis and visualization projects built with Python.

> Python yordamida ma'lumotlarni tahlil qilish va vizualizatsiya qilishga bag'ishlangan amaliy loyihalar to'plami.

---

## 📁 Project Structure / Loyiha tuzilmasi

```
DataViz-Analysis-Portfolio/
│
├── bike_share.ipynb     # Bike rental analysis — Regression & Heatmaps
├── cborn.ipynb          # Young people survey — Seaborn visualization
├── kirish_puli.ipynb    # College tuition analysis
├── goldsilver.ipynb     # Data normalization / scaling techniques
├── example.ipynb        # NFL pass data — Missing value handling
├── top1.ipynb           # Weather & Olympics — Matplotlib basics
└── README.md
```

---

## 📌 Notebooks / Notebooklar

---

### 🚲 `bike_share.ipynb` — Bike Rental Analysis / Velosiped Ijarasi Tahlili

**EN:** Explores bike rental demand using regression plots and heatmaps. Analyzes the relationship between temperature, month, weekday, humidity, and wind speed with total rentals.

**UZ:** Velosiped ijarasi talabini regressiya grafiklari va heatmap yordamida tahlil qiladi. Harorat, oy, hafta kuni, namlik va shamol tezligining ijara soniga ta'sirini o'rganadi.

- **Dataset:** `bike_share.csv`
- **Libraries / Kutubxonalar:** `seaborn`, `pandas`, `matplotlib`, `numpy`
- **Techniques / Texnikalar:** `regplot`, `residplot`, `x_jitter`, `x_estimator`, `x_bins`, `crosstab`, `heatmap`, correlation matrix

---

### 🧑‍🎓 `cborn.ipynb` — Young People Survey / Yoshlar So'rovnomasi

**EN:** Analyzes internet usage habits among young people by age and gender.

**UZ:** Yoshlar orasida internetdan foydalanish odatlarini jinsi va yoshi bo'yicha tahlil qiladi.

- **Dataset:** `young-people-survey-responses.csv`
- **Libraries / Kutubxonalar:** `seaborn`, `pandas`, `matplotlib`
- **Techniques / Texnikalar:** `catplot`, `set_style`, `set_palette`, style and color variants

---

### 🏫 `kirish_puli.ipynb` — College Tuition Analysis / Kollej O'qish Narxlari

**EN:** Analyzes US university tuition fees by region and visualizes a personal budget line.

**UZ:** AQSh universitetlarining o'qish narxlarini mintaqalar bo'yicha tahlil qiladi va shaxsiy byudjet chizig'ini vizualizatsiya qiladi.

- **Dataset:** `college_datav3.csv` (DataCamp)
- **Libraries / Kutubxonalar:** `seaborn`, `pandas`, `matplotlib`
- **Techniques / Texnikalar:** `displot`, `histplot`, `subplots`, `axvline`, density plots

---

### 🥇 `goldsilver.ipynb` — Data Normalization / Normalizatsiya Usullari

**EN:** Compares four normalization methods on chemical element data.

**UZ:** Kimyoviy elementlar ma'lumotlari ustida to'rtta normalizatsiya usulini solishtiradi.

- **Dataset:** `goldsilver.csv`
- **Libraries / Kutubxonalar:** `pandas`, `numpy`, `seaborn`
- **Techniques / Texnikalar:** Max Scaling, Mean Scaling, Min-Max Scaling, Robust Scaling

---

### 🏈 `example.ipynb` — NFL Data Cleaning / NFL Ma'lumotlarini Tozalash

**EN:** Identifies and handles missing values (NaN) in real sports data.

**UZ:** Real sport ma'lumotlaridagi yo'qolgan qiymatlarni (NaN) aniqlash va to'ldirish.

- **Dataset:** `example.csv` (NFL games)
- **Libraries / Kutubxonalar:** `pandas`, `numpy`
- **Techniques / Texnikalar:** `fillna`, median imputation, missing value indicator (`-1`)

---

### 🌦️ `top1.ipynb` — Weather & Olympics / Ob-havo & Olimpiada

**EN:** Covers Matplotlib fundamentals by comparing Austin and Seattle weather and analyzing 2016 Olympic medals.

**UZ:** Matplotlib asoslarini Austin va Seattle ob-havo ma'lumotlarini solishtirish va 2016 Olimpiada medallarini tahlil qilish orqali o'rganadi.

- **Datasets / Datasetlar:** `austin_weather.csv`, `seattle_weather.csv`, `summer2016.csv`, `medals_by_country_2016.csv`
- **Libraries / Kutubxonalar:** `matplotlib`, `pandas`
- **Techniques / Texnikalar:** `ax.plot`, markers (`o`, `v`, `*`), multiple subplots

---

## 🛠️ Technologies / Texnologiyalar

| Technology | Purpose / Maqsad |
|---|---|
| Python 3.x | Main programming language / Asosiy dasturlash tili |
| Pandas | Data loading & cleaning / Ma'lumot yuklash va tozalash |
| NumPy | Numerical computations / Matematik hisob-kitoblar |
| Seaborn | Statistical visualization / Statistik vizualizatsiya |
| Matplotlib | Plots & charts / Grafiklar va diagrammalar |
| Jupyter | Interactive notebook environment / Interaktiv muhit |

---

## 🚀 Getting Started / Ishga tushirish

```bash
# Install dependencies / Kutubxonalarni o'rnatish
pip install pandas numpy seaborn matplotlib jupyter

# Launch Jupyter / Jupyter-ni ishga tushirish
jupyter notebook
```

---

## 👤 Author / Muallif

This project was created as hands-on practice in Python data analysis and visualization.

Ushbu loyiha Python va ma'lumotlar tahlili bo'yicha amaliy mashqlar sifatida yaratilgan.
