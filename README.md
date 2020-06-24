# King County Home Prices Multiple Linear Regression Modeling

<img src='Images\22680345663_87edff3bb7_o.jpg'/>

## Introduction 
For this project, we wanted to predict housing prices in King County, which is located in Seattle, Washington. We used Multiple Linear Regression modeling to help analyse our data, dive deeper to explore and answer a few questions around specific features, and predict housing prices in the area. I specifically wanted to take a closer look at the correlation of price compared to the condition, zipcode, and year built features.

## Data Description
<summary style="font-size: 18px"> Data File Used</summary>

* kc_house_data
* housing_dataset_cleaned (1)
* no_outliers_housing
<details><summary style="font-size: 16px"> Question 1: How are prices distributed throughout King County?</summary>

#### Question Details
We found that the highest priced homes were closer to the larger cities as well as near Lake Washington which seems to also be correlated with the fact that Seattle is home to a large tech industry. Microsoft and Amazon are headquartered in the metropolitan area. 

Housing prices are more expensive in close proximity to Seattle and Bellevue. (Dark green cluster East of Lake Washington.)

Housing prices are less expensive the farther you go away from Lake Washington in any direction.

<img src= 'Images\unnamed (1).png'/>
</details>

<details><summary style="font-size: 16px"> Question 2: What effect does housing condition on the sales price?</summary>

#### Question Details 
We wanted to look at how home condition affected prices along with combining a few more features such as zip code and year built to see if those features had any affect in combination with the first feature.  

<img src= 'Images\newplot (1).png'/>

The homes between 1900 and 1980 have the highest condition ratings. They are holding their values very well due to the fact that there is a shortage of homes in King County. The home owners are keeping their properties nicely renovated because the county is growing at a rapid rate. Seattle is the 5th most expensive city to live in the United States and with a home shortage of 1 home to 1060 people, the home prices are surging.
<img src= 'Images\download (3).png'/>

We also wanted to know if there was a specific zip code that had the highest rated condition homes compared to price. The two zip codes with the most 5 rated condition homes was in 98125 and 98101. These areas are located in downtown Seattle in waterfront properties and more specifically, Pikes Place Market.
<img src= 'Images\download.png'/>

</details>

<details><summary style="font-size: 16px"> Question 3: Does the grade of the home affect the sale price?</summary>

#### Question Details
We looked at homes with a grade between 8 through 12 in the area to help predict home price. We developed a predictive model and as you can see, between grade 9 and 10, there is a price increase of $255,454 and that is also the average increase between each grade. Our findings concluded that for eacg home grade increase, the property value increases by 3-5%
<img src= 'Images\grade_9_prediction.png'/>
<img src= 'Images\unnamed.png'/>

</details>

## Conclusion/Recommendation

1. Depending on the budget of the buyer, if they are looking for a more luxurious house then they should look towards the Seattle downtown area and Lake Washington.  If they are looking for a less expensive home, than they should look at the houses which are a far distance from Seattle and the lake.

2. Older homes should be purchased between the years 1900 and 1980 due to the fact that these homes possess the highest home condition ratings and they seem to hold their value the most. Renovations definitely needs to be kept current in order to keep the property values high, but these homes will hold their value and are great investments due to the high demand of living in King County and the scarce homes available on the market to be sold. There is 1 home available for every 1060 people in the Seattle area. 


3. The homes with the highest conditions and prices are located in zipcodes 98125 and 98101 which is more specifically, Pikes Place Market in Downtown Seattle. Purchasing homes in these zip codes will also provide very high investment returns due to their high populatity and demand. Seattle is the 5th most sought after city to reside in the United States. 

4. Conduct a high quality renovation in your home before selling to ensure the highest home grade which will increase property value. If you are looking to buy in the area, then make sure that you check the grade of the house to ensure higher quality for your money. The higher the grade, your property value will increase 3-5%

* My notebook in this respitory only covers question 2 in detail. My team has specific notebooks that they used to answer questions 1 and 3. Please check those out.

<a href="https://github.com/jari-el13/dsc-mod-2-project-v2-1-onl01-dtsc-ft-041320/blob/master/student.ipynb">Question 1: How are prices distributed throughout King County?</a> 

<a href="https://github.com/leighannajo/dsc-mod-2-project-v2-1-onl01-dtsc-ft-041320">Question 3: Does the grade of the home affect the sale price?</a>

* If you haven't read my blog on this project, please check it out.

<a href="https://medium.com/@heatherrachael9/creating-a-predictive-model-for-home-prices-that-anyone-can-use-73749d6b1e40">Medium Blog</a>
## Future Work
* We want to do some more research into the Affordable Housing Shortage in Seattle and figure out if there is any special programs for home buyers in the area to assist in their purchase. 
* With the high cost of living in Seattle, we also wanted to look into the average income of residents to see if Seattle offers enough income for the average reseident to live comfortably. 
* Examine the effect that Microsoft and Amazon has in moving to Seattle on home price.
* Get more information on demographic data and add those findings into new features and test. 
