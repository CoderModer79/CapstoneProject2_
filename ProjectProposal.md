The problem :

Twitter Sentiment Analysis over 13 Feelings

The Client

a. Individual Buyers : Whoever interested in buying a new car wonders about the actual value of the specific car with the one which was asked by the seller. So it is important for all to come to a better understanding of the values of the cars.

b. Dealers : Most dealers would like to learn the value of that individual car, and determine its value later on.

c. Individual Sellers : Most private sellers would need the value of their car since the value is not constant, it changes considering the depreciation, the repairs etc.

d. Websites or Applications created to help private parties or dealers sell their vehicles.

e. .....

Data Set:

a. Link of Data from Kaggle : https://www.kaggle.com/orgesleka/used-cars-database/data

b. Data Set includes 19 features and 371528 data points/observations.

c. The data seems raw. Has too many missing values, outliers. Also includes nonsense/ wrong entries like 9999 as year of Registration.

d. This data includes the data points/observations from 2016. (I will search for methods to scrape data for 2017.)

e. Target Feature is 'price'. Since it is the price of an individual car, it is continuous.

My approach to solve this problem: **

a. This seems to be a supervised problem.

b. Regression, cause the dependent feature needs to be continous. However, I will combine cross-validation, GridSearch, Random Selection and etc.

c. My dependent feature would be the value of the used cars.

d. My independent features would be the 'name' of the car, seller type, horse power of the car, mileage, any damage or repair, gearbox (automatic or manuel), age of the car...

e. I am thinking of dividing the data I have with 'train_test_split' feature of scikit learn. If I end up getting the data for 2017, then I would use the data from 2016 as my training data.
