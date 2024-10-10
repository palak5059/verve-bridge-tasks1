# verve-bridge-tasks1

NBA Draft Combine Measurements (Data Analytics)

dataset source - https://www.kaggle.com/datasets/thedevastator/nba-draft-combine-measurement-data-from-2012-201?select=nba_draft_combine_all_years.csv

Analyzing the NBA draft combine data to understand the relationship between player measurements and their success in the draft. 

    Data Collection: The dataset was obtained from a web-based platform and community for data science and machine learning practitioners. the dataset consisted measurements from 
    multiple NBA draft combines, including player height, weight, vertical jump, and other relevant metrics.
    Data Cleaning: The dataset was cleaned by removing rows with missing values to ensure accurate analysis. Key features such as height, weight, vertical jump, and draft pick position 
    were retained for analysis.
    Descriptive Analysis: Key statistics were summarized to provide insights into the physical attributes of players. Trends and outliers were identified to understand variations among 
    players.
    Correlation Analysis: Correlations between different measurements and draft pick positions were examined using Pearson correlation coefficients to determine significant relationships.
    Predictive Modeling: Linear regression models were developed to forecast player success based on their combine measurements.
    Visualization: Various visualizations were created to present insights and patterns in the data effectively.


Findings:

    Average Measurements:
       - Height (No Shoes): Approximately 78.2 inches
       - Weight: Around 217.5 pounds
       - Vertical Jump (Max): About 33.7 inches
       - Bench Press: Average of 10.5 repetitions
       - Agility Drill Time: Approximately 11.1 seconds

    Trends: There is a noticeable increase in vertical jump heights over the years, indicating a shift towards more athletic players.
    Outliers: Notable outliers include Hasheem Thabeet (height of      85.25 inches) and DeJuan Blair (weight of 277 pounds), which may influence team evaluations.
    Correlation Analysis:
    •	Player Success (Draft Pick):
    o	Negative correlations (indicating better draft position is linked to higher performance):
    	Vertical Jump (Max): Players with higher vertical jumps tend to be drafted higher (-0.35).
    	Sprint Time: Faster sprint times show a mild correlation with a better draft pick (-0.17).
    o	Positive correlations (indicating worse draft position):
    	Body Fat: Higher body fat percentages are weakly associated with lower draft picks (0.19), implying fitter players may be drafted earlier.
    •	Player Height and Wingspan: There is a strong positive correlation between height and wingspan (0.87). Taller players generally have longer wingspans.
    •	Weight and Vertical Jump: Heavier players tend to have lower vertical jumps, with a negative correlation of -0.58.

    A linear regression model was developed using key features to predict draft pick positions, achieving an R² score of approximately 0.92, meaning about 92% of the variance in draft 
    positions (a higher value indicates better performance). 



Key Insights an conclusion:

    Athleticism Matters: Players with higher vertical jumps tend to be selected earlier in the draft, emphasizing the importance of athletic performance in player evaluations.
    Height Advantage: Taller players generally have better chances of being drafted higher, which aligns with traditional scouting practices that favor size.
    Weight Considerations: While weight can be an asset, excessively heavy players may face challenges during the selection process.
    Height and Wingspan are strongly correlated, but height alone does not strongly predict draft success.

Results:

    The regression model achieved an R² score of approximately 0.92, meaning about 92% of the variance in draft pick positions.  This indicates the players have better success rate as 
    for 
    the better performance from the players in regards to their combine measurements.



