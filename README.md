# Baking Personalization System

A hyper-personalization system for banking enthusiasts that provides personalized banking tips, and techniques using advanced AI models.

## Features

- Personalized banking product recommendations based on user preferences
- Banking technique suggestions
- Feedback based recommendation
- Interactive user interface

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## Project Structure

- `app.py`: Main Streamlit application
- `models/`: Directory for storing model files
- `data/`: Directory for storing recipe and user data
- `utils/`: Utility functions for data processing and model inference

## Technologies Used

- Streamlit for the web interface
- Hugging Face Transformers for natural language processing
- Sentence Transformers for semantic similarity
- Pandas and NumPy for data manipulation
- Scikit-learn for machine learning utilities 
