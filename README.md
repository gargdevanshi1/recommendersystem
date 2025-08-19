# Recommender System

A small collection of assignment and homework scripts for CSE 258 (Recommender Systems). This repository contains code for toy recommendation and prediction tasks used in coursework.

## Repository structure

- [Book review prediction/assignment1.py](Book review prediction/assignment1.py)  
  - Key symbols: [`Popular`](Book review prediction/assignment1.py), [`cp_similarity`](Book review prediction/assignment1.py), [`Jaccard`](Book review prediction/assignment1.py), [`getSimilarities`](Book review prediction/assignment1.py), [`feat`](Book review prediction/assignment1.py), and [`svd_model`](Book review prediction/assignment1.py).
- [Clothing recommendation/cse258r_assignment2.pdf](Clothing recommendation/cse258r_assignment2.pdf) — assignment spec (PDF).
- Misc recommenders/  
  - [Misc recommenders/homework1.py](Misc recommenders/homework1.py) — regression & classification exercises (key symbols: [`feature1`](Misc recommenders/homework1.py), [`feature2`](Misc recommenders/homework1.py), [`feature3`](Misc recommenders/homework1.py)).
  - [Misc recommenders/homework2.py](Misc recommenders/homework2.py) — model pipelines and basic recommender implementations (key symbols: [`Jaccard`](Misc recommenders/homework2.py), [`mostSimilar`](Misc recommenders/homework2.py), [`predict_rating_item`](Misc recommenders/homework2.py), [`predict_rating_user`](Misc recommenders/homework2.py)).
  - [Misc recommenders/homework3.py](Misc recommenders/homework3.py) — baseline recommenders, feature pipelines, and matrix-factorization experiments (key symbols: [`Baseline`](Misc recommenders/homework3.py), [`compute_max_jaccard`](Misc recommenders/homework3.py), [`feat`](Misc recommenders/homework3.py), [`gradient_descent`](Misc recommenders/homework3.py), `answers`).

## Purpose

These scripts implement:
- simple popularity and similarity-based read-prediction models,
- logistic regression pipelines for binary classification,
- k-NN / Jaccard-based item/user collaborative filtering,
- baseline bias models and rudimentary matrix factorization (SVD via the Surprise library),
- utilities for generating submission CSVs for read and rating prediction tasks.
