# Decades of Storytelling - IMDB Data Visualized (Power BI)

## Project Objective
To Visualize decades of IMDB data in Power BI to reveal audience trends and content insights. 

## Dashboard components (KPIs)
1. Trend of IMDB voting: Sum of IMDB votes/scores over time to capture engagement momentum and peaks by year.
2. Trend of release: Count of titles released per year to visualize industry output and saturation periods.
3. Top movies & TV shows: Ranked list by popularity or average IMDB score (e.g., Inception, Forrest Gump, Breaking Bad).
4. Trend of runtime: Average runtime by year to observe format shifts and pacing trends.
5. Age certification vs ratings: Average IMDB score by certification (TV‑14, TV‑MA, etc.) to infer audience maturity preferences.
6. Year‑wise IMDB scores: Average IMDB score per year across decades to reveal rating cycles and standout eras.

- Dashboard Interaction -> <a href="https://github.com/FaisalManiyar/Decades-of-Storytelling-IMDB-Data-Visualized-in-Power-BI/commit/c1b34c7f200e58142a77236617641a33f2759fd4">View Dashboard<a/>

Process workflow
1. Data ingestion
2. Data cleaning
3. Modeling:
- Calendar table: Create a Year dimension linked to ReleaseYear.
- Relationships: Titles (fact) → Year (dim).
- Measures: DAX for averages, sums, top‑N rankings.
4. Visualization

## Dasboard
<img width="1463" height="749" alt="IMDB_PBI" src="https://github.com/user-attachments/assets/009ea28e-2d70-4235-b531-27a4500325cf" />

## Key insights
- Engagement momentum rose around the 2000s: Both votes and release counts show a notable upswing, suggesting increased audience activity and content output.
- Top titles cluster in modern eras: High‑ranking titles (e.g., Inception, Forrest Gump, Breaking Bad) reflect strong performance in late 90s–2010s periods.
- Runtime trends shift post‑2000: Average runtime fluctuates with a general decline after 2000, hinting at format optimization and pacing for streaming audiences.
- Mature certifications rate higher: TV‑14 and TV‑MA show stronger average scores, indicating a tilt toward complex, mature storytelling preferences.

## Final conclusion
This dashboard translates a complex entertainment dataset into clear, actionable narratives: engagement and content output surged in the 2000s, mature certifications consistently earn higher ratings, and runtimes have been refined to fit modern consumption. For content strategy, prioritize TV‑14/TV‑MA programming with strong narrative depth, calibrate runtimes to audience tolerance, and leverage high‑performing modern titles for recommendation engines. The framework is modular, reproducible, and ready to scale with broader IMDB data—making it a solid portfolio piece and a practical analytics asset.




