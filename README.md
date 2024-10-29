
# SPAM Deactivate

## Overview

The Spam Detection Web Application is designed to classify emails as spam or not spam using a Naive Bayes classifier. The application leverages Flask for the web framework, Scikit-learn for machine learning, and Bootstrap for responsive design. Users can input their emails, and the application will return a prediction along with visual feedback.

## Features
- User-friendly interface for email input.
- Real-time spam classification using a Naive Bayes model.
- Visual feedback on spam detection results.
- Responsive design powered by Bootstrap.
## Requirements
- Python 3.x
- Flask
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-detection-app.git
   cd spam-detection-app
2. Install the required Python packages:
   ```bash
    pip install Flask scikit-learn pandas numpy matplotlib seaborn
3. Download or prepare a dataset in CSV format containing email texts and     their labels (spam or not spam) and save it as emails.csv
4. Train the model (if not already provided):
   
  - Ensure that the dataset is loaded and the model is trained in the app.py file.
- Save the trained model as model.pkl using pickle.
  
##  Usage
 1. Run the application:
    ```bash
    python app.py
2. Open your web browser and navigate to http://127.0.0.1:5000/ :


## Demo
<h3>Landing page</h3>
![Home](https://github.com/user-attachments/assets/2759415c-872b-48ee-aff5-6efc7593c62c)

