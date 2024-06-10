The project is a comprehensive Streamlit application designed for property price prediction, analytics, and recommendation in Gurgaon, India.

1. Price Prediction Module: It leverages a Random Forest Regressor model, optimized with column transformers and hyperparameter tuning. This model, saved as a pickle pipeline, predicts property prices based on user inputs such as location, size, and amenities.

2. Analytics Module: It offers extensive data analysis and visualization capabilities. Users can explore interactive scatter maps, word clouds, sunburst charts, pie charts, scatter plots, boxplots, and distplots to understand property trends and distributions. Additionally, OLS regression analysis provides insights into the factors influencing property prices, helping users make informed decisions.

3. Recommender System: This module suggests properties to users based on cosine similarity, considering the weighted importance of features like location, price, and property type to enhance recommendation accuracy. 

The data for this project is meticulously sourced from 99acres.com through a custom web scraping script, ensuring the dataset is rich, up-to-date, and relevant. The app seamlessly integrates these functionalities, allowing users to predict prices, analyze market trends, and find suitable properties, all within a user-friendly interface. This makes it a powerful tool for both property buyers and sellers, providing valuable insights and personalized recommendations.
