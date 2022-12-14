<img src = "https://scwcontent.affino.com/AcuCustom/Sitename/DAM/014/bikeshare_Adobe.jpg">

# NYC Bike Sharing Data Analysis. Is Bike Sharing in Des Moines viable?

## Purpose of the project

This is for use by potential investors of the bike sharing project in Des Moines. The analysis done will show whether or not this is a viable positive project worth investment. Data analysis is done through Tableau and the data visualized for better understanding. This os a written analysis of the data explaining the visualizations and ultimately sharing the conclusion of this analysis.

The source of data for the analysis is the publicly available NYC Citi Bike data located on the Citi Bike Website. 
The data on trip duration is first convered to a datetime format using python's panda module. I used Jupyter Notebook to achieve this and exported a csv file that is uploaded and used in Tableau. This was to help capture the duration of every bike ride and consistently expresses a useable datatype.

### Questions to be answered:

What are the best locations to concentrate beginning efforts for this project?
What is the length of time bikes are checked out for all riders and genders?
What is the gender and user type distribution of potential customers?
What is the avergae bike trip length, thus influence distance between store locations>
What is the checkout time by gender?
How are trips distributed through the week?
How are trips distributed by gender through the week?
How are trips distributed by user type through the week?

[Link](https://public.tableau.com/app/profile/nehemiah.maheto/viz/Module14Challenge_16592899079540/Story1?publish=yes) to the Tableau Visualizations:

## Data Analysis
Let us take a deeper look at the different results concluded from this data.

![Image 1](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%200.jpg)

Table above depicts the most likely starting locations by the users. The areas with larger and darker colors depicts the most likely areas one will take out a bike for use. This will help investors when deciding where to start first to attract as much customers as possible. Strategic marketing will be key in these areas.

![Image 2](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%201.jpg)

Table above shows the time most people spend with the bikes before checking out. We can see most of the users only use the bikes for 5 minutes with the graph gradually falling thereafter. Most users will have checked out in twenty five minutes with the outliers spreading out till the hour with very few extending thereafter.
This coupled with the best starting locations, we can conclude that offices well spaced out within five to twenty minues of each other would be ideal in these areas to cater for all users within this area. The offices can spread out with longer distances as we head into the least best starting locations.

![Image 3](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%202.jpg)

Figure above shows us the distribution of these checkout times by gender.

![Image 4](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%204.jpg)

Figure above shows us the gender distribution between the two user types.
The high number of uknowns in the customer group indicates that customers rarely give or opt not to indicate their genders. We can still see a relatively high number of males in both user groups. This may help in targeted marketing.

![Image 5](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%203.jpg)

Figure above shows distribution of trips through the week. Most people use it in the morning and evening hours assumably to and from work. There is also a high number of trips during the day on Saturday. Sunday shoes a relatively lower number of trips.

![Image 6](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%205.jpg)

Figure above shows the distribution of the weekly trips by gender.

![Image 7](https://github.com/Nehemiahmageto/bikesharing_/blob/main/Visualizations/Capture%206.JPG)

Figure above shows the distribution per week per user type and by gender. We can see a high number of trips by subscribers as expected, but an even higher number by the male subscription group more than any other group.

# Summary
From the analysis we can come to a conclusion that there is a huge demand for cycling especially to and from work which will give continuous market throughout the year. We also have dedicated subscription especially from male users. We also know where to locate out outlets best suitable for the market groiup.

For the future, we may look to visualize;

1. The routes most taken, from the start and endpoint.
2. Growth of market size between different points in time.
