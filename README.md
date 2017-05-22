Collaborative filtering for recommendation systems in Python
============================================================



Rating prediction algorithms
----------------------------


Surprise
--------

- Why / goal: needed for my PhD, no library at the time
- Why not scikit learn: rating prediction /= classif or regression
- Tuto: k-NN algorithm (With Notebook)
  - Basic class (trainset, prediction)
  - How to evaluate? RMSE, cross validation
  - split() and folds(), then final script
- What it does
  - Easy to implement algorithms
  - Built-in Algortihms (Some are cythonized)
  - Dataset handling
  - Automatic cross validation
  - Grid Search
  - Interface with pandas, serialization
  - Really tried to make a good doc, without hiding anything. Kept code simple.
- What's to follow:
  - implicit feedback algorithms
  - (Feel free to contribute!)

- Pobably mostly a tool for researchers / students. Not really suited for
  'real' recommendation problems. See LightFM, mrec or Mangaki


