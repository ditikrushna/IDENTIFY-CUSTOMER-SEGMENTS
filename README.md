##  Identify Customer Segments (Machine Learning Project)

### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Objective](#objective) 
  * [Data Overview](#data-overview) 
  * [Technologies Used](#technologies-used)
  * [Techniques Used](#technique-used)
  * [Results and Discussion](#Result-and-discussion)
  * [To Do](#to-do)
  * [Team](#team)
  * [Licence](#licence)
  * [Credits](#credits)

### Overview 
In this project, Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company. I have looked at relationships between demographics features, organized the population into clusters, and saw how prevalent customers are in each of the segments obtained. 

### Objective 
Apply **unsupervised learning techniques** on demographic and spending data for a sample of German households. Preprocess the data, apply **dimensionality reduction techniques**, and implement **clustering algorithms** to segment customers with the goal of optimizing customer outreach for a mail order company. 

### Motivation 
This project was completed as part of Udacity's [Data Scientist Nanodegree](https://eu.udacity.com/course/data-scientist-nanodegree--nd025) certification. 

### Data Overview 
The files used in the project:

-   `Udacity_AZDIAS_Subset.csv`  : Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
-   `Udacity_CUSTOMERS_Subset.csv`  : Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
-   `Data_Dictionary.md`  : Information file about the features in the provided datasets.
-   `AZDIAS_Feature_Summary.csv`  : Summary of feature attributes for demographic data.
-   `Identify_Customer_Segments.ipynb`  : Jupyter Notebook divided into sections and guidelines for completing the project. The notebook provides more details and tips than the outline given here.

### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://github.com/scikit-learn/scikit-learn/blob/master/doc/logos/scikit-learn-logo-small.png">](https://github.com/scikit-learn/)
<img target="_blank" src="https://github.com/ditikrushna/IDENTIFY-CUSTOMER-SEGMENTS/blob/master/Resource/Seaborn.jpg" width=170> 
<img target="_blank" src="https://github.com/ditikrushna/IDENTIFY-CUSTOMER-SEGMENTS/blob/master/Resource/matplotlib.png" width=170> 
<img target="_blank" src="https://github.com/ditikrushna/IDENTIFY-CUSTOMER-SEGMENTS/blob/master/Resource/numpy.png" width=170>  
<img target="_blank" src="https://github.com/ditikrushna/IDENTIFY-CUSTOMER-SEGMENTS/blob/master/Resource/pandas.png" width=170>  

### Techniques Used 

1. K-means clustering
2. PCA 

### Results and Discussion 
A comparison of customer to demographics data. The two clusters distribution comparison allowed to see where the strongest customer base for the company is. 

<image target="_blank" src="https://github.com/ditikrushna/IDENTIFY-CUSTOMER-SEGMENTS/blob/master/Resource/result.png" width=""> 

The company seems to be doing well with rather older people, living in less-dense households, more traditional and conservative (focus on investing/saving) where mail order sales can appear to be a more attractive option.

The company is not so efficient in targeting more younger and educated audience, living in more high-density areas, having bigger consumption and being more materialistic (focus on spending). 
### Todo 
1. Apply different clustering algorithms 
2. Creates a web application 
3. Deplyment has to be done in near future in some platform like [Heroku](https://g.co/kgs/D6wEju)

### Team  
[![Ditikrushna Giri](https://ditikrushna.me/images/diti.jpg)](https://ditikrushna.me/) |
-|
[Ditikrushan Giri](https://ditikrushna.me/) |)


### Licence
Feel free to use the code and let me know if the model can be improved. If you would like to do further analysis, it is available below under a [Creative Commons CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)license.  

### Credits 
1.  Graphical image of result and discussion taken from [Ksatola](https://github.com/ksatola)'s notebook . 
2.  Logo of different packages are taken from different source and they are all non-copyright images . 
