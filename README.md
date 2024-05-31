# MovieMetrix

MovieMetrix is a personalized movie recommendation system built using Streamlit. The application leverages natural language processing (NLP) techniques and machine learning to provide tailored movie recommendations based on user preferences and moods.

## Features

- **Personalized Recommendations**: Input your movie preferences and get a list of recommended movies based on cosine similarity.
- **Mood-Based Recommendations**: Enter your current mood to receive movie recommendations that match your sentiment using TextBlob sentiment analysis.
- **Filter Movies**: Filter movies by director, actor, or genre for more targeted recommendations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MovieMetrix.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MovieMetrix
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

## Usage

1. Ensure the `Net.csv` file containing movie data is in the project directory.
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
3. Use the sidebar to navigate between personalized recommendations, mood-based recommendations, and filtering options.
4. Enter your preferences or mood and get instant movie recommendations!

## Project Structure

- `app.py`: The main application file.
- `Net.csv`: The dataset containing movie information.
- `requirements.txt`: A file listing the required Python packages.

## Technologies Used

- **Streamlit** for building the web application
- **Pandas** for data manipulation
- **scikit-learn** for vectorization and similarity calculations
- **TextBlob** for sentiment analysis
- **NLTK** for text preprocessing

## Screenshots

![Home Page](screenshots/home.jpg)
![Personalized Recommendations](screenshots/recommendations.jpg)
![Mood-Based Recommendations](screenshots/mood_recommendations.jpg)
![Filteration](screenshots/filteration.jpg)


