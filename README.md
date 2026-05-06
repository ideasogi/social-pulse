# 📱 Social Media Usage — Exploratory Data Analysis

A data analysis project exploring behavioral patterns across 7 social media platforms, with a focus on what the data reveals for **marketing strategy**.

---

## What this project does

This notebook analyzes data from **1,000 social media users** to answer:

- Which platform captures the most daily time?
- Which platform delivers the highest engagement per minute spent?
- Does posting more content lead to more likes?
- How do time, posts, likes, and followers relate to each other?

---

## Key findings

| Finding | Marketing implication |
|---|---|
| Instagram leads in average daily minutes | Strongest for brand awareness campaigns |
| Time spent ≠ engagement quality | Evaluate platforms by engagement efficiency, not screen time alone |
| Posting more does NOT reliably earn more likes | Content quality and platform fit matter more than posting frequency |

---

## Dataset

**Source:** [Social Media Usage Dataset – Kaggle](https://www.kaggle.com/datasets/bhadramohit/social-media-usage-datasetapplications)  
**Size:** 1,000 users × 6 columns  
**Platforms:** Instagram, TikTok, Facebook, YouTube, Pinterest, LinkedIn, Snapchat  

| Column | Description |
|---|---|
| `App` | Social media platform |
| `Daily_Minutes_Spent` | Minutes per day on that app |
| `Posts_Per_Day` | Posts created daily |
| `Likes_Per_Day` | Likes received daily |
| `Follows_Per_Day` | New followers gained daily |

---

## Tools used

| Tool | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, grouping |
| `seaborn` | Statistical charts (bar, box, scatter, heatmap) |
| `matplotlib` | Chart sizing and display |
| `plotly` | Interactive visualizations (used in Streamlit app) |
| `numpy` | Numeric operations and correlation matrix |

---

## How to run locally

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/social-pulse.git
cd social-pulse

# 2. Install dependencies
pip install pandas numpy seaborn matplotlib plotly jupyter

# 3. Open the notebook
jupyter notebook socialmedia_final.ipynb
```

---

## Project structure

```
social-pulse/
│
├── socialmedia_final.ipynb   ← main analysis notebook
├── README.md                 ← this file
└── data/
    └── social_media_usage.csv
```

---

## Author

**bsogdiana** — learning data analysis and building projects that connect data to real marketing decisions.

---

## What's next

- [ ] Add demographic variables (age, gender) to segment the analysis
- [ ] Build a Streamlit dashboard for interactive exploration
- [ ] Compare findings against global social media benchmark reports
