**📊 Netflix Data Analysis Dashboard (Power BI)**

> 📌 Power BI dashboard project analyzing Netflix data to identify trends in content production, ratings, and audience behavior.






## 🔍 Project Overview
    This project analyzes a Netflix dataset to understand how content trends, audience engagement, and ratings have evolved over time.

## 🎯 Objective
The objective of this project is to explore how Netflix content has evolved over time and to identify patterns in ratings, audience engagement, and content distribution using Power BI.

## 📁 Dataset Information
    The dataset consists of approximately 5283 records, including both movies and TV shows.

    Key Columns:
        - id – Unique identifier for each title
        - title – Name of the movie or TV show
        - type – Movie / TV Show
        - release_year – Year of release (1953–2022)
        - age_certification – Audience rating category (partially missing)
        - runtime – Duration in minutes
        - imdb_score – IMDb rating
        - imdb_votes – Number of votes received


## ⚙️ Data Processing & Transformation

          - Created a custom metric: “Rating Votes”
            → "imdb_score × imdb_votes"
            → Used to evaluate overall popularity and impact
          - Handled missing values in age certification by retaining available data
          - Performed aggregations such as averages and counts for analysis


## 🎯 Key Business Questions Answered

            1. Which are the top-performing movies and TV shows overall?
            2. How has content production changed over time?
            3. How has IMDb rating trended over the years?
            4. Has audience engagement (votes) increased over time?
            5. How has runtime evolved over the years?
            6. How does age certification impact ratings?


## 📈 Key Insights

🏆 Top Performing Titles

      - Using the custom “Rating Votes” metric:
      - Inception leads with ~20M rating votes
      - Forrest Gump follows with ~18M
      - Breaking Bad ranks third (~16M)
      - Other top titles include Django Unchained and Saving Private Ryan


📊 Content Growth Trend

      - Content production has grown significantly in recent years, with a sharp rise after 2010
      - Peak observed around 2019 (~749 titles)
      - Minimal releases in early decades (1950s–1970s)
        Indicates strong recent expansion in content creation


⭐ IMDb Score Trend

      - IMDb ratings are less stable when the number of votes is low, but become more consistent as audience participation increases.
      - As the number of voters increases, ratings become more stable
        Suggests reliability of ratings improves with higher audience participation


👥 Audience Engagement (Votes)

        - Continuous increase in voting activity over time
        - Peak engagement observed around 2017 (~68M votes)
          Reflects growing audience interaction and platform reach


⏱ Runtime Trend

        - Average runtime has decreased over time
          - ~163 minutes (1960s)
          - ~86 minutes (recent years)
            Indicates shift towards shorter, more consumable content


👉Age Certification vs Ratings

        - TV Shows tend to receive higher ratings compared to movies
        - Audience engagement appears stronger for TV content
           Suggests evolving viewer preference toward series-based content



## 🛠 Tools & Technologies

        - Power BI – Data visualization and dashboard creation
        - Excel / Dataset Source – Data handling

---

## 📸 Dashboard Preview
        
        "NETFLIX DASHBOARD.png" - Power BI project Dashboard



## 📂 Project Files

- "Netflix DATA.pbix" – Power BI project file



## Conclusion

This project demonstrates the ability to:

- Perform data exploration and transformation
- Build meaningful KPIs and custom metrics
- Analyze trends and extract actionable insights
- Present findings through an interactive dashboard
This project reflects my ability to not only build dashboards, but also to interpret data and derive meaningful insights from it.


👤 Author
    LAYASRI

---
