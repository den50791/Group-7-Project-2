# MIST 4610 Project 2

# Team Name
47114 Group 7

## Team Members:
- Leif Hurdal ([@leifhurdal](https://github.com/leifhurdal))
- Amy Morales ([@amymorales](https://github.com/amyfrmorales))
- Dung Nguyen ([@dungnguyen](https://github.com/den50791))
- Vivian Pham ([@vivianpham](https://github.com/vivianxpham))
- Ben Williams ([@benwilliams](https://github.com/bendeanwilly))

## Dataset Description:

### Dataset 1: California Hospital Performance Ratings
  - **Source**: [Data.gov](https://catalog.data.gov/dataset/california-hospital-performance-ratings-91d9b/resource/7ac54225-fb51-40c3-b2fb-9979a4bbc620)  
  - **Dimensions**: 25974 rows X 13 columns
  
  - **Columns**: 
  
    - Year: Year of the performance rating data.
    - County: County where the hospital is located.
    - Hospital: Name of the hospital.
    - OSHPD-ID: Identifier for the hospital from OSHPD (Office of Statewide Health Planning and Development).
    - System: Type of healthcare system the hospital belongs to.
    - Type of Report: Type of performance report.
    - Performance Measure: Specific measure of hospital performance being reported.
    - Number of Adverse Events: Number of adverse events recorded.
    - Number of Cases: Number of cases or procedures evaluated.
    - Risk-Adjusted Rate: Performance rate adjusted for risk factors.
    - Hospital Ratings: Rating assigned to the hospital based on performance.
    - Longitude: Longitude coordinates of the hospital location.
    - Latitude: Latitude coordinates of the hospital location.
  
  - **Data Types**: Numeric (Integer), Text (String), and Numeric (Float)

### Dataset 2: California Hospital Inpatient Mortality Rates and Quality Ratings
  - **Source**: [Data.gov](https://catalog.data.gov/dataset/california-hospital-inpatient-mortality-rates-and-quality-ratings-c11e9)  
  - **Dimensions**: 53216 rows X 11 columns
  
  - **Columns**:
  
    - Year: Year of the mortality rate and quality rating data.
    - County: County where the hospital is located.
    - Hospital: Name of the hospital.
    - OSHPD-ID: Identifier for the hospital from OSHPD (Office of Statewide Health Planning and Development).
    - Procedure/Condition: Medical procedure or condition evaluated for mortality rate.
    - Risk-Adjusted Mortality Rate: Mortality rate adjusted for risk factors. The Risk-Adjusted Mortality Rates (RAMR) presented here adjusts the observed mortality rates. This statistical methodology takes into account preexisting health problems that put some patients at greater risk of death to “level the playing field” and allow fair comparisons across hospitals.
    - Number of Deaths: Number of deaths recorded for the procedure/condition.
    - Number of Cases: Number of cases or procedures evaluated.
    - Hospital Ratings: Rating assigned to the hospital based on quality metrics.
    - Longitude: Longitude coordinates of the hospital location.
    - Latitude: Latitude coordinates of the hospital location.
    
  - **Data Types**: Numeric (Integer), Text (String), and Numeric (Float)

### Dataset 3: Poverty Across California
  - **Source**: [ppic.org](https://www.ppic.org/data-set/poverty-across-california/)  
  - **Dimensions**: 60 rows X 2 columns

  - **Columns**: 
    - County: Name of the county.
    - CPM Poverty Rating: Poverty rating based on the County.
  
  - **Data Types**: Text (String) and Float (Decimal)

## Team Questions:

1. How do hospital ratings in California affect the average risk-adjusted mortality rate for different procedures? Which procedure was performed "worse" by hospital rating based on the highest risk-adjusted mortality rate?
   - Importance: The question is important because it allows one to analyze the impact of hospital performance on mortality rates for different medical procedures. This brings significance for the hospitals in the state of California as well as patients looking for appropriate medical care. By evaluating the relationship between hospital ratings and mortality rates, hospitals can identify where there may be issues concerning quality control and allocate additional resources for better patient care. From this, incoming patients can make informed decisions when deciding where to receive medical treatment based on their medical condition/procedure. 
   - Tie to Dataset: This relates to the second dataset because it provides information on hospital ratings, risk-adjusted mortality rates, and procedure/conditions allowing us to come up with this visual model. 
    
2. What is the relationship between poverty rates and the average risk-adjusted mortality rates by county?
   - Importance: The question is important because it reflects on the understanding of how one's financial situation can affect the outcome of one's health, specifically mortality rates. Economically, there may be costs or threats to the economy as a state or by county for poverty-related inequalities. From this, authorities in the state of California may use this insight to hold accountability and implement policies to target possible health disparities regardless of one's income. However, if there is no clear relationship, officials would be encouraged to investigate other factors besides poverty rates to determine the overall health outcomes of the people.
   - Tie to Dataset: This relates to the second and third datasets because it provides information on the risk-adjusted mortality rates, county, and CPM poverty ratings with some data manipulation.
   
## Data Manipulations:
   - (Describe manipulations to dataset)
   - Purpose: 

## Analysis and Results:
   - (Summary of analysis)
   - Visualizations: ![IMG_3836](https://github.com/den50791/MIST4610-Group-7-Project-2/assets/163002845/7a34f425-e661-48cb-9dae-9fe0923d0598)
   - Implications:
   - Citations:
