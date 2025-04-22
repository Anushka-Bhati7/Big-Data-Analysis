# Big-Data-Analysis
COMPANY- CODTECH SOLUTION

NAME- ANUSHKA BHATI

INTERN ID- CT04DA489

DOMAIN- DATA ANALYTICS

DURATION- 4 WEEKS

MENTOR- NEELA SANTOSH
# NEW YORK CITY TAXI TRIPS DATA ANALYSIS USING PYSPARK
#OVERVIEW
The goal of this internship project is to perform scalable data analysis on a large dataset using PySpark, showcasing how distributed computing can be applied to real-world problems involving high-volume data. We focus on the New York City Taxi Trips dataset, which captures millions of transportation records per month, and derive insights related to ride behavior, cost metrics, and demand trends.
# Tools & Technologies Used
1. PySpark
      Core engine for distributed big data processing
      Enables handling of large datasets across clusters or multiple cores
      
2. NYC Yellow Taxi Dataset
       Real-world dataset with millions of taxi trip records
       Includes pickup/dropoff times, fare amounts, distances, etc.
       
3. Python
       Programming language used to write and execute PySpark scripts
       Widely used in data science and big data ecosystems
       
4. Jupyter Notebook / .py Script
       Used for interactive development and clean presentation of code
       Supports documentation, markdown, and result visualization
       
5. Pandas (optional)
       Used for local manipulation of small samples or summaries
        Allows easy conversion of Spark DataFrames for quick testing
        
6. Matplotlib / Seaborn (optional)
        Data visualization libraries
        Used for plotting trends like trip volume by hour or fare distribution 
# Dataset Description
* Source: NYC Taxi & Limousine Commission Open Data Portal

* Size: Millions of records per month

* Format: CSV

* Fields Include:

* Pickup and Dropoff Timestamps

* Trip Distance

* Passenger Count

* Fare Amount

* Pickup Hour (Derived)

* This dataset simulates real-time transportation data that is typically handled by ride-hailing and mobility companies such as Uber, Lyft, or Ola.
# Tasks Performed
1. Initialization
   Created a Spark session to handle distributed processing.
   Set configurations for optimized performance.
2. Data Ingestion
   Loaded CSV dataset with automatic schema inference using PySpark’s read.csv() function.
3. Data Cleaning
   Removed invalid entries such as:
   Negative/zero distance or fare amounts
   Trips with no passengers
4. Feature Engineering
   Extracted pickup hour from timestamp to analyze ride demand by time of day.
5. Aggregations
   Trips by Hour: Grouped data to identify peak travel hours.
   Average Fare per Mile: Created a custom metric for cost efficiency.
   Top Longest Trips: Identified high-distance (and potentially high-cost) rides.
6. (Optional) Visualization
   Converted Spark output to Pandas for small-scale visualizations like line graphs and histograms.
# Real-World Applications
* Transportation Forecasting: Predict high-demand hours to allocate resources efficiently.
  
* Dynamic Pricing: Use average fare/mile to improve fare models and customer fairness.
  
*  Urban Planning: Help cities design better infrastructure based on pickup/dropoff clusters.
  
* Anomaly Detection: Detect unusual trips, potential fraud, or system misreporting.
# Final Deliverables
* ✔️ Clean and documented PySpark script or Jupyter Notebook
  
* ✔️ Sample dataset (Excel/CSV for testing)
  
* ✔️ Summary of insights in markdown or PDF format

* ✔️ (Optional) Visualizations for added clarity
  
* ✔️ Ready for submission & certificate issuance



