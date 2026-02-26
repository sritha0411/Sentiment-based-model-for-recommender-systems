# Sentiment-based-model-for-recommender-systems
**YouTube Sentiment Analysis & Recommender System 📊🎬**
This project is a web-based application designed to extract and analyze sentiments from YouTube comments. By leveraging a CNN (Convolutional Neural Network) model, it classifies user feedback to provide data-driven insights and personalized video recommendations.

🚀 Features
User Authentication: Secure sign-up and login system.

Data Processing: Tools to load and preprocess datasets for training.

Deep Learning Analysis: Uses a CNN model to predict sentiments (Positive, Neutral, Negative).

Batch Analysis: Upload CSV files of comments for bulk sentiment prediction.

Single Comment Prediction: Real-time sentiment analysis for individual text inputs.

Recommendation Engine: Suggests related videos based on the analyzed sentiment patterns.

Data Visualization: Generates graphical representations (pie charts) of sentiment distribution.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript (Django Templates)

Backend: Django (Python Framework)

Database: MySQL (managed via SQLyog/WampServer)

Machine Learning: TensorFlow / Keras (CNN Algorithm)

Tools: WampServer, SQLyog, Anaconda/Python Terminal

📂 Project Structure
Plaintext
YouTubeSentiments/
├── Dataset/             # CSV files for training and testing
├── model/               # Saved CNN model files
├── SentimentApp/        # Django application logic
├── Sentiment/           # Project configuration settings
├── DB/                  # SQL scripts for database setup
└── manage.py            # Django entry point

⚙️ Installation & Setup
Database Setup:

Open WampServer and ensure MySQL is running.

Use SQLyog to import the database script found in the DB/ folder.

Environment Configuration:

Ensure you have Python and Django installed.

Install dependencies: pip install tensorflow django pymysql pandas matplotlib

Run the Application:

Bash
python manage.py runserver
Access the Site:
Open your browser and go to http://127.0.0.1:8000/

📊 How it Works
Train the Model: Load the dataset and run the CNN training module to establish prediction accuracy.

Input Data: Either type a single comment or upload a .csv file containing multiple YouTube comments.

Analysis: The system processes the text and displays a sentiment score and classification.

Recommendation: Based on the sentiment, the system provides a list of recommended Video IDs to improve user engagement.
