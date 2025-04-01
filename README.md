
![stars-movies-1200x670-1-1024x572](https://github.com/user-attachments/assets/7f8450ad-bc3f-422c-b701-a789e7ff2268)



# Movie Recommendation System

## Overview
This project is a machine learning-based movie recommendation system that suggests movies to users based on their preferences. The system utilizes collaborative filtering and content-based filtering techniques to generate personalized recommendations.

## Features
- **User-Based and Item-Based Collaborative Filtering**: Recommends movies based on user behavior and interactions.
- **Content-Based Filtering**: Suggests movies similar to a given movie based on metadata like genre, director, and cast.
- **Hybrid Model**: Combines collaborative and content-based approaches for improved recommendations.
- **Interactive Interface**: Users can input their favorite movies and receive recommendations.

## Dataset
The recommendation system is trained on a dataset containing:
- Movie titles, genres, and descriptions
- User ratings and interactions
- Cast, crew, and other metadata

## Technologies Used
- **Python**
- **Pandas & NumPy** (Data processing)
- **Scikit-learn** (Machine learning models)
- **NLTK** (Text processing for metadata analysis)
- **Streamlit** (For building an interactive web app)

## Installation
To set up and run the project, follow these steps:
```bash
# Clone the repository
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

## Usage
1. Run the Streamlit app using the above command.
2. Enter the name of a movie or select user preferences.
3. View the recommended movies and explore further suggestions.

## Future Enhancements
- Integrating deep learning models for better recommendations
- Adding user authentication for personalized experiences
- Incorporating real-time streaming data

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

Download the 'Movie' data -> https://drive.google.com/file/d/1v8EJevZpV6j1-z6BFxjIGlNSoyeyjmjZ/view?usp=drive_link
