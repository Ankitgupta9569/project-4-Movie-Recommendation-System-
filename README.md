# Movie Recommendation System

![Movie Recommendation](images/project3.jpg)

## 🎬 Overview

The **Movie Recommendation System** project uses machine learning algorithms to recommend movies based on user preferences and past behavior. By analyzing a user's watch history, ratings, and similar user profiles, the system suggests movies that they are likely to enjoy. This project leverages collaborative filtering, content-based filtering, and hybrid recommendation techniques.

## ⚙️ Technologies Used
- **Python** 🐍
- **Machine Learning** 🤖
- **Pandas** 📊
- **NumPy** 🔢
- **Scikit-learn** 🧠
- **Surprise Library** 🎁
- **Matplotlib** 📉
- **Flask** 🚀 (for web application)

## 🔍 Problem Statement

With an ever-expanding number of movies available on streaming platforms, users often struggle to find movies they will enjoy. A recommendation system helps users discover movies based on their preferences, ratings, and viewing history, improving their experience by providing personalized suggestions.

## 💡 Solution

We designed a recommendation engine using the following approaches:
- **Collaborative Filtering**: Uses user-item interactions to find similarities between users and suggest items liked by similar users.
- **Content-Based Filtering**: Analyzes movie features like genre, director, and cast to recommend similar movies.
- **Hybrid Model**: Combines both approaches for better accuracy.

### Example Flow:
1. User ratings are collected.
2. Data is processed using collaborative and content-based algorithms.
3. The system generates a list of recommended movies based on the user's interests.

## 📊 Dataset

The project uses the **MovieLens Dataset**, a popular dataset for building recommendation systems, which contains millions of movie ratings and metadata.

- **Dataset Size**: 20 million ratings from 138,000 users on 27,000 movies.
- **Features**: Movie ID, User ID, Rating, Genre, Title, etc.

## 🔧 Steps to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/ankitgupta9569/movie-recommendation-system.git
    ```
2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the script to train the recommendation model:
    ```bash
    python train_model.py
    ```
4. To get movie recommendations for a user:
    ```bash
    python recommend_movies.py
    ```
5. (Optional) Run the Flask web application:
    ```bash
    python app.py
    ```

## 🎯 Results

- **Accuracy**: Achieved a high **RMSE** (Root Mean Squared Error) for model evaluation, indicating the model's strong predictive capabilities.
- **Recommendation Quality**: The hybrid model provides diverse and relevant recommendations based on user preferences.
  
Example:
- **Top Recommended Movies for User X**:
    1. **The Dark Knight**
    2. **Inception**
    3. **Forrest Gump**
    4. **The Matrix**
    5. **Interstellar**

## 📈 Visualizations

- **Rating Distribution** 🎯
- **Recommendation Accuracy** 📊
- **User-Item Interaction Matrix** 🧩
- **Top Rated Movies by Genre** 🎥

## 💬 Discussion

This project successfully uses various techniques to recommend movies. While the hybrid model provides good recommendations, further improvements can be made by incorporating additional features like:
- **User demographics** (e.g., age, location).
- **Temporal dynamics** (e.g., time of the day/week/month preferences).
  
## 🚀 Future Enhancements

- Implementing **Deep Learning** models for better recommendations.
- Using **Reinforcement Learning** for dynamic recommendations based on real-time user feedback.
- Integrating with real-world APIs (e.g., IMDb, TMDb) to enhance movie metadata.

## 🌐 View the Project on GitHub

[Click here to view the code on GitHub](https://github.com/ankitgupta9569/movie-recommendation-system)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 📝 Author
**Ankit Gupta**  
[LinkedIn](https://www.linkedin.com/in/ankitgupta2026) | [GitHub](https://github.com/ankitgupta9569)
