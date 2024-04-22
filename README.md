---
title: Fastapisentimental
emoji: 🌖
colorFrom: gray
colorTo: purple
sdk: streamlit
sdk_version: 1.33.0
app_file: app.py
pinned: false
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
# Sentiment Analysis Model with Streamlit

This project implements a sentiment analysis model using Streamlit for the user interface.

## Files

- `app.py`: Python script containing the Streamlit application code for the sentiment analysis model.
- `sentiment_analysis.pkl`: Pickle file containing the trained sentiment analysis model.
- `Dockerfile`: Dockerfile for containerizing the application.
- `requirements.txt`: File listing the Python dependencies required for the application.

## Installation

To run the application locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Change into the project directory:

    ```bash
    cd your-repository
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

## Usage

1. Once the application is running, you can access it in your web browser.
2. Enter a review in the provided text input field.
3. Click the "Predict" button to see the sentiment prediction for the entered review.

## Docker

Alternatively, you can run the application using Docker. Make sure Docker is installed on your system.

1. Build the Docker image:

    ```bash
    docker build -t sentiment-analysis-app .
    ```

2. Run the Docker container:

    ```bash
    docker run -p 80:80 sentiment-analysis-app
    ```

## About

This project demonstrates how to deploy a sentiment analysis model with Streamlit and Docker.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

