# Movie Recommender System

The Movie Recommender System is a Python-based web application built using Streamlit and integrated with The Movie Database (TMDb) API. This system offers users personalized movie recommendations based on their input of a selected movie title. Leveraging cosine similarity, it compares the selected movie with a database of films to suggest similar ones, enhancing users' movie-watching experiences by introducing them to relevant content they might enjoy.

## Project Overview

The project revolves around the development of a user-friendly interface that allows users to input their preferred movie title and receive recommendations for similar movies. The recommendations are generated through the following steps:

1. **Data Retrieval**: The system fetches movie data from the TMDb API, including movie titles, poster images, and other relevant information.

2. **Similarity Calculation**: A precomputed similarity matrix is utilized to determine the similarity between the selected movie and other movies in the database. Cosine similarity is employed as the metric for comparison.

3. **Recommendation Display**: The system displays a list of recommended movies along with their respective poster images, providing users with visually appealing suggestions.

## Key Features

- **Interactive Interface**: The user interface is designed to be intuitive and easy to navigate, allowing users to quickly input their movie preferences and view recommendations.
  
- **Dynamic Recommendations**: Recommendations are dynamically generated based on the selected movie, ensuring that users receive relevant and up-to-date suggestions.
  
- **Poster Display**: The system enhances the user experience by displaying movie posters alongside the recommended titles, enabling users to visually explore their options.

## Usage

To use the Movie Recommender System:

1. Clone the repository to your local machine.

2. Navigate to the project directory and install the required dependencies using `pip install -r requirements.txt`.

3. Run the Streamlit app using `streamlit run app.py`.

4. Open your web browser and access the provided URL to interact with the application.

5. Select a movie from the dropdown menu, click the "Show Recommendation" button, and explore the recommended movies displayed on the screen.

## Future Enhancements

- **User Authentication**: Implement user authentication to allow users to save their preferences and receive personalized recommendations.
  
- **Improved Recommendation Algorithm**: Explore advanced recommendation algorithms to enhance the accuracy and relevance of movie recommendations.
  
- **Enhanced User Interface**: Continuously improve the user interface to provide a seamless and visually appealing experience for users.


## Installation

To use this project, you'll need to follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/movie-recommender.git
   ```

2. Navigate to the project directory:

   ```bash
   cd movie-recommender
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```


To run the movie recommender system:

1. Ensure you're in the project directory.

2. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

3. Open your web browser and go to the URL provided by Streamlit to interact with the app.

4. Select a movie from the dropdown menu and click the "Show Recommendation" button to see similar movie recommendations.

## Dependencies

The following dependencies are required to run this project:

- Streamlit
- Requests

These dependencies are automatically installed when running `pip install -r requirements.txt`.

## Credits

- **Data Source**: This project uses data from [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api).
- **Similarity Calculation**: The similarity between movies is computed using cosine similarity.
- **Poster Images**: Movie posters are fetched from TMDb API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
