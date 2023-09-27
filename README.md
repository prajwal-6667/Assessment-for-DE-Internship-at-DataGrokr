# Real Estate Data Analysis Web Application

## Introduction

The Real Estate Data Analysis Web Application is a Flask-based web application designed to provide answers to various data analysis questions related to real estate properties. This project leverages Python, Flask, and data analysis techniques to create an interactive web interface for querying and visualizing real estate data.

## Features

- 10 data analysis questions with detailed answers.
- Interactive web interface with Bootstrap-based styling.
- Integration with Ngrok for exposing the web application publicly.
- Code snippets for data cleaning, SQL queries, and Flask routes.
- Easy-to-follow instructions for running the web application.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (version 3.x) installed on your system.
- Pip package manager installed.
- An Ngrok authentication token (for public internet access).

## Getting Started

Follow these steps to set up and run the Real Estate Data Analysis Web Application:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/real-estate-analysis.git
cd real-estate-analysis
```

### 2. Install Dependencies

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

### 3. Configure Ngrok

Obtain an Ngrok authentication token and set it in your code for public internet access. Replace `YOUR_NGROK_TOKEN` with your actual token:

```python
from pyngrok import ngrok
ngrok.set_auth_token("YOUR_NGROK_TOKEN")
```

### 4. Run the Flask Application

Start the Flask server locally:

```bash
python app.py
```

### 5. Access the Web Application

The web application will be accessible at `http://localhost:7700`.

### 6. Access Question Results

Questions and their respective results can be accessed by visiting the provided URLs:

- Question 1: [http://localhost:7700/question-1](http://localhost:7700/question-1)
- Question 2: [http://localhost:7700/question-2](http://localhost:7700/question-2)
- ...

## Code Structure

The project structure is organized as follows:

- `app.py`: The main Flask application.
- `templates/`: HTML templates used to render question results.
- `static/`: Static assets (e.g., CSS and JavaScript).
- `data/`: Data files used for analysis.
- `requirements.txt`: List of Python packages required for the project.

## Questions Answered

The web application provides answers to the following 10 data analysis questions:

1. Retrieve properties that have a price greater than 1 million and are located in "Estados Unidos" (l1).
2. Categorize properties based on their surface area.
3. List all properties in the 'Belgrano' neighborhood (l3) with the same number of bedrooms and bathrooms as another property.
4. Calculate the average price per square meter for each property type in the 'Belgrano' neighborhood.
5. Identify properties that have a higher price than the average price of properties with the same number of bedrooms and bathrooms.
6. Calculate the cumulative price for each property type, ordered by the creation date.
7. Identify the 10 locations with the highest total surface area of properties listed for sale.
8. Find the top 5 most expensive properties in the 'Palermo' neighborhood listed in August 2020.
9. Find the top 3 properties with the highest price per square meter within each property type.
10. Find the top 3 locations with the highest average price per square meter for properties listed for sale in the year 2020.
