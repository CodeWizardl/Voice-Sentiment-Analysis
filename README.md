# Sentiment Analysis of Call Recording

This project is designed to perform sentiment analysis on incoming calls to a helpdesk using a sentiment analysis model. The sentiment analysis model is powered by the [AssemblyAI](https://www.assemblyai.com/) API. The goal is to analyze the emotional tone of the calls and gain insights into the overall sentiment of the interactions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Introduction

Describe the purpose and scope of your project. Include any relevant background information, such as the motivation behind creating the sentiment analysis model for helpdesk call recordings. Highlight that the sentiment analysis model is powered by the AssemblyAI API.

## Features

- **Sentiment Analysis:** The project leverages a sentiment analysis model powered by the [AssemblyAI](https://www.assemblyai.com/) API to determine the emotional tone of incoming calls.
- **User Interface:** Utilizes Streamlit to provide a user-friendly interface for running the analysis.
- **Insights:** Gain insights into the overall sentiment trends over time.

## Installation

To set up the project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. Install the required dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

**Note:** Make sure you have Python 3.7 installed on your system.

## Usage

To use the application for sentiment analysis on call recordings, follow these steps:

1. Ensure that you have obtained an API key from [AssemblyAI](https://www.assemblyai.com/) for sentiment analysis.

2. Update the configuration with your AssemblyAI API key.

3. Run the application using Streamlit:

    ```bash
    streamlit run app.py
    ```

4. Access the application in your web browser by navigating to the provided local address (usually http://localhost:8501).

5. Explore the user interface to perform sentiment analysis on incoming calls and gain insights into emotional tones.

**Note:** This project relies on the AssemblyAI API for sentiment analysis. Ensure that you have a valid API key and update the configuration accordingly for seamless functionality.

## Conclusion
- In conclusion, leveraging the AssemblyAI API for sentiment analysis enhances this project's capability to analyze emotional tones in helpdesk calls. By harnessing this advanced model, the project strives to provide valuable insights into overall sentiment, offering a nuanced understanding of interactions and facilitating informed decision-making for improved customer support experiences.