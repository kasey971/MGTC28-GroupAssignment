# Starting a Toy Store in Toronto

## Insights in the Toy Industry in Canada

### Opportunities

1.    Online learning

Since the COVID-19 pandemic, more people adopted working-from-home styles and more chlidren have adapted to online learning. 
The time and chances for children to get together with friends are reduced, so parents seek to purchase more toys for their children. 
Thus, the needs for toys have been increased.

2.    High revenue growth

According to the report of [IBIS World](https://my-ibisworld-com.myaccess.library.utoronto.ca/ca/en/industry/45112CA/performance), there is a large growth in the revenue of the toy industry from 2018 to 2023 in Canada. 
The overall profits, the number of employees, the number of businesses, and the average wage have also increased from 2018 to 2023. 


### Challenges

1.    Price-based competition

The products sold by different stores tend to be the same, so many businesses choose to lower the prices of toys to attract customers. 

2.    Decrease in the profit margin

The report of IBIS World also indicates a decrease in the profit margin from 2018 to 2023 in Canada. 


## Data Preparation

### Toronto Neighborhood Data
1.    Source - wikipedia for postal codes in Toronto & geographical coordinates
2.    Variables - (1) postal code, (2) borough, (3) neighborhood, (4) latitude, (5) longitude

### Demographic Data
1.    Source - Statista database, 2021 Census of Population
2.    Range - only select areas in Central Toronto
3.    Variables - (1) the number of children in the region, (2) the rate of children in the population of the region, 
(3) the median after-tax income in 2020 among recipients, (4) the number of employed individuals, 
(5) the unemployment rate in the region

### Competitors Data
1.    Source - Foursquare Places API
2.    Variables - (1) the number of other toy stores in the region, (2) the reviews from customers on these stores


## Data Analysis

### Bar Plots
Among all regions in Central Toronto, region with postal code M4S (Davisville) has the largest number of children as well as employed individuals. 
The unemployment rate in M4s is the 3rd low and the median after-tax income in 2020 in M4S is high enough. 
M4S also has the smallest number of competitors. 

Thus, we suggest M4S for starting the toy store because of potentially large needs and low competition. 

### Customer Reviews

We also collected the reviews from customers on the existing toy stores in Davisville. 
Most reviews are positive. Here are some points that customers find satisfied with the stores. 
Few negative points mentioned by the reviews are listed above. A store does not accept phone payment or card payment. A person asked whether a specific toy was sold in the store, suggesting that there is no easy way for customers to get a list of what toys are in the store. 

Based on these reviews, we suggest the following strategies for the new toy store:
1.    Being friendly to customers
2.    Offering discounts and holding events occasionally for customers
3.    Digitalization of the products list so that customers can easily find the toy they want to buy
4.    Accepting various payment methods, including cash, card, phone, etc.
5.    Offering other services to increase competitiveness, such as gift wrapping, gift purchase consulting, etc. 

## Contributions
Yunqian Cao: 
	·Business Problem Design: Conducted market research using resources like IBISWorld to identify opportunities and  decided to develop the Toy Store business
	·Responsible for the extraction and the process of data ‘Toronto Demographic Information'. 
	·Presentation Development: Designed and structured the presentation slides to ensure clarity, coherence, and visual appeal
	
	

Stanley Gong:
	··Data Extraction: Collected and processed Toronto neighborhood data using Foursquare API and census data.
	·Competitor Analysis: Used the Foursquare API to map competitors in selected neighbourhoods, identifying gaps and opportunities for the proposed business.
	·Data analysis and visualization.  
	·Market Research on competitors' customer review
	


