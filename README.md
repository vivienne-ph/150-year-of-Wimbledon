# 150-year-of-Wimbledon
# Project Overview
This project analyses nearly 150 years of Wimbledon Championship data to uncover long-term trends in match duration, win rates, and geographic patterns of success. The report places a particular focus on the small group of "top players" who have won the tournament five or more times to identify the patterns that distinguish them. 

## Dataset Details
* The dataset records every Wimbledon Championship final for Men's and Women's Singles.
* Data fields include the champion and runner-up names, nationality, tournament seed, final score, match duration in minutes, and per-set game counts.

## Tools & Data Transformation
* **Data Preparation:** Microsoft Excel.
* **Visualisation:** Tableau.
* **Key Calculations:** Several calculated fields were created, including Set Win Rate, Upset Flag, and Decade grouping. Min-max normalisation was also applied to Win Rate, Match Duration, and Seed to compare them accurately on a single parallel coordinates chart.
<img width="454" height="261" alt="image" src="https://github.com/user-attachments/assets/50ee06c0-6faf-48d3-8a4f-31ab974aaf8a" />
<img width="462" height="227" alt="image" src="https://github.com/user-attachments/assets/8175cc4a-29a5-4100-ab2d-f88d1716895b" />

## Visualisations & Key Findings
* **Geographic Distribution (Treemap & Geographic Map):** The United States and United Kingdom dominate both the champion and runner-up counts. Women's Singles shows a slightly wider geographic spread across Europe compared to Men's Singles.
<img width="1015" height="570" alt="image" src="https://github.com/user-attachments/assets/1cb03d93-45b3-40f9-b64b-3212998c0b53" />
<img width="1009" height="538" alt="image" src="https://github.com/user-attachments/assets/dd74d024-b1ca-4c8c-85e4-2261264ee573" />
* **Match Duration Trends (Line Chart):** Men's match duration has risen sharply from the 1960s onward, peaking near 200 minutes by 2020[cite: 2]. Women's duration has increased more gradually over the same period.
<img width="1010" height="517" alt="image" src="https://github.com/user-attachments/assets/03597e63-f789-457d-aeba-1d4b51c2932f" />
* **Win Rate vs. Match Duration (Scatter Chart):** The longer a match runs, the closer the champion's win rate converges toward a 50/50 split, indicating that longer matches tend to be closer, more evenly contested affairs.
<img width="1015" height="529" alt="image" src="https://github.com/user-attachments/assets/0f98ca1f-2c10-4022-8337-abea697ddc2a" />
* **Seed Comparisons & Upsets:** Since formal seeding began in 1927, higher-seeded finalists typically win, but there are notable upsets, including a 31st-seeded champion defeating a 7th-seeded runner-up.
<img width="1008" height="518" alt="image" src="https://github.com/user-attachments/assets/c54200ed-b101-4e04-8beb-edfa6d58d203" />
* **Top Players Analysis (5+ Titles):**
  * M. Navratilova leads the all-time list with 9 titles, followed by R. Federer and H.W. Moody (8 titles each).
<img width="1009" height="518" alt="image" src="https://github.com/user-attachments/assets/f12c9bf1-828b-4f9f-abfb-f14b28ebca67" />
  * Parallel coordinates analysis reveals that nearly all top players held the tournament's #1 seed, meaning sustained dominance is tied to entering as the clear favourite. N. Djokovic stands out as an outlier with an unusually high normalised average match duration compared to his peer.
<img width="1015" height="525" alt="image" src="https://github.com/user-attachments/assets/1883a83f-cd83-4842-a86a-2320a74c0e81" />
