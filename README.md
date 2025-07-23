🎬 Netflix Movie Data Analysis

A deep dive into Netflix’s movie collection using Python, exploring trends in genre, popularity, ratings, and release patterns.

🔍 Key Insights

1. Most frequent genre :
   **Drama** dominates Netflix’s movie catalog by volume.

2. Most popular movie :
   Spider-Man : No Way Home

3. Least popular movie :
   The United States vs Billie Hoilday

4. Year with the most releases :
   **2019** saw the highest number of Netflix movie premieres.


🛠️ Exploratory Data Analysis (EDA) Workflow

1. Load & Clean Data
   - Imported datasets (CSV/JSON).
   - Parsed release dates, handled missing/null values in important fields.
   - Removed duplicates and standardized columns.

2. Feature Engineering
   - Extracted `release_year` from the release date.
   - Expanded multi-genre fields (e.g., `"Drama|Thriller"`) into separate categorized rows.

3. Descriptive Statistics & Visualizations
   - Plotted histograms and boxplots to inspect distributions for popularity and vote averages.
   - Generated count frequencies for genre and release year via bar charts.

4. Aggregation & Ranking
   - Used `groupby()` and aggregation to find the top vote average and popularity records.
   - Identified the most common genre and busiest release year.

5. Visual Storytelling
   - Genre breakdown chart— highlights Drama dominance.
   - Release trend line chart— tracks growth with a peak in 2019.
   - Scatter plot of Popularity vs. Vote Avg — annotated with top and bottom performers.


📊 Sample Visualizations

Genre Distribution (Bar Chart) 
*Example: Bar chart showing count of movies per genre.*

Popularity vs. Vote Avg (Scatter Plot) 
*Scatter plot highlighting top & bottom performers by popularity and votes.*

🧪 Tech Stack

- Python 
- pandas, numpy 
- seaborn, matplotlib 

 Dataset: Netflix movie metadata CSV


📂 How to Run

1. Clone this repository  
   bash
   git clone https://github.com/username/netflix-movie-analysis.git
   cd netflix-movie-analysis


2. Install dependencies

   bash
   pip install -r requirements.txt
   

3. Run the analysis script / Jupyter notebook

   bash
   python analyze.py
   or
   jupyter notebook analysis.ipynb

4. View outputs:

   * `.csv` results in `output/`
   * Charts in `figures/`
   * Full Jupyter notebook for interactive exploration.
