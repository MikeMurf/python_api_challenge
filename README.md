# python_api_challenge
Main Observations / Insights

The saved figures from the plots have been incorporated into these observations insights for explanatory purposes and legibility.
 
1.	The most noticeable trend for the cities generated by the random sampling is that: -

•	67% of the cities sampled are in the Northern Hemisphere, and, 
•	33% of the cities sampled are in the Southern Hemisphere.
•	This is nearly identical to the land masses of the respective Hemispheres.
•	68% of the earth’s land mass is in the Northern Hemisphere, and,
•	32% of the earth’s land mass is in the Southern Hemisphere.
•	Reference: https://www.worldatlas.com/articles/which-hemisphere-has-the-largest-area-covered-by-land.html
•	This confirms that the cities sampled are distributed relatively uniformly by latitude as the sampled cities conform almost exactly with the land masses of the hemispheres.


2.	Analysis of World-Wide Latitude versus Temperature reveals the following trends: -

![image](https://user-images.githubusercontent.com/89948865/148723293-6062318d-82e1-42fb-a69e-30a1f7374743.png)


1)	Temperature tends to increase almost linearly as you move from the most northern latitudes towards the equator then plateau out once you reach 23 degrees (the Tropic of Cancer). 
2)	The cities sample was taken in the Southern Hemisphere summer (Northern Hemisphere winter) hence: -
o	The temperate zone between the Tropic of Capricorn (-23 degrees) and the Equator (0 degrees) is experiencing hot summers conditions, 
o	The temperate zone between the Tropic of Cancer (23 degrees) and the Equator (0 degrees) is experiencing cool winter conditions.
3)	The tropics of Capricorn and Cancer are the latitudes where the sun is closest to the earth in the respective summers which would account for the plateauing of high temperatures at this level in the Southern Hemisphere.
4)	The r squared value of 0.88 for the Northern Hemisphere shows a strong degree of fit to the line of best fit indicating a strong relationship between latitude and temperature [Refer point 2.1) below].
5)	Interestingly, the r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere [Refer point 2.2) below].
6)	This may be explained by the sample size of 184 for the Southern Hemisphere versus the sample size of 378 for the Northern Hemisphere. Further statistical analysis beyond the scope of this assignment is required to explore this further.

2.1)	Linear Regression - Northern Hemisphere cities' Temperature vs Latitude

![image](https://user-images.githubusercontent.com/89948865/148723349-19d6ec98-8a26-4933-8e62-9f04d9d66779.png)

The r-square is -0.875522577935197

•	The linear regression plots Northern Hemisphere cities' temperatures against their latitude.
•	The regression shows that temperatures are higher near the equator and lower further away from the equator.
•	The r-square value of -0.88 rounded shows that there is a strong degree of fit to the line of best fit for latitude and temperature.

2.2)	Linear Regression - Southern Hemisphere cities' Temperature vs Latitude

![image](https://user-images.githubusercontent.com/89948865/148723387-15ccb019-ada3-4b2d-a9bb-2ddab18d1e5a.png)

The r-square is 0.3681140053502776

•	The linear regression plots Southern Hemisphere cities' temperatures against their latitude.
•	The regression shows that temperatures are higher near the equator and lower further away from the equator.
•	The r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere.



3.	Analysis of World-Wide Latitude versus Humidity reveals the following trends: -

•	There does not appear to be any particular correlation between latitude and humidity on a world-wide comparison [Refer point 3.1) below].
•	The r squared value of 0.88 for the Northern Hemisphere, however, shows a strong degree of fit to the line of best fit indicating a strong relationship between latitude and temperature [Refer point 3.2) below].
•	Interestingly, the r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere [Refer point 3.3) below].
•	Again, this may be explained by the sample size of 184 for the Southern Hemisphere versus the sample size of 378 for the Northern Hemisphere. Further statistical analysis beyond the scope of this assignment is required to explore this further.

3.1)	World_Wide cities' Humidity vs Latitude

![image](https://user-images.githubusercontent.com/89948865/148723494-7ba248cb-cdc5-4ff7-8037-411e51d163a7.png)



3.2)	Linear Regression - Northern Hemisphere cities' Humidity vs Latitude

![image](https://user-images.githubusercontent.com/89948865/148723564-76f3c4f7-acba-47dd-bfbc-39c7068b0c44.png)




