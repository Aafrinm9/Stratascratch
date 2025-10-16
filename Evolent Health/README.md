# 🍺 Beer Data Science Project

## 📘 Assignment Overview
In this assignment, you will analyze a beer dataset and answer the following questions. Use data analysis, visualization, and statistical reasoning to support your findings.

### Questions
1. Rank the **top 3 breweries** that produce the strongest beers.  
2. Identify **which year** beers received the **highest ratings**.  
3. Based on user ratings, determine which factors are most important among **taste, aroma, appearance, and palette**.  
4. Recommend **3 beers** to your friends based on the data.  
5. Find which **beer style** is the favorite among users. Compare **written reviews** with the **overall review score** for that beer style.

---

## 🧾 Data Description
The dataset (`BeerDataScienceProject.tar.bz2`) contains detailed information about beers and their reviews.  
Below are the columns available:

| Column Name | Description |
|--------------|-------------|
| `beer_ABV` | Alcohol by volume (%) |
| `beer_beerId` | Beer ID |
| `beer_brewerId` | Brewer ID |
| `beer_name` | Name of the beer |
| `beer_style` | Style or category of the beer |
| `review_appearance` | Rating of beer’s appearance |
| `review_palette` | Rating of beer’s palette (colors) |
| `review_overall` | Overall rating |
| `review_taste` | Rating of beer’s taste |
| `review_profileName` | Reviewer's username |
| `review_aroma` | Rating of beer’s aroma |
| `review_text` | Full text of the review |
| `review_time` | Timestamp of the review |

---

## 💡 Hint
The `.tar.bz2` file is a compressed CSV. You can load it into a Pandas DataFrame using:

```python
import pandas as pd

df = pd.read_csv("BeerDataScienceProject.tar.bz2", compression="bz2")

---

## 📩 Data Access
Due to file size limits, the dataset is not included in this repository.  
If you need access to the data, feel free to email me.
