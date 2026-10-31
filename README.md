# ☕ Starbucks Beverage Analysis | Power BI Dashboard
An interactive Power BI dashboard that explores Starbucks beverage nutrition
(calories, sugar, caffeine, protein) across beverage categories, alongside
the brand's global store footprint.

![Dashboard Preview](images/dashboard-preview.png)
## 📌 Project Overview
This project analyzes Starbucks beverage nutrition data to compare categories,
spot the highest-calorie and highest-caffeine drinks, and visualize where
Starbucks operates worldwide.

## 🎯 Objectives
- Compare average calories and caffeine across beverage categories
- Identify the beverages with the highest caffeine content
- Visualize Starbucks global store presence
- Let users filter drinks by protein range

## 📂 Datasets
| 'starbucks_data.csv' | Nutrition facts for 33 beverages across 9 categories and 13 prep options (242 rows) | 242 rows, 18 columns |
| 'directory.csv' | Starbucks store locations worldwide | 25,600 rows, 13 columns |

## 📊 Dashboard Features
| KPI cards | Total Beverages, Average Sugar, Average Calories, Average Caffeine |
| Protein range slicer | Filter all visuals by protein (g) |
| Area chart | Average calories by beverage category |
| Map | Starbucks global presence |
| Donut chart | Beverage category distribution |
| Bar chart | Average caffeine by category |
| Column chart | Top 5 highest-caffeine beverages |

## 🔍 Key Insights
- Smoothies have the highest average calories (about 282 kcal), followed closely by Frappuccino Blended Coffee (about 277 kcal).
- Brewed Coffee has the highest average caffeine (about 294 mg) with almost no calories, so it is the most efficient caffeine source.
- Frappuccino® Blended Crème drinks are caffeine-free but still average about 233 calories.
- The highest-calorie item is the White Chocolate Mocha (2% milk) at 510 calories.
- Starbucks has 25,600 store records across 73 countries, with the US alone accounting for about 53%.

## 🛠️ Tools & Skills
- Power BI Desktop
- DAX measures
- Data cleaning and modeling
- Dashboard design and storytelling

## 📁 Repository Structure

├── dashboard/   → Power BI file (.pbix)
├── data/        → Source datasets (CSV)
├── images/      → Dashboard screenshot
└── README.md


## ▶️ How to Open
1. Download 'dashboard/starbucks-analysis.pbix'
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the protein slicer and click any visual to cross-filter

## 👤 Author
Rishav Shaw
B-Tech computer Science & Engineering.
