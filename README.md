# Optimized-Data-Acquisition

For the purpose of my Data Analyst's professional training, I worked on optimized data acquisition's solution. BottleNeck is a famous wine vendor. It has plenty of shop across Europe, especially in France which represent at least 50% of sales. 
As freelance Data Analyst, I had to find out relationship between data provided by ERP and CMS and merge in a consistent data structure. 

# 1. Data Clean up

It's the most important part of the solution. Indeed, much of the work consisted in data's manipulation (sorted data, delete unrevelant features, missing values, replace wrong data..). 
So in this part, I have done some quantitative and qualitative analysis to quickly identify relevant data and data to remove. My decision to keep feature or not depending to missing values's proportion and correlated features. 

I also checked uniquness on all of my pretending primary-key before merging.  

Finally, I was able to merge data from 

# 2. Testing Data Requests 

The first step allowed me to work with relevant well-sorted data. Next, I wrote data request to get annual sales and compare it with sale department team. 
In addition, my algorithm taking CMS and ERP merged data as parameters, provides monthly sales report for each online product of our catalog. 


# 3. Outliers's additional analysis

Outliers additional's analysis helped me to have more detailed information about each of my quantitatives features. With a basic boxplot data representation overviewing my data distribution, I was able to identify and correct them if necessary. 
In my case, this kind of analysis was useful to detect wrong prices's input like 2 000-euros's Chateaux de la Loire instead of 20.  
