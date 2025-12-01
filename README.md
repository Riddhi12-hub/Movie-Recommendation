# Movie Recommendation System

This project is a **simple, interactive, and visually appealing Movie Recommendation System** built using Python. It uses **movie genres and ratings** to recommend similar movies, making it beginner-friendly yet professional for resumes and portfolios.

---

## **Features**

1. **Popularity-Based Recommendation:**  
   Shows top-rated movies based on average user ratings.

2. **Content-Based Recommendation:**  
   Recommends movies similar to a selected movie using **genre similarity** (cosine similarity with bag-of-words).

3. **Interactive User Input:**  
   Users can input a movie they like and get personalized recommendations.

4. **Visualizations:**  
   - Most popular genres  
   - Top 10 movies by rating  
   - Ratings of recommended movies  
   - Popularity vs rating scatter plots  

5. **Clean & Resume-Friendly:**  
   - Step-by-step comments  
   - Clean and professional visualizations  
   - Easy to understand code

---

## **Dataset**

- **Movies Dataset (`movies.csv`)**: Contains `movieId`, `title`, and `genres`.  
- **Ratings Dataset (`ratings.csv`)**: Contains `userId`, `movieId`, `rating`, and `timestamp`.  

**Recommended Dataset:** [MovieLens ml-latest-small](https://files.grouplens.org/datasets/movielens/ml-latest-small-README.html)

---

## **Installation & Setup**

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `movies.csv` and `ratings.csv`.
3. Run the notebook `Movie_Recommendation_System.ipynb`.
4. Input a movie name to get recommendations and explore interactive plots.

---

## **Libraries Used**

- `pandas` → data manipulation  
- `numpy` → numerical operations  
- `matplotlib` & `seaborn` → data visualization  
- `sklearn` → content-based filtering (cosine similarity & CountVectorizer)  

---

## **Usage Example**

```python
Enter a movie you like: Toy Story (1995)
You might also like:
1. A Bug's Life (1998)
2. The Lion King (1994)
3. Aladdin (1992)
4. Beauty and the Beast (1991)
5. Monsters, Inc. (2001)

