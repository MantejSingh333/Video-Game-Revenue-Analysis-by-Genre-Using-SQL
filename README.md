# Video-Game-Revenue-Analysis-by-Genre-Using-SQL
SQL-based analysis identifying top-performing video game genres and revenue-driving titles using joins and window functions.

Video Game Revenue Analysis by Genre (SQL)
Project Overview

This project analyzes video game revenue data to identify which genres generate the highest revenue and to understand the key factors driving their success. Using SQL, I examined game revenue, descriptions, and review data to uncover patterns that inform strategic decisions related to marketing, monetization, and game design.

The analysis focuses on genre-level performance while preserving game-level detail to highlight standout titles that disproportionately influence overall revenue.

Objective

The goal of this analysis is to:

Identify the most lucrative video game genres

Determine which games drive the majority of genre revenue

Understand how engagement indicators (such as reviews) relate to revenue performance

These insights can help studios prioritize resources, refine monetization strategies, and guide future game development decisions.

Data & SQL Approach
Tables Used

games_revenue

games_description

games_reviews

Joining Method

An INNER JOIN was used to combine all tables using the shared primary key game_id, maintaining a one-to-one relationship across datasets.
Although alternative join types would yield identical results due to fully matched rows, the INNER JOIN was selected for clarity and simplicity.

SQL Techniques Used
Window Functions

The RANK() window function was used to rank games by total revenue within each genre, allowing:

Comparison of games against others in the same genre

Identification of high-impact titles that dominate revenue

This approach preserves game-level detail while enabling genre-level insights.

Key Insights
Genre-Level Revenue Distribution

Action games dominate the market, generating approximately 78% of total revenue

Other genres trail significantly:

Simulation: ~11%

Role-Playing: ~4.5%

Revenue Concentration Within Action Genre

A small number of games account for a large share of Action genre revenue:

Game	Share of Action Revenue
Counter-Strike	~32%
PUBG	~8%
Dota 2	~7.2%

These titles also rank highest in total reviews, indicating large and highly engaged player bases.

Key Success Drivers

The analysis suggests a strong relationship between player engagement and revenue:

Large player bases increase in-game purchase opportunities

Competitive multiplayer gameplay drives long-term engagement

Live service models (updates, seasons, events) significantly boost sustained revenue

These factors help explain the financial dominance of the Action genre.

Recommendations

Continue Prioritizing Action Games
Focus on competitive, replayable Action titles with strong multiplayer components.

Strengthen Monetization Strategies
Successful games leverage:

In-game purchases

Battle passes

Cosmetic items

Seasonal or subscription-style content

Explore Cross-Genre Innovation
Hybrid games combining Action with RPG or Survival elements can expand market appeal (e.g., PUBG).

Maintain Strategic Flexibility
Player preferences evolve rapidly; studios should continue experimenting with genres and monetization models.

Limitations

Skewed Revenue Distribution:
A small number of blockbuster titles heavily influence genre-level results.

Genre Classification Ambiguity:
Some games span multiple genres (e.g., Elden Ring classified as Action despite being marketed as an RPG), which may affect comparisons.

Conclusion

The analysis demonstrates that the Action genre is the most lucrative segment of the video game industry, driven primarily by a few highly successful competitive multiplayer titles. While other genres contribute meaningful revenue, they remain far less dominant.

Despite limitations, the findings provide actionable insights into revenue concentration, engagement-driven success, and strategic opportunities across genres.

Tools & Skills Demonstrated

SQL (JOINs, window functions, aggregation)

Analytical thinking & business insight

Revenue and performance analysis

Communicating insights and limitations clearly
