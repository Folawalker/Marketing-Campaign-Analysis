# Marketing-Campaign-Analysis
An analysis to determine the effectiveness of different campaign types run by a company
# Table of Content
- Project Overview
- Dataset
- Data Inspection
- Data Cleaning
- Exploratory Data Analysis
  - Overview of the Data
    - Descriptive Statistics
    - Data Distribution
    - Check for Outlier
  - Comparative Analysis
    - Engagement Score vs Age Groups
    - Conversion Rate vs Age Group
    - Engagemet Score vs Channels
    - Conversion Rate vs Channels
    - CTR vs Channels
    - CPC vs Channels
  - ROI Analysis
    - Across Campaign Types
  - Location Based Trends
- Contributions

# Project Overview
The main purpose of this analysis is to help determine the most effective advertisement channels after the completion of a campaign. This is supposed to help make more effective targeted ads next time.

# Dataset
- `Campaign ID`: SN of the campaign
- `Company`: Company running the campaign/ad
- `Campaign Type`: Medium used for the campaign(Email, Influencer, etc..)
- `Target Audience`: Gender and age group of intended ad viewer
- `Duration`: Length of the campaign
- `Channel Used`: Platform used for the campaign(google ads, youtube, etc..)
- `Conversion Rate`: Pecentage of people who purchased an item directly from the ad
- `Acquisition Cost`: Cost of running the ad in USD
- `ROI`: Profit made from that specific transaction
- `Location`: geographical location of ad
- `Date`: Date of deployment
- `Clicks`: Number of times the ad was clicked on
- `Impressions`: Number of interactions the ad post got
- `Engagement Score`: Measures how actively people interact with the ad
- `Customer Segment`: Highlights the segment of customer/product
- `CTR`: Click Through Rate
- `CPC`: Cost Per Click

# Data Inspection
Data information was checked using `.info()` function on python and it helped confirm there were no missing values, also cnfirmed the datatypes, number of rows and columns.
I printed the top 5 rows plus header to check what the dataset looked like as well.

# Data Cleaning
The dataset had been cleaned from excel before importing to python

# Exploratory Data Analysis
## 1. Overview of the Data
- Descriptive Statistics: Used the `.describe()` function to check the basic statistical distribution of the dataset(mean, median, mode, max and min values, etc..)
- Data Distribution: Checked for unique target audience across the various channels
- Check for Outlier: Used the boxplot to check for outliers among the numerical data in the dataset
## 2. Comparative Analysis
- Engagement Score vs Age Groups: Checked the engagement score trend across age groups
- Conversion Rate vs Age Group: Examined the conversion rate across age groups
- Engagemet Score vs Channels: Analyzed the engagement score across various channels
- Conversion Rate vs Channels: Examined the conversion rate across various channels
- CTR vs Channels: Checked for the click through rate of various channels
- CPC vs Channels: Analyzed the cost per click across various channels
## 3. ROI Analysis
- Identifyimg underperforming and overperforming campaigns based on ROI
## 4. Location Based Trends
- Examined various trends and activities across the 5 locations in the dataset

# Contributons
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.
