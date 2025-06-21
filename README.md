
<p align="center">
  <img src="https://media1.tenor.com/m/XOOmEJhESJEAAAAd/titanic-1953-titanic-retro-movie.gif" alt="Description" width="600" />
</p>  

# 🚢 Titanic – First ML Project
Starting point for almost everyone who ever tried Data Science — and it's also the first one for me.
The goal was to predict survival on the Titanic using supervised learning. I used **Python** in **Google Colab** and the following libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.
After performing EDA, I built a pipeline using `sklearn.pipeline` and performed hyperparameter tuning with `GridSearchCV`. I trained and compared several models:

- `SGDClassifier`
- `LogisticRegression`
- `KNeighborsClassifier`
- `RandomForestClassifier`
- `VotingClassifier` (ensemble)

📊 Final result:  
Model scored **0.78708** on Kaggle, placing **1407th out of 15,360** at the time of this writing.

🔗 Check it out on [Kaggle](https://www.kaggle.com/code/maximravichev/titanic-notebook)

