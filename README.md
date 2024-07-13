# Movie Recommendation System

## Overview

The Movie Recommendation System is a web application designed to help users find movies tailored to their preferences. This project leverages the Gemini API, LangChain for language processing, and Streamlit for creating an interactive user interface. Additionally, ngrok is used to provide secure tunnels to the Streamlit web server, making the application accessible over the internet.

## Features

- **Movie Recommendations**: Users can input their preferences and receive tailored movie suggestions.
- **Real-time Query Processing**: Utilizes the Gemini API via LangChain to process user queries and provide instant recommendations.
- **Interactive UI**: Built with Streamlit to offer a user-friendly and interactive interface.

## Installation

To install and set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Lbp2563/Movie-Recommendation-System_Gemini_LangChain.git
   cd movie-recommendation-system
2.
   Install the required dependencies using pip install -r requirements.txt
3. Set up environment variables:
   GOOGLE_API_KEY=your_google_api_key
4. Set up ngrok:
   ngrok authtoken your_ngrok_authtoken

## Usage

**streamlit run app.py**
**ngrok http 8501**

Use the URL provided by ngrok to access the Streamlit app in your browser
