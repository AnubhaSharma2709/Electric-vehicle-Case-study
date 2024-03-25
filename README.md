# Electric Vehicle (EV) Market Segmentation

## Project Overview

This project aims to analyze and segment the electric vehicle (EV) market in India to identify optimal market segments for establishing an EV startup. By leveraging various segmentation techniques and datasets, the goal is to tailor marketing strategies and product offerings to meet the diverse needs and preferences of different consumer segments.

## Market Potential Estimation

### Total Population:
Approximately 1.4 billion people.

### Percentage of Urban Population:
Around 30% of India's population resides in urban areas.

### Vehicle Ownership Rate in Urban Areas:
Assume 1 vehicle for every 4 urban residents.

### Potential EV Urban Market:
Estimated 105 million potential urban EV users.

## Segmentation Factors

### 1. Psychographic Segmentation:
- Environmental Consciousness: 40% of urban population prioritize eco-friendly products.
- Technology Enthusiasts: Assume 60% of urban population are early adopters of new technology.

### 2. Behavioral Segmentation:
- Commuting Habits: Estimate 50% of urban population commute less than 30 km daily.
- Parking Facilities: Assume 70% of urban residents have access to private parking.

### 3. Geographic Segmentation:
- Focus Cities: Delhi, Mumbai, Bangalore, Chennai, Kolkata, Hyderabad, Pune, Ahmedabad, Surat, Jaipur.
- Tier 2 Cities: Indore, Chandigarh, Lucknow, Kochi, Bhopal, Visakhapatnam, Nagpur, Coimbatore, Vadodara, Patna.

### 4. Demographic Segmentation:
- Age Groups: 30% of urban population falls within 25-40 age bracket, likely early adopters.
- Occupations: Assume 20% of professionals such as IT workers and consultants are interested in EVs.

## Data Preprocessing

Based on the provided datasets, preprocessing steps include:
- Mapping categorical data to numerical format.
- Handling missing or invalid data.
- Converting 'Make' column to numerical values.
- Dropping unnecessary columns.

## Segment Extraction (ML techniques used)

Utilizing the Elbow Method for K-Means clustering, we identified 4 optimal clusters to segment the data, enabling the identification of meaningful patterns and segments within the dataset.

## Profiling and Describing Potential Segments

Segments are described based on hierarchical clustering of segmentation variables:
- Segment 0: Age, Profession, Marital Status, Education, No of Dependents, Personal Loan, House Loan, Wife Working, Make.
- Segment 1: Profession.
- Segment 2: Total Salary.
- Segment 3: Salary.

## Selection of Target Segment

Segment 2 is selected as the target segment for the EV startup due to:
- High Financial Status.
- Age Demographics alignment.
- Stable Income.
- Preference for SUVs.

## Customizing the Marketing Mix

Potential Customer Base in the Early Market:
- Estimated sales and profits for Electric 2-Wheelers, 3-Wheelers, and 4-Wheelers.

## The MOST OPTIMAL MARKET SEGMENTS

Based on comprehensive analysis, the most optimal market segments are identified by geographic and demographic factors, focusing on high-demand states and strategic product offerings.

### Feasible Strategy:
- Focus on High-Demand States.
- Leverage Existing Infrastructure.
- Government Subsidies and Incentives.
- Product Focus: EV 2-Wheelers and SUVs.

By targeting these optimal market segments and aligning product offerings, the EV startup can capitalize on the growing demand for electric vehicles in India.

## Data Sources
- [Electric Vehicle Models Dataset](https://www.kaggle.com/datasets/kkhandekar/electric-vehicles-india)
- [Indian Automobile Buying Behavior Study Dataset](https://www.kaggle.com/datasets/karivedha/indian-consumers-cars-purchasing-behaviour)
- [State-wise Electric and Non-electric Vehicle Registrations Dataset](https://data.gov.in/search?title=Electric%20Vehicles)

These datasets provide comprehensive insights into various aspects of the electric vehicle market in India, facilitating informed decision-making and targeted approaches.

