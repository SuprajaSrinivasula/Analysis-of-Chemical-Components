# Analysis-of-Chemical-Components
This project develops a content-based recommendation system for cosmetic products using chemical ingredient analysis. It helps consumers—especially those with sensitive skin—choose products by understanding ingredient similarities rather than relying on trial and error.

Overview

Dataset: 1,472 cosmetic products from Sephora (name, ingredients, category, skin type compatibility).

Goal: Recommend alternative products with similar chemical compositions for safer, cost-effective, and informed purchases.

Approach:

Data Preprocessing: Clean & tokenize ingredient lists.

Feature Encoding: Convert ingredients to vectors using One-Hot Encoding or word embedding.

Dimensionality Reduction: Apply t-SNE to project high-dimensional ingredient vectors into 2D space.

Visualization: Use Bokeh to create interactive plots for exploring product clusters.

Recommendation: Suggest similar products based on ingredient proximity in the embedding space.

Tech Stack

Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Bokeh, Matplotlib.

ML Techniques: Word Embedding, One-Hot Encoding, t-SNE.

Visualization: Interactive 2D ingredient similarity maps.

Key Features

Interactive product exploration with hover tooltips (name, brand, price, rating).

Ingredient-based similarity comparison between products.

Filtering by category and skin type.

Identifies cheaper or better-rated alternatives with similar formulations.

Future Scope

Personalized recommendations based on individual skin profiles.

Integration of ingredient safety ratings & allergen alerts.

Incorporating product reviews using NLP.

Mobile/web app for real-time recommendations.
