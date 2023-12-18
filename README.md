# Historic_houses_to_resell_in_Seattle
Finding the best historic houses to resell in Seattle

The objetive of this challenge is finding the best historic houses for one investor who wants them in the best neighborhoods of Seattle, King County, and to resell them within a year with high profits. He is willing to renovate the house.

![image]([Best_Historic_houses.png)]


To solve this challenge I had to import the database from SQL by selecting several variables from different tables in sql to create a Dataset in Python. I then began an exploratory data analysis stage, defining the rules both for classifying a house as historic and for selecting the structural and maintenance conditions that would qualify them as a good buy for resale. These historic houses were then categorised into 1. refurbished historic houses, 2. unrefurbished historic houses with low refurbishment costs and 3. Historic houses that have not been refurbished but do not require refurbishment. With a good resale value in mind, the 10 neighbourhoods with the highest average house values were selected and 190 houses were then spatialised. The database was then statistically analysed in order to filter out the 'good outliers', i.e. well-located houses with low or no renovation costs, with a size close to the average of the other houses, but which had advantageous prices. In short, a list was created with 8 homes (5 with a demand for low-cost renovations and 3 with no demand for renovations) that had an average value around 40% lower than the average of the other well-located historic homes, which would allow the client a good profit margin.

Both coding and presentation are available in this repository.
