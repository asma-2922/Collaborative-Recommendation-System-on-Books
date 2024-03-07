# RecSys Course Project - 2

- Contributors: [Preyali Dave](https://github.com/preyali), [Asama Narmawala](https://github.com/asma-2922), [Kirtan Soni](https://github.com/kir1906), [Krish Rupapara](https://github.com/KrishRupapara)
- Dataset :link:: [Librarything Data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#social_data)
- In this Project, we have used collaborative filtering approach to recommend books to the user from the Librarything dataset.
- 
**COLLABORATIVE FILTERING** : To address some of the limitations of content-based filtering, collaborative filtering uses similarities between users and items simultaneously to provide recommendations. This allows for serendipitous recommendations; that is, collaborative filtering models can recommend an item to user A based on the interests of a similar user B.
 
- We will be taking into use some of the collaborative featuring methods on the above dataset 
**DATA DESCRIPTION**

  **1.Comments**- The explict reviews given by users.
  
  **2.Work**- Item/ book ID numbers.
  
  **3.User**- names of the users. 
  
  **4.user_id**- UserID of the users/ customers.
  
  **5.Star**- Ratings given by users.
  
  There were a few more unsuable columns that was removed after preprocessing.
  

## Tasks

- <a href='#exploratory-data-analysis'>Exploratory Data Analysis</a>
- <a href='#data-preprocessing'>Data Preprocessing</a>
- <a href='#collaborative-filtering'>Collaborative Filtering</a>
- <a href='#results'>Results</a>

## Exploratory Data Analysis

-Exploratory Data Analysis (EDA) to gain insights into Rating characteristics.
-In EDA we provide data visualisation in different graph method like pair plot, cat plot, subplot, data distribution plot, pie chart, scatter plot. EDA summarize the main behaviour, features, and patterns in a dataset.
-Describing the relation between each other and making the observations.

## Data Preprocessing
-Data cleaning and preprocessing contains mainly segregation of values, dropping the unecessary values and columns to get a more sturctured and comphrendable data that is suitable for analysis and model training.
Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis.
This step involves several tasks, data transformation involves converting data into a different format or structure to meet the requirements of specific analysis techniques or machine learning algorithms.



## Collaborative Filtering
- In this section, we have mainly applied the collaborative filtering techniques for rating predictions of particular books as items and the corresponding users.
- The item-item and user-user matrix factorisation was applied as a part of model based filtering to form the user-item interaction matrix and then find the correlation and similarities.

## Results
