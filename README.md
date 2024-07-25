# SQL_PYTHON: USER ENGAGEMENT ANALYSIS FOR RESTAURANT SUCCESS 

<br />

## PROJECT OVERVIEW
Yelp is an online directory for finding local businesses, including restaurants, cafes, spas and other services, with a strong social component that encourages users to leave written reviews, star ratings, and photos of their experiences.
In the competitive restaurant industry, understanding the key factors that drive business success is crucial for stakeholders. This project examines how user engagement (reviews, tips, and check-ins) impacts business success metrics (review counts and ratings) in the restaurant industry using the Yelp dataset. The goal is to provide insights for restaurant owners and managers to improve their strategies for attracting and retaining customers.

**Research Objectives**
- Determine the Correlation of user engagement with reviews and ratings.
- Investigate the impact of sentiment on reviews and ratings.
- Explore time trends in engagement.

**Dataset Information**
-	This dataset, a subset of Yelp's data, contains information about businesses in eight metropolitan areas across the USA and Canada. 
-	The original data, provided by Yelp, is available in five JSON files: business, review, user, tip, and check in, stored in a database for convenient data retrieval.
-	The dataset is directly available for download from either [Yelp Dataset](https://www.yelp.com/dataset) or [Kaggle](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset). 

<br />

## STEPS
<br />

### Database Creation
<br />

**1. Importing Libraries**
- Imported libraries to read and process JSON files into Pandas DataFrames for efficient analysis and manipulation.
<br />

**2. Loading JSON Files into Dataframes**
- Loaded data from five Yelp JSON files into Pandas DataFrames for efficient manipulation and analysis.
- Converted each JSON file line-by-line into dictionaries, which are then used to create Pandas DataFrames.
<br />

**3. Establishing Database Connection**
- Connected to a SQLite database named yelp.db using SQLAlchemy, efficiently transferring DataFrames into SQLite tables.
- Loaded each of the five DataFrames into SQLite as separate tables, organizing the Yelp dataset for easy querying and analysis.
<br />

### Analysis and Findings
<br />

**1. Importing Libraries**
- Imported libraries, facilitating data exploration, manipulation, and visualization in Python, ideal for analytical tasks.
<br />

**2. Database Connection**
- Connected to yelp.db SQLite database, retrieves and displays the names of all tables.
<br />

**3. Displaying Table Data**
- Loaded table data into Pandas DataFrames for quick previews.
- Includes five tables: Business, Review, User, Tip, Checkin.
<br />

**4. Data Analysis and Visualisation**

Created visualizations to address the following research questions: 
- Analysis of Open Restaurant Businesses Among Total Businesses.
- Analysing the relationship between review_count and rating.
- Analysing the relationship between restaurant engagement and ratings.
- Examining the Relationship Between Reviews, Tips, and Check-Ins for Businesses
- Comparing User Engagement (Reviews, Tips, and Check-Ins) Between High-Rated and Low-Rated Businesses.
- Analysing User Engagement Patterns Over Time for Successful vs. Less Successful Businesses.
- Identifying Seasonal Trends in User Engagement for Restaurants.
- Correlating Sentiment of Reviews and Tips with Restaurant Success Metrics.
- Comparing Engagement Levels Between Elite and Non-Elite Users.
- Identifying the Busiest Hours for Restaurants.
<br />

**5. Data Interpretation**
- Analyze Metrics.
- Customer Focus.
- Optimize Operations.
- Boost Visibility.
- Collaborate with Elites.
- Capitalize on Demand.
- Improve Engagement.
- Expand Opportunities.
---
<br />

Please check out the **[Full Report]()** for Further Explanation!<br />
\
Your Thoughts and Feedback are highly appreciated! :smile:<br />
