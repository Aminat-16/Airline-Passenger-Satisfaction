# Airline Passenger Satisfaction Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data sources](data-sources)
- [Tools Used](tools-used)
- [Data Cleaning/Preparation](data-cleaning/preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Results/Findings](results/findings)
- [Recommendations](recommendations)

### Project Overview

This project analyzes passenger satisfaction data from Dano Airlines to uncover insights about customer experience and highlight areas for improvement. The analysis was carried out as part of the capstone project for the Digitaley Drive Data Analyst Bootcamp, Using a combination of Excel for data cleaning and exploration, and Power BI for interactive visualization, the analysis identifies trends across different passenger demographics, travel types, and service ratings.


![Airline passenger satisfaction dashboard](https://github.com/user-attachments/assets/042ff23d-08b4-4c10-a9df-12d4837de78d)

### Data Sources

The dataset was provided by Digitaley Drive as part of a Data Analytics Bootcamp capstone project. It contains over 120,000 passenger records, including demographic details, travel information, service ratings, and overall satisfaction.

### Tools Used

- Excel - Data Cleaning
- Power BI - Data Analysis, Creating Reports

### Data Cleaning/Preparation


In the initial data preparation phase, I performed the following tasks:
1. Identified 393 null values in the Arrival Delay column.
   - These nulls were replaced with 0, assuming the passengers arrived on time.
   - Nulls represented less than 1% of the total dataset, making the impact minimal.
2. Created a new column to categorize passengers into age groups:
   - Children (0–12 years)
   - Teenagers (13–19 years)
   - Young Adults (20–35 years)
   - Adults (36–50 years)
   - Middle-aged (51–65 years)
   - Seniors (66 years and above)
3. Checked for duplicates across the dataset, none were found.

### Exploratory Data Analysis


EDA involved exploring the airline data to answer key questions such as:
- What factors are most strongly correlated with overall passenger satisfaction?
- How does passenger satisfaction vary by different demographics (age groups, flight types, etc.)?
- Calculate the average satisfaction score for each service category

### Data Analysis


1. Measures and KPIs (DAX)
- Total Passengers – Total number of passengers.
- Satisfaction Rate – Percentage of satisfied passengers.
- Dissatisfaction Rate – Percentage of dissatisfied passengers.
- Average Satisfaction Score – Mean satisfaction score across all passengers.
- Average Flight Distance – Average distance traveled by passengers.
2. Multi-row Card – Shows average satisfaction scores for all service categories (e.g., Cleanliness, Wifi Service, Gate Location, Seat Comfort) to identify best and worst rated services.
3. Column Chart – Visualizes average satisfaction by Flight Class (Economy, Economy Plus, and Business).
4. Pie Chart – Displays satisfaction by Customer Type (First-time vs. Returning).
5. Bar Chart – Compares satisfaction across Age Groups.
6. Donut Chart – Shows satisfaction by Travel Type (Personal vs. Business).

### Results/Findings


1. In-flight Service and Baggage Handling received the highest average satisfaction scores, making them the best-performing service categories across all passengers.
2. Wi-Fi Service and Gate Location had the lowest satisfaction ratings, indicating areas where Dano Airlines should prioritize improvements.
3. Returning customers reported higher satisfaction levels than first-time flyers, suggesting that loyalty and previous experience positively influence passenger perceptions.
4. Business class passengers showed significantly higher satisfaction compared to economy class passengers, highlighting the impact of class type on overall experience.
5. Passengers aged 46 and above were the most satisfied, while younger age groups (particularly 18–30) reported lower satisfaction on average.

### Recommendations

Based on the analysis, I recommend the following actions:

- Wi-Fi had the lowest satisfaction score. Invest in upgrading the onboard internet infrastructure and offer affordable, reliable connectivity to enhance passenger experience.
- Low ratings for gate location suggest inconvenience or long walking distances. Collaborate with airport authorities to ensure better gate assignments and clearer directional signage.
- Moderate satisfaction with online booking and boarding points to usability issues. Redesign the app and website for easier navigation and faster check-ins.
- Economy class passengers reported lower satisfaction. Improve seat comfort, meal variety, and in-flight entertainment without significantly raising operational costs.
- Returning customers are more satisfied. Launch or expand a frequent flyer program to reward loyalty and encourage repeat bookings.
- Enhance age-specific services by offering kid-friendly options for Children and Teenagers, improving digital experiences for Young Adults and Middle-aged passengers, and maintaining high standards for Adults and Elderly to further boost satisfaction across all age groups.







