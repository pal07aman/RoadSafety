# RoadSafety
200102

PART B
Source-kaggle , link- https://www.kaggle.com/datasets/shree1992/housedata

PART C

The data which i have used , on plotting will display a scatter plot having data points linearly arranged . Also we know regression works on a straight line in which trend line is set through the data points to tell the outcome .Thus we know regression is what we must use for this data . Now we know that prices are to be predicted , hence we set labels (output) as price columns and we also convert dates to 1’s and 0’s so that it doesn’t influence our data much . We use 0 for houses which are new that is built after 2014 . I’ve made my train data as 90% and 10% of the data to be my test data , and randomized the splitting of data by using random_state. So now , we have train data , test data and labels for both let us fit our train and test data into linear regression model .
After filling the datas we can give our final prediction/tally.
