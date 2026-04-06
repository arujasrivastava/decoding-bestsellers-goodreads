# 📖 Decoding Bestsellers: What Makes a Book Succeed on Goodreads?

## Overview
Conducted an end-to-end data analysis of 8,100 Goodreads books 
using Excel Power Query and PivotTables to identify the quantitative 
drivers of reader satisfaction, including page count distribution, 
publisher tier performance, and community engagement patterns. 
Engineered five calculated columns — including a hidden gem index 
and a publisher classification framework — to surface non-obvious 
insights. Delivered findings through an interactive Excel dashboard 
with dynamic slicers and a dedicated insights sheet with 7 business 
takeaways.

## ❓ Business Questions
- Does reading more mean rating more generously?
- What is the sweet spot for book length?
- Do certain publishers consistently produce better rated books?
- What makes a hidden gem — high quality but low visibility?
- Has book quality (as rated by readers) changed across decades?

## 🔍 Key Findings
- **Hidden gems rate 0.40 points higher** than mainstream books 
  but receive 93% fewer ratings — high quality books are 
  systematically underdiscovered
- **Epic books (700+ pages) rate highest at 4.15** — readers 
  reward depth and ambition
- **Other publishers edge out major publishers** (3.951 vs 3.938) 
  — prestige does not predict quality
- **Books from the 1960s–80s rate consistently higher** — 
  survivorship bias means only the best old books remain popular
- **Elite books attract 8x more ratings** than average books — 
  quality and visibility are self-reinforcing

  ## 💼 Business Recommendations

- Promote high-performing titles to maximize engagement  
- Use niche Bookstagram influencers to boost hidden gems  
- Invest in long-form Fantasy & Historical Fiction content  

## 🛠️ Tools & Techniques
- Microsoft Excel — Power Query, PivotTables, calculated columns
- Power Query — data import, cleaning, conditional columns, 
  null handling, publisher classification using contains logic
- Excel formulas — IFS, IF, AND, OR for tier classification
- Dashboard design — KPI cards, interactive slicers, 
  dual-axis charts, dark theme UI
- Data storytelling — insight-first chart titles, 
  dedicated insights sheet

## 🧹 Data Cleaning Process
Raw dataset contained 11,000 rows with mixed languages, null 
publishers, and inconsistent formatting. Key cleaning decisions:
- Filtered to English-only books (language_code: eng/en-US/en-GB)
- Applied row filters: rating > 1, num_ratings > 50, pages > 0
- Created publisher_tier using "contains" logic to handle 
  variants (Penguin, Penguin Books, Penguin Classics → 
  all classified as Major Publisher)
- Replaced null publishers with "Unknown Publisher"
- Final dataset: 8,100 clean, analysis-ready records

## 📁 File Guide
| Sheet | Contents |
|---|---|
| Raw Data | Original unmodified source data |
| Clean_Data | Power Query output with 5 calculated columns |
| Analysis | 5 PivotTables with connected slicers |
| Dashboard | Interactive visual dashboard |
| Insights | 7 business findings with limitations noted |

## 🔮 Future Work
- Add genre column for genre-level analysis
- Add price data to analyse value vs quality relationship
- Build in Tableau for richer interactivity

## ⚠️ Limitations
- The hidden gems insight should be interpreted with caution — 
as rating count increases, average rating tends to decrease 
due to more diverse audience opinions. Higher ratings for 
low-count books may partly reflect limited sample size.
- Only books in english language were analysed. 

## 👤 About Me
I am a self-taught data analyst, economics post grad, and an avid fiction reader 
passionate about combining domain knowledge with data skills.


[LinkedIn](https://www.linkedin.com/in/aruja-srivastava-5197481b9/) · 
[Email](arujawork@gmail.com)

---
*Data source: Goodreads Books Dataset · Kaggle · 
Analysed in Microsoft Excel*
