# Udacity-project1
Repo for Udacity training project

# Motivation for the Analysis

The Seattle Airbnb Open Data provides a rich dataset that offers valuable insights into the short-term rental market in Seattle. Analysing this data will help us understand various aspects of the Airbnb trends, which can be beneficial for hosts and guests.

**Optimizing Pricing Strategies:**
By understanding the factors that influence pricing and identifying peak booking periods, hosts can optimize their pricing strategies to maximize revenue. This analysis can reveal seasonal trends and demand patterns, helping hosts adjust their prices accordingly.
Enhancing Customer Experience:

Analyzing customer reviews and identifying common themes can help hosts improve their listings and services. Understanding what guests value most can lead to higher satisfaction and better reviews, ultimately attracting more bookings.
Identifying Market Trends:

Tracking the number of new listings and total visitors over time can provide insights into market growth and saturation. This information is crucial for potential investors and existing hosts looking to expand their operations.

**Neighbourhood Insights:**
Examining how customer reviews vary across different neighbourhoods can highlight areas with high demand and guest satisfaction. This can guide hosts in choosing the best locations for new listings and help guests make informed decisions about where to stay.

**Operational Efficiency:**
Understanding booking patterns and occupancy rates can help hosts manage their properties more efficiently. This includes optimizing availability, managing maintenance schedules, and planning for peak periods.

However, the analysis aimed looked at the following questions: 
1. What are the busiest times of the year for Airbnb bookings in Seattle?
2. How do customer reviews vary across different neighbourhoods in Seattle?
3. How does pricing fluctuate across the different Top30 neighbourhoods during this period of time?

# Libraries used and why:

**1.pandas;**


**Function:**
pandas is a powerful data manipulation and analysis library. It provides data structures like DataFrames, which are essential for handling and analyzing structured data.

**Usage in Analysis:**
Loading data from CSV files.
Handling missing data.
Performing data transformations and aggregations.

**2. matplotlib.pyplot;**


**Function:** 
matplotlib is a plotting library used for creating static, interactive, and animated visualizations in Python.
**Usage in Analysis:**
Creating various types of plots (e.g., bar plots, line plots, histograms) to visualize data trends and distributions.
Customizing plot aesthetics (e.g., titles, labels, colours).

**3. seaborn;**

   
**Function:**
seaborn is a statistical data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
**Usage in Analysis:**
Creating more complex and aesthetically pleasing visualizations (e.g., count plots, bar plots, histograms with KDE).
Enhancing the readability and interpretability of plots with built-in themes and colour palettes.

These libraries together provide a comprehensive toolkit for performing data analysis and visualization, helping to uncover insights and trends.

# Files in the Repository


**listings.csv:**
In this file, you'll find detailed information about each Airbnb listing in Seattle. This includes attributes such as the listing ID, host ID, neighbourhood, property type, room type, price, minimum nights, number of reviews, and various other features related to the listing and the host.

**calendar.csv:**
This file provides daily availability and pricing information for each listing. It includes columns for the listing ID, date, availability status, and price.

**reviews.csv:**
In this CSV there are reviews left by guests for each listing. It includes the review ID, listing ID, date of the review, reviewer ID, reviewer name, and the review comments.
