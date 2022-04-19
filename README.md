# Store-Sales---Time-Series-Forecasting
This project predict sales for the thousands of product families sold at Favorita stores located in Ecuador. It is a competition hosted by Kaggle.
## Additional Notes
Wages in the public sector are paid every two weeks on the 15 th and on the last day of the month. Supermarket sales could be affected by this.
A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.
## Analysis
https://public.tableau.com/app/profile/shivani.singhal8462/viz/EcuadorFavoritaStores/EcuadorFavoritaStores?publish=yes

![Ecuador Favorita Stores](https://user-images.githubusercontent.com/76504592/162259938-b0c3f791-cf01-4ed2-ae4d-a19ce6c39836.png)

<img width="574" alt="image" src="https://user-images.githubusercontent.com/76504592/162763752-d7e90977-b38a-4305-9a06-cc007a36c953.png">

## Observations from transactions data set -

1. Transactions is highly correlated with sales.
2. The number of transactions increases every year in Decembor month.
3. The transactions increases at the end of week.

<img width="438" alt="image" src="https://user-images.githubusercontent.com/76504592/161805626-b80f94c7-cdae-4601-a4ca-2eb13ddcc858.png">

<img width="527" alt="image" src="https://user-images.githubusercontent.com/76504592/161806402-f38f26c7-4053-4d98-b5e6-cfb586277f05.png">


## Observations from oil data set -
Oil prices were high only in 2013 and 2014.
Oil prices were lowest in 2016 - the time when earthquake struck Ecuador on April 16,2016.

<img width="386" alt="image" src="https://user-images.githubusercontent.com/76504592/161274061-37c0b211-bcb9-4ce4-abe3-a200ff0c3ce1.png">

## Evaluation
The evaluation metric for Store Sales forecasting learning competition:
1𝑛∑𝑖=1𝑛(log(1+𝑦̂ 𝑖)−log(1+𝑦𝑖))2⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯
