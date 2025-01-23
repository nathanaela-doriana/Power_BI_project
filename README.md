# Insights about Airbnb France 

## Project Description
This project analyzes Airbnb data to provide detailed insights into accommodation trends, pricing strategies, host characteristics, and traveler priorities in France. By leveraging this dashboard, both new and experienced Airbnb hosts can optimize their offerings to align with market demands, while travelers can gain a better understanding of regional trends and prioritize their preferences.

## Steps of the Analysis

1. **Data Collection (Scraping)**:
   - Used **web scraping techniques** to extract detailed Airbnb data, including:
     - Accommodation types, addresses, prices, ratings, cancellation policies, host experience levels, and traveler reviews.
   - Geographical data such as regions were derived using geocoding techniques with libraries like `geopy`.

2. **Data Cleaning**:
   - Ensured the dataset was clean and consistent:
     - Removed duplicates and null values.
     - Standardized column names and data types for ease of analysis.
     - Created new variables like **host categories** (based on experience) and **accommodation categories**.

3. **Feature Engineering**:
   - Created additional variables, including:
     - **Average price per traveler** to compare pricing fairness.
     - **Family-friendly categories** based on the number of travelers an accommodation can host.

4. **Keyword Analysis**:
   - Extracted and analyzed traveler reviews to identify key priorities such as comfort, cleanliness, and scenic views.
   - Grouped keywords to highlight regional and accommodation-specific trends.

5. **Dashboard Creation in Power BI**:
   - Designed an interactive dashboard to explore:
     - Regional trends in pricing and capacities.
     - Popular accommodation types.
     - Traveler priorities and pricing analysis.
     - The impact of free cancellation on pricing and visibility.

## Key Features of the Dashboard

1. **Regional Pricing Distribution**:
   - Visualizes the average price per night in different regions of France.
   - Highlights regions with the highest and lowest prices, aiding hosts and travelers in understanding regional pricing disparities.

2. **Host Capacity Analysis**:
   - Illustrates the maximum number of travelers accommodated across regions.
   - Regions are color-coded based on their host capacities, helping identify areas with larger or smaller accommodations.

3. **Most Common Accommodation Types**:
   - Displays the top 10 most common types of accommodations in France.
   - Helps hosts and travelers identify popular accommodation styles.

4. **Host Experience vs. Pricing**:
   - Investigates how host experience influences pricing per night.
   - Categorizes hosts into beginner, intermediate, and expert levels to understand their pricing strategies.

5. **Accommodation-Specific Insights**:
   - Provides detailed analysis for selected accommodation types, including:
     - Average price per night.
     - Average traveler capacity.
     - Regional distribution and keywords reflecting traveler priorities for specific accommodations.

6. **Pricing Analysis**:
   - Compares average prices and traveler capacities for different accommodation types.
   - Identifies the most family-friendly or group-friendly accommodation types.

7. **Keyword Analysis**:
   - Explores traveler preferences based on keywords extracted from reviews.
   - Reveals regional and accommodation-specific priorities like comfort, cleanliness, and views.

8. **Impact of Free Cancellation**:
   - Analyzes the relationship between free cancellation options and pricing.
   - Helps hosts assess whether offering free cancellation aligns with market expectations and increases visibility.


## How This Dashboard Adds Value

- **For Hosts**: Assists in tailoring their listings to better suit regional demands, pricing competitively, and highlighting features that matter most to travelers.
- **For Travelers**: Offers a clear view of the most popular and cost-effective accommodations based on their priorities and preferred regions.
  

## Repository Structure

📁 **notebooks/**  
&nbsp;&nbsp; ├── **Airbnb Part 1 - scraping.ipynb**: Scrapes data from Airbnb listings.  
&nbsp;&nbsp; ├── **Airbnb Part 2 - cleaning.ipynb**: Cleans and preprocesses the scraped data.  
&nbsp;&nbsp; └── **Airbnb Part 3 - comments analysis.ipynb**: Performs keyword analysis on guest comments.

📁 **data/**  
&nbsp;&nbsp; └── **Final Dataset for PowerBI.csv**: Cleaned and enriched dataset for analysis.

📄 **README.md**: Overview of the project.  
📄 **PowerBI Dashboard**: Visual representation of insights.



## How to Reproduce the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Ousow/Power_BI_project.git
   cd Power_BI_project

## Team Members
- Francesca Vasta
- Nathanaëla Razafindrakoto
- Oumou Sow
