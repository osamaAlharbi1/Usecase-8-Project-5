# Hotel Clustering Prediction

The project aims to predict the quality of hotels based on their features. We started by collecting data from Wego using web scraping techniques, leveraging the Selenium library to fetch the necessary data.


the datasite
Title                       object
Rating                     float64
Price                       object
region                      object
Airport Shuttle              int64
Business Centre              int64
Facilities for Disabled      int64
Fitness Centre               int64
Restaurant                   int64
Room Service                 int64
Spa                          int64
Swimming Pool                int64
Wellness Centre              int64

Next, we cleaned the data using the 7-dimension method to ensure it was ready for analysis. We then visualized the data to gain a better understanding of the key features and relationships.

After gaining insights from the data, we moved on to feature engineering. In this stage, we developed custom scoring systems to better capture the nuances of hotel quality. For example, we created a Luxury_Score that combines weighted price, weighted rating, and premium amenities such as Spa, Wellness Centre, Swimming Pool, and Fitness Centre, with these amenities being weighted more heavily. Additionally, we designed a Satisfaction_Score that accounts for both customer ratings and essential service amenities like Room Service, Facilities for Disabled, and Airport Shuttle.

With our refined set of features, we began building our model. Since we aimed to use unsupervised machine learning, we explored various clustering algorithms. After fitting and testing several models, we evaluated their performance and selected the best one. The K-means clustering algorithm emerged as the top performer.

Finally, we deployed the model using FastAPI and Streamlit, with hosting provided by Render.

For more details, you can find the project in the repository.

### streamlit link : https://labtop-agijj3a5z83uoly3okkegk.streamlit.app/
### Presentation link : [Insert Presentation Link Here]


اسامه الحربي 
سامر غربي 
عبد العزيز الكثيري 
وديعه البحيري 