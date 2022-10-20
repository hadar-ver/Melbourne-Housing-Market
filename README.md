# Melbourne-Housing-Market
This project is the final assigment of the 'Selected Topics in Statistics' course as part of the 'Data Science' M.Sc at Ben Gurion University in Israel, and it was made by Hadar Verthaim, Zofit Allouche, Guy Niran.
In this project, we analysed real-life data of properties sold in Melbourne, Australia, using Python. We aimed to train a model that will be able to predict the sell price by using most available attributes as an input. The first phase focused on exploratory data analysis that was performed on the model to feel the data, see correlations between the variables and to identify issues and abnormalities in the data. Then, the pre-processing phase prepared the data for modeling, in which we capitalized the prices to one period, in order to nullify the change of currency value affect. Also, linearity assumptions were tested and addressed when needed. The models that were tested are Linear Regression, LASSO regression, Random Forest, CatBoost and Artificial Neural Networks. Our metric for evaluation and comparison is the Mean Absolute Error, which can give proportions to the goodness of the model while also be a metric to compare with other models. We have found wide difference of score between the models. The best model found is CatBoost. The results are showing that it is a difficult task to accurately predict the price, as the mean of the error for the best model is approximately 200K.

Housing market in Melbourne has been increasing in recent years, making many investors interested in assessing a price for properties such as house, cottage, or a villa.
The data for this project was downloaded from Kaggle. The data was scraped from the publicly available website www.Domain.com.au. This dataset includes Price, Address, Type of Real estate, Suburb, Method of Selling, Rooms, Real Estate Agent, Date of Sale and distance from C.B.D. (Central Business District). 
Inspired by the distance from CBD feature, an additional feature that measures the distance of the properties to major public healthcare was created using the geographical coordinates of both properties and hospitals.
We’ve decided to capitalize the price target, so that we nullify the decrease of AUD during time. Both features above will be elaborated in the pre-processing phase.
We did not take into consideration, but aware of, other changes that could be affected pricing over time, such as suburb popularity change, seller reputation change and so forth.

Our research goals were:
1.	To build a model which will enable an accurate prediction of house prices in Melbourne, Australia, using available information online
2.	To find the most important features that has the strongest effect on house prices

![image](https://user-images.githubusercontent.com/71387302/196926120-207f5c2c-77b7-4fef-85c6-34137632271f.png)

