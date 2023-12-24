<h2> Delhi House Pricing Prediction </h2>

This repository showcases a web application designed to predict house prices in Delhi, incorporating a machine learning model and a Flask backend. The project utilizes a RandomForestRegressor algorithm trained on a dataset of Delhi house prices, providing users with an intuitive interface for predicting property values.

<b> Key Features: </b>

1. Web Interface:

- Developed an interactive and responsive web interface using HTML, CSS, and JavaScript.
- Utilized Bootstrap for styling to ensure a visually appealing and user-friendly layout.

2. Machine Learning Model:

- Trained a RandomForestRegressor model using scikit-learn on a dataset of Delhi house prices.
- Implemented data preprocessing techniques, including categorical encoding and outlier handling, to enhance model performance.

3. Flask Backend:

- Created a Flask server to handle incoming requests and seamlessly integrate the machine learning model for predictions.
- Established routes for rendering the home page and handling predictions based on user input.

4. Data Handling:

- Employed LabelEncoder for encoding categorical features, improving the model's ability to interpret location data.
- Conducted comprehensive data preparation, including log-transformations, to ensure robust model performance.

<b> Usage: </b>

- Users input location, area, number of bedrooms, and toggle various amenities on the web page.
- Upon form submission, JavaScript sends the data to the Flask server (/predict).
- The Flask server uses the pre-trained ML model to predict the house price and returns the result.
- The predicted price is displayed on the web page.

<h2> Referential Screenshot </h2>

<img alt="Screenshit" src="https://github.com/namangaur628/Delhi-Property-Price-Prediction/assets/114846431/f36eceac-5919-48f2-b91b-3ae5a3c7b462">

