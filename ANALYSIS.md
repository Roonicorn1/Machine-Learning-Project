# ANALYSIS  
The following is the technical analysis of the data and the links to the models used in the shaping the data.  
## Final Model  
[Linear_Regression](linear_regression.ipynb)  
This model was chosen based on the fact that it fit the data the best. When compared to the other models like the Decision Tree and the SVM, the Linear Regression model had a better time fitting the data and also didn't eat my laptop's RAM like the other 2 models. 
## Trial Models
[Classification](Classification.ipynb)  
These are included for credibility, I did not just choose regression as a cop out. I tried out the other models and they did not work well for the data I chose. 

## Findings and Commentary  
So beginning this project the first milestone began with Linear Regression since that is what we went over in class first. The Model worked very well in the beginning aside from early hiccups. At first I had a hard time identifying which features to choose. After looking through the data a bit I found a few that seemed to be related. The features were the percentage of the population of the county that worked in a particular field. Professional, Service, Office, and Construction are the features I chose to dig into and see if they could be used to identify the median income of a county. Production was also a feature that was related to the others but was left out due to shaping errors. It is still included in the plots of the data.  

Aside from Linear Regression I tried a Decision Tree and a SVM both of which did not perform as well as the Linear Regression. Initially this was disheartening because those models were to me a big part of what makes machine learning different from a statistics class and I'm sure with more time and work I could adapt those models in the future. The struggle of not being successful with the other models was overcome by still having the Linear Regression to fall back on. 
