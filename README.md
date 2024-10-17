# British_Airways_Reviews_PROJECT_with-ADVANCED_PARAMETERS

The British Airways Reviews Project aims to create an interactive dashboard using Tableau to visualize customer reviews of the airline. This dashboard offers users the ability to filter and analyze various metrics, including overall ratings, food quality, and entertainment features, making it a user-friendly tool for exploring the data.
T
he project utilizes two primary data sources: a CSV file containing detailed reviews, labeled "ba_reviews.csv," which offers insights into various aspects of the airline experience such as seat comfort, cabin staff service, and value for money, and another file, "countries.csv," that provides geographical context.

Data preparation involved connecting these CSV files in Tableau and establishing a relationship between the location information in the reviews and the country data to enable geographical analysis. The dashboard is designed for high interactivity, allowing users to toggle between different metrics and filter data based on parameters like timeline, seat type, traveler type, and continent.

Key features of the dashboard include a geographical map that visualizes data dynamically based on selected metrics, enhanced tooltips that offer additional information, and summary metrics displayed in a text table. Users can also see trends over time with a continuous month timeline and a double bar chart showcasing average metrics alongside the number of reviews for different aircraft groups.

The construction of the dashboard employs a floating layout for better spacing and alignment, with essential elements such as the title "British Airways Review," summary metrics, and interactive filters organized to facilitate a seamless user experience. Overall, this project promises an insightful and engaging way for users to explore British Airways reviews.



British Airways Reviews Project (with Advanced Parameters)

Project Overview: This project involves creating an interactive dashboard using Tableau to visualize British Airways reviews. The dashboard allows users to dynamically   
     filter and explore various metrics such as overall ratings, food ratings, entertainment ratings, and more. The goal is to provide an intuitive and interactive 
     experience for users to analyze the data based on their specific interests.

Data Source: The dataset consists of two CSV files:
    1.	ba_reviews.csv: Contains detailed reviews of British Airways, including metrics like rating, seat comfort, cabin staff service, food and beverages, ground service, 
        value for money, and entertainment.
    2.	countries.csv: Contains country information to enable geographical analysis.

Data Preparation:
    1.	Connecting to Data: Both CSV files were connected to Tableau. The ba_reviews table contains review details, while the countries table includes country information.
    2.	Editing Relationships: A relationship was established between the place field in the ba_reviews table and the country field in the countries table to enable   
        geographical filtering.

Dashboard Blueprint: The dashboard is designed to be highly interactive, allowing users to:
    •	Toggle between different metrics (overall rating, cabin staff service, entertainment, food, ground service, seat comfort, value for money).
    •	Filter data by timeline, seat type, traveler type, aircraft type, and continent.
    •	Use visual elements like maps, line charts, and bar charts as dynamic filters.

Key Features:
1.	Map Chart:
    o	Geographical Data: The place column was converted to a geographic location datatype.
    o	Dynamic Metrics: A parameter named “Pick a Metric” was created to allow users to toggle between different metrics. A calculated field was used to apply the selected 
      metric to the map.
    o	Interactive Title: The map title dynamically updates based on the selected metric.
2.	Filters:
    o	Month Filter: Allows users to filter data by month. The filter is applied to all worksheets using the data source.
    o	Seat Type and Traveler Type Filters: These filters are applied to all worksheets and allow users to filter data based on seat type and traveler type.
    o	Aircraft Type Filter: Aircraft types with fewer than 50 reviews were grouped into an “Other” category to simplify the filter options.
    o	Continent Filter: Allows users to filter data by continent.
3.	Tooltips:
    o	Enhanced Tooltips: Tooltips were customized to show additional metrics, such as the number of reviews from each country.
4.	Summary Metrics:
    o	Text Table: Summary metrics for overall rating, cabin staff service, entertainment, food and beverages, ground service, seat comfort, and value for money were 
      displayed using a text table.
5.	Line Chart – Timeline:
    o	Continuous Month: The date field was used to create a continuous month timeline. The selected metric was displayed over time.
6.	Double Bar Chart:
    o	Aircraft Group: The bar chart displays the average selected metric and the count of reviews for each aircraft group.

Dashboard Construction:
    1.	Floating Layout: A floating layout was used for the dashboard to manage spacing and alignment.
    2.	Dashboard Elements: 
        o	Title: The dashboard title “British Airways Review” was added.
        o	Summary Metrics: Placed at the top of the dashboard.
        o	Map and Filters: The map and associated filters were added using a vertical container.
        o	Charts: The timeline chart and aircraft group chart were added, with tooltips customized to show the number of reviews and average metrics.

Interactivity:
    •	Filter Actions: Each visual element (map, line chart, bar chart) can be used as a filter. For example, clicking on a specific country on the map filters the data to   
      show reviews from that country.
    •	Dynamic Updates: The dashboard elements update dynamically based on the selected filters and parameters, providing a seamless and interactive user experience.

Conclusion: This Tableau project demonstrates advanced data visualization techniques, including dynamic parameters, interactive filters, and customized tooltips. The resulting dashboard provides a comprehensive and user-friendly interface for exploring British Airways reviews, making it a valuable addition to any data analyst’s portfolio.
