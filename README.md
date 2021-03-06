# comparing-baltimore-chicago-incarceration-rate-low-incomes
Overview: Data trends and visualizations for Baltimore and Chicago incarceration for people who came from 25th percentile parent income.
Brief Description: For this project I looked at incarceration rates for children who were born with parents at the 25th percentile of the national income distribution. The data codebook describes incarceration as residing in a federal detention center, federal prison, state prison, local jail, residential correctional facility, military jail, or juvenile correctional facility. I decided to use the census track data from https://www.opportunityatlas.org/ , but also the full data set from https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing . I compared Baltimore to Chicago, because that is where I was born. My findings were that:
* When looking at the tract data from https://www.opportunityatlas.org/ , on average Baltimore has a higher incarceration rate than Chicago
* When looking at the full data sheet from https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing , on average Chicago has a slightly higher incarceration rate than Baltimore (but it's almost the same)
* On average men are incarcerated far more significantly in both cities than women
* When looking at the tract data from https://www.opportunityatlas.org/ , on average men in Baltimore are incarcerated more than men in Chicago
* When looking at the full data sheet from https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing , on average men in Chicago are incarcerated more than men in Baltimore. But on average women in Baltimore are slightly more incarcerated than women in Chicago
* In order to compare with the full data set, I looked at the following races - Black, Hispanic, and White. For both cities black people are incarcerated the most on average
* On average for both data about Baltimore, White people were the second most incarcerated population on average. However, for Chicago the data from https://www.opportunityatlas.org/ said White people were the second highest, while the data from https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing said hispanics were the second highest in Chicago


![](AllRaces.PNG)


Later, this same analysis was done in Python, and the same findings were discovered again. After using both Excel and Python, Pivot Tables were easier to construct in Excel. In Python, it appears more difficult to separate each column by city. Python utlimately was just not as helpful for my particular dataset for this project and added additional steps that made me still use Excel for certain elements. The graphs were simple to generate, however, using this software. Some visualizations formed by plotly are below: 


![](IR%20by%20City.png)
![](IR%20by%20Males.png)
![](IR%20by%20Race%20(Black).png)
![](IR%20by%20Race%20(White).png)
![](IR%20by%20Race%20(Hispanic).png)
# Note: 
I think the reason for some of these different distributions is because for the data from https://www.opportunityatlas.org/ , Baltimore and Chicago reported data for about the same number of areas found, whereas the data from https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing had a count of almost 250 more people on average and far more areas listed in Chicago, so the data from here might show a bias - but I used it to get gender data and then found it might be helpful to compare all of its data to what I originally found. The tract data had no data on female incarceration, but the full set data did.

# Takeaways: 
Despite some differences in the data, it can be assumed that Baltimore and Chicago have similiar issues with incarceration rates for this specific population, and in terms of Baltimore-centric solutions a good approach may be to look at what Chicago is doing and learn from what they are doing wrong or improving upon to help this issue (if at all), in order to foster change. 

# Simple step-by-step description:
* Went on https://www.opportunityatlas.org/ and searched incarceration rates for Baltimore and Chicago, and downloaded the Geography Tracts and also the Full Data Sets
* I then constructed Pivot Tables for the different subgroups (Everyone, Gender, and Race) I wanted to find with the data, taking the data for each individual city out from the mass data and finding averages
* After this, I created graphs from both data to compare
* I used Pivot Tables, chart generation, and basic calculations for this project

# Link to Full Data Sheet (too large): 
https://drive.google.com/open?id=1lfRlNJd3JjdU_HvhXSrH0titgZWgxR5p
