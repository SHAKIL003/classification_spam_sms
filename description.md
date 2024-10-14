# Spam SMS Classification using Multinomial Naive Bayes Classifier

This project focuses on building a machine learning model to classify SMS messages as spam or ham (non-spam).

## App Development in Streamlit

The app provides an interactive interface to input SMS text and get predictions on whether it's spam or not. Developed using the Streamlit framework, it’s user-friendly and efficient.

### Features
- **Real-time Predictions**: Input any SMS text and receive instant classification results.
- **Model Used**: Utilizes the Multinomial Naive Bayes algorithm for accurate spam detection.
- **User Interface**: Built with Streamlit for a seamless and interactive user experience.

## Deployment on Heroku

The application is deployed on Heroku, making it accessible to users anywhere without the need for local setup.

### Steps for Deployment
1. **Prepare the App**: Ensure all necessary files, including `requirements.txt` and `Procfile`, are ready.
2. **Create Heroku App**: Set up a new application on Heroku.
3. **Deploy**: Push the code to Heroku and let it handle the deployment process.

## How to Run Locally
1. **Clone the Repository**: 
    ```shell
    git clone [your-repo-url]
    ```
2. **Set Up Virtual Environment**: 
    ```shell
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```
3. **Install Dependencies**: 
    ```shell
    pip install -r requirements.txt
    ```
4. **Run the App**: 
    ```shell
    streamlit run app.py
    ```

## Requirements
- Python
- Streamlit
- Scikit-learn
- Pandas
- Numpy


