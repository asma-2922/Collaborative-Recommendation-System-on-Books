# RecSys Course Project - 2

- Contributors: [Preyali Dave](https://github.com/preyali), [Asma Narmawala](https://github.com/asma-2922), [Kirtan Soni](https://github.com/kir1906), [Krish Rupapara](https://github.com/KrishRupapara)
- Dataset :link:: [Librarything Data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#social_data)
- In this Project, we have used collaborative filtering approach to recommend books to the user from the Librarything dataset.
  
**COLLABORATIVE FILTERING** : To address some of the limitations of content-based filtering, collaborative filtering uses similarities between users and items simultaneously to provide recommendations. This allows for serendipitous recommendations; that is, collaborative filtering models can recommend an item to user A based on the interests of a similar user B.
  
**Description of the dataset**

>* comment: The review or comment left by the user. 
>* nhelpful: The number of helpful votes received for the review.
>* unixtime: A timestamp indicating when the review was posted.
>* work: An identifier for the work being reviewed.
>* user: Name of the user who wrote the review.
>* stars: A numerical value representing the rating given in the review, on a scale of 0 to 5. 
>* time: The date when the review was posted.
>* user_id - An identifier of the user who wrote the review.
  

## Tasks

- <a href='#exploratory-data-analysis'>Exploratory Data Analysis</a>
- <a href='#data-preprocessing'>Data Preprocessing</a>
- <a href='#collaborative-filtering'>Collaborative Filtering</a>
- <a href='#results'>Results</a>
- <a href='#novelty'>Novelty</a>


## Exploratory Data Analysis

- Exploratory Data Analysis (EDA) to gain insights into Rating characteristics.
- In EDA we provide data visualisation in different graph method like scatter plot, density plot and heatmap. EDA summarize the main behaviour, features, and patterns in a dataset.
- Describing the relation between each other and making the observations.

## Data Preprocessing
- Data cleaning and preprocessing contains mainly segregation of values, dropping the unecessary values and columns to get a more sturctured and comphrendable data that is suitable for analysis and model training. Also converted the text file to csv for better usage.
Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis.
This step involves several tasks, data transformation involves converting data into a different format or structure to meet the requirements of specific analysis techniques or machine learning algorithms.



## Collaborative Filtering
- In this section, we have mainly applied the collaborative filtering techniques for rating predictions of particular books as items and the corresponding users.
- We have made use of both memory and model based approach to do the rating predictions.
- The item-item and user-user matrix factorisation was applied to form the user-item interaction matrix and then find the correlation and similarities.
- The traditional collaborative filtering approach solely focuses on improving accuracy of the rating without considering user satisfaction. If most accurate result predicts similar items, then it may not be very well for user satisfaction. So to tackle that problem, we implemented a diversity aware recommendation model, which can improve overall diversity of the recommended items while taking consideration of accuracy.
  

## Results
- The user-user matrix approach gave the MSE = 0.75.
- The item-item matrix approach gave the MSE = 0.55.
- Memorization Approach it is not possible to capture relationship between more than one also not able to detect similar (exact) item and that can affect user's rating. We had very sparse data so in avg user have given only to 20 item and we had 0.16 million items so if item is new then that rating can we counted from single or biased rating.

# Novelty
- We have implemented the Recommendation system for books on Tkinter.
- Performed Webscrapping to extract book names from Book id (work).
- Performed Matrix Factorization using neural network. 
