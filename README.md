<div align="center">

<!-- Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:7c3aed&height=200&section=header&text=LeetCode%20Pandas%20Study%20Plan&fontSize=36&fontColor=ffffff&fontAlignY=38&desc=15%20Questions%20%7C%20Data%20Manipulation%20with%20Python&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

<!-- Badges -->
<br/>

![Language](https://img.shields.io/badge/Language-Python-3776ab?style=for-the-badge&logo=python&logoColor=white)
![Library](https://img.shields.io/badge/Library-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)
![Progress](https://img.shields.io/badge/Progress-15%2F15-22c55e?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=for-the-badge)

<br/>

> **Solving all 15 LeetCode Pandas problems** — covering DataFrame creation, filtering, reshaping, and method chaining. Built as part of my data science learning journey.

</div>

---

## 📌 About This Repository

This repo contains my solutions to the **LeetCode Introduction to Pandas** study plan — a curated set of 15 problems designed to build core `pandas` skills used in real-world data science and analytics workflows.

Each solution is written in **clean, idiomatic Python** with brief comments explaining the approach.

---

## 🗂️ Problem Index

| # | Problem | Difficulty | Topic | LeetCode |
|---|---------|------------|-------|----------|
| 01 | Create a DataFrame from List | 🟢 Easy | DataFrame Creation | [#2877](https://leetcode.com/problems/create-a-dataframe-from-list/) |
| 02 | Get the Size of a DataFrame | 🟢 Easy | DataFrame Info | [#2878](https://leetcode.com/problems/get-the-size-of-a-dataframe/) |
| 03 | Display the First Three Rows | 🟢 Easy | Viewing Data | [#2879](https://leetcode.com/problems/display-the-first-three-rows/) |
| 04 | Select Data | 🟢 Easy | Filtering & Selection | [#2880](https://leetcode.com/problems/select-data/) |
| 05 | Create a New Column | 🟢 Easy | Column Operations | [#2881](https://leetcode.com/problems/create-a-new-column/) |
| 06 | Drop Duplicate Rows | 🟢 Easy | Data Cleaning | [#2882](https://leetcode.com/problems/drop-duplicate-rows/) |
| 07 | Drop Missing Data | 🟢 Easy | Data Cleaning | [#2883](https://leetcode.com/problems/drop-missing-data/) |
| 08 | Modify Columns | 🟢 Easy | Column Operations | [#2884](https://leetcode.com/problems/modify-columns/) |
| 09 | Rename Columns | 🟢 Easy | Column Operations | [#2885](https://leetcode.com/problems/rename-columns/) |
| 10 | Concatenate DataFrames | 🟢 Easy | Combining Data | [#2886](https://leetcode.com/problems/concatenate-dataframes-vertically/) |
| 11 | Fill Missing Data | 🟢 Easy | Data Cleaning | [#2887](https://leetcode.com/problems/fill-missing-data/) |
| 12 | Reshape Data: Melt | 🟢 Easy | Reshaping | [#2888](https://leetcode.com/problems/reshape-data-melt/) |
| 13 | Reshape Data: Pivot | 🟢 Easy | Reshaping | [#2889](https://leetcode.com/problems/reshape-data-pivot/) |
| 14 | Encode Column | 🟢 Easy | Encoding | [#2890](https://leetcode.com/problems/encode-column/) |
| 15 | Method Chaining | 🟢 Easy | Best Practices | [#2891](https://leetcode.com/problems/method-chaining/) |

---

## 🧠 Concepts Covered

```
DataFrame Creation      →  pd.DataFrame(), from lists/dicts
Viewing & Inspection    →  .head(), .shape, .info()
Selection & Filtering   →  .loc[], boolean indexing
Column Operations       →  assign, rename, arithmetic transforms
Data Cleaning           →  drop_duplicates(), dropna(), fillna()
Combining DataFrames    →  pd.concat()
Reshaping               →  .melt(), .pivot_table()
Encoding                →  pd.get_dummies(), .astype('category').cat.codes
Method Chaining         →  fluent, readable pipeline-style code
```

---

## 📁 Repository Structure

```
leetcode-pandas-study-plan/
│
├── solutions/
│   ├── 2877_create_dataframe.py
│   ├── 2878_get_size.py
│   ├── 2879_first_three_rows.py
│   ├── 2880_select_data.py
│   ├── 2881_create_new_column.py
│   ├── 2882_drop_duplicates.py
│   ├── 2883_drop_missing_data.py
│   ├── 2884_modify_columns.py
│   ├── 2885_rename_columns.py
│   ├── 2886_concatenate_dataframes.py
│   ├── 2887_fill_missing_data.py
│   ├── 2888_melt.py
│   ├── 2889_pivot.py
│   ├── 2890_encode_column.py
│   └── 2891_method_chaining.py
│
└── README.md
```

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Programming Language |
| Pandas | Data Manipulation |
| LeetCode | Problem Platform |

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/<your-username>/leetcode-pandas-study-plan.git
cd leetcode-pandas-study-plan

# Install dependency
pip install pandas

# Run any solution
python solutions/2877_create_dataframe.py
```

---

## 💡 Key Takeaways

- **`.loc[]` vs boolean indexing** — both work, but `.loc[]` is more explicit for label-based access
- **`.assign()`** — preferred over direct column assignment for method chaining
- **`fillna()` vs `dropna()`** — use based on whether missing data carries signal or not
- **`melt()` / `pivot_table()`** — essential for converting between wide and long format
- **Method chaining** — makes pandas code readable and reduces intermediate variable clutter

---

## 👤 Author

**Ramesha Gangadharappa (Ram)**  
B.Tech Data Science | New Horizon College of Engineering, Bengaluru  
Freelance Data Analyst @ [Decoder Space](https://www.fiverr.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=flat-square&logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/Tuberamesh)
[![Instagram](https://img.shields.io/badge/Instagram-@decoder__space-E4405F?style=flat-square&logo=instagram)](https://instagram.com/decoder_space)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:2563eb&height=100&section=footer" width="100%"/>

*Part of my Data Science portfolio — solving real problems, one dataset at a time.*

</div>
