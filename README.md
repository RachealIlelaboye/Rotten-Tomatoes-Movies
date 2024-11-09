# Rotten-Tomatoes-Movies
This repository documents the full workflow of a  data analysis project, including data cleaning, exploratory data analysis, and visualizations for business decision-making. 

## Goals and Insights
- Uncover trends: Identify high-performing studios, and movies.
- Analyze ratings distribution
- Drive Data-Driven Decisions: Offer actionable insights and recommendations to improve ratings.

## Data Source
Microsoft Excel Comma Separated Values File (.csv) from TriInspire Tech Ltd [LinkedIn](https://ng.linkedin.com/company/tri-inspire-tech-ltd)

## Tools 
- Power BI
  - Data Cleaning and transformation
  - For data visualization
  - Reporting.
- Github
  - Portfolio building.

## Data Cleaning
This project utilizes Power BI's Power Query Editor for essential data preparation tasks. The primary goals are:
1. Cleaning data to remove duplicates and handle missing values.
2. Ensuring data consistency by setting appropriate data types.
3. Transforming the data to align with analysis and reporting requirements.

### 1. Loading Data into Power Query
- **Import Data**: Load data from CSV using **Get Data**.
- **Access Power Query**: Open **Transform Data** to access Power Query Editor, where cleaning and transformation is applied.

### 2. Data Cleaning

- **Removed Duplicates**: Removed Duplicates under the **Home** tab to ensure data uniqueness.

- **Replaced Missing Values**: 
  - Used **Replace Values** in the **Transform** tab to fill or replace nulls with NA.
  - Select **Fill Down** for filling blanks.

- **Ensure Data Type Consistency**: 
  - Assigned each column a correct data type (e.g., text, whole number, date) by selecting the data type icon in the column header.

- **Trim and Clean Text**: 
  - Remove extra spaces or non-printable characters using **Trim** or **Clean** from the **Transform** tab.

### 3. Data Transformation

- **Filter Rows**: 
  - Removed specific values.

### 4. Finalizing Data for Analysis

- **Apply and Load**: After completing data cleaning and transformation, click **Close & Apply** to load the processed data into Power BI for visualization and analysis.


## Data Visualizations 
![ROtten Tomatoes a](https://github.com/user-attachments/assets/ad6fd260-11c2-4486-883d-d27a2be08819)
![ROtten Tomatoes b](https://github.com/user-attachments/assets/71e95b45-09e1-40e3-abb9-9501921347f3)

## Insights and Findings

**Key Metrics**
- Total Movies Analyzed: 16,090
- Genres Covered: 1,080
- Directors: 8,320
- Writers: 12,120
- Total Studios Analyzed: 2,890 studios contributed to the analyzed movie dataset.
- Average Runtime: Displays the typical runtime for movies in minutes, helping to identify trends in movie length.

**Findings**
- **Rating Distribution**
 - Most Common Rating: R (Restricted), followed by NR (Not Rated), PG-13, and PG.
 - Movies with Certified Fresh Status: Around 2,960 movies achieved the "Certified Fresh" status, while "Fresh" movies numbered 6,450 and "Rotten" movies totaled 7,230.
   
- **Popular Genres**
  - Top Genres by Movie Count: Drama is the leading genre by number of movies, followed by Comedy, Documentary, and Horror.
  - Top Genres by Audience Count: The audience shows a preference for Comedy, Drama, Action & Adventure, and Horror.
  - Audience Rating Distribution: Ratings are skewed towards "PG-13" and "R," indicating a high prevalence of movies aimed at older audiences.
  - Genre by Rating Analysis: The rating analysis across genres shows that Drama and Comedy are consistently high-rated by audiences.
    
- **Studio Performance**
  - Top 10 Studios by Movie Count: Paramount Pictures, Universal Pictures, Warner Bros., Sony Pictures, and others are the leading studios by number of movies produced.
- Genre Focus by Studios: Different studios have distinct genre focuses, with some specializing more in drama and comedy while others lean towards action and adventure.
- Top Movies by Tomatometer Rating
  Popular movies with high ratings include "Hamlet," "A Star is Born," "Little Women," and "The Pride and the Prejudice." These movies demonstrate strong positive reception based on Tomatometer ratings.

- **Genre Insights Based on Tomatometer Rating**
  - High-Rated Genres: Drama and Comedy show strong performance, as many movies in these genres hold high ratings.
  - Niche Genres: Art House, Documentary, and Action & Adventure genres are also well-represented among high-rated movies.
  
- **Top Movies and Audience Ratings**
  - Top 10 Movies by Audience Rating: High-rated movies include "Home," "Little Women," "A Star is Born," and "An Inconvenient Truth." These movies reflect strong audience engagement and satisfaction.
  - Top Movies by Tomatometer Count: Frequently rated movies include popular titles like "A Star is Born," "Halloween," "The Lion King," and "Captain Marvel," indicating these titles have had substantial critical review and visibility.
  
- **Genre and Audience Preferences**
  - Top Genres by Audience Rating: Drama, Comedy, and Documentary genres have the highest audience ratings, showcasing their popularity and resonance with viewers.
  - Top 7 Genres by Audience Count: Drama and Comedy dominate the audience count, followed by niche genres like Art House, Documentary, and Mystery, revealing broad preferences and potential areas for growth.

- **Studio Performance**
  - Top Studios by Audience Rating and Count: Leading studios like Universal Pictures, Warner Bros., and Paramount have the highest audience ratings and counts. This indicates that well-established studios continue to attract significant viewership and maintain audience satisfaction.
  - Popular Movies by Studio: Major box-office hits like "Titanic," "The Lord of the Rings," "Spider-Man," and "Shrek 2" are associated with these top studios, suggesting a correlation between studio reputation and movie success.

## Conclusion
The data highlights the significant influence of Drama and Comedy genres on audience ratings and viewership. Major studios like paramount pictures and Universal play a pivotal role in producing popular, high-rated movies, while top-rated movies attract substantial critical attention and audience ratings. Additionally, audience preferences lean towards longer runtimes for high-engagement movies.Ratings distribution indicates a mix of "Rotten" and "Fresh" movies, showing diverse audience reception across genres and studios.

## Recommendations
- For Studios: Invest in producing Drama and Comedy films to leverage high audience engagement and ratings.
- For Filmmakers: Focus on building critical acclaim through quality storytelling in high-engagement genres like Drama and Documentary.
- For Marketers: Highlight high audience ratings and established studios' involvement to enhance movie appeal among viewers.
