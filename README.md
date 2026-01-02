# Python-Networks
Introduction to Networks on Python

These is a short overview of Complex Networks on Python and a guide for 
beginners users to the basic steeps are needed when someone is dealing
with a network. 

In the main folder you can find the following jupyter notebooks:

Lecture 1

1) part_1_Networks_and_Python.ipynb
2) part_2_Real_World_Networks.ipynb

In the first part, we go through the basic operations that can be performed on a network,
as for example computing P(K) (degree distribution), C(k) (clustering coefficient),
L (average shot path) or comparing different scaling hypotheses.

In the second part, we compute some centrality measures (as for example the betweenness centrality)
on one of the most famous networks of the field: the Zachary's karate club. 
We  continue by giving an insight on community detection and we conclude by showing how
it is possible to export the analyzed network to other tools, as for example Gephi.


These Notebooks can not be used as a complete introduction to Networks on Python.
They can not be thought of as a compressive guide of the libraries used in the notebooks.

They are just a short overview, which should give to the reader a sense of what
can be done with Networks using python.

These Jupyter Notebooks were used during the class of Complex-Network at the CCNY:


Lecture 2

1) social_media_analysis_part1.ipynb 
3) social_media_analysis_part2.ipynb


These two notebooks guide us through different applications of neural networks in social media analysis:
understanding audience sentiment and engagement predictions.

In the first part, we focuses on using a neural network for **sentiment analysis**. We explore techniques
for preprocessing social media data, such as tokenization and vectorization, and train a neural network model
to classify the sentiment (e.g., positive, neutral, or negative) within posts. This helps us understand
audience emotions and feedback.

In the second part, we extend the analysis by training a neural network to **predict future interactions**
or engagement metrics based on past data. By leveraging previous post engagements, such as likes or comments, we develop a
model to forecast future trends, which can be applied to improve social media strategy and audience engagement predictions.

Lecture 3

ML_for_Election_Prediction.ipynb

In this notebook we analyze a Facebook dataset about the 2024 US elections (US_2024_800k.csv), where each row corresponds to a post with the following fields:

- `p_id`: post identifier  
- `conf`: confidence of the classifier  
- `class`: one of `['Neither', 'Anti-Kamala', 'Anti-Trump', 'Pro-Kamala', 'Pro-Trump']`  
- `statistics.like_count`: number of likes  
- `creation_time` / `date`: time of publication  
- `candidate_support`: aggregated candidate label (`Kamala`, `Trump`, or NaN for `Neither`)

We start by exploring basic statistics: number of posts and likes over time, class distribution, confidence distributions by class, and engagement patterns (total and average likes) across the different categories.

Next, we collapse the original labels into two camps (Kamala vs Trump), and compute:

- share of posts aligned with each candidate  
- share of likes aligned with each candidate  

We compare these quantities to external signals at the **national level**:

- pre-election national polling averages  
- the final 2024 popular vote

In the second part of the notebook, we focus on **time**. We study how the “prediction from likes” changes when we:

- use daily vs cumulative like share  
- apply moving averages with different window lengths  
- use expanding windows with **exponential decay**, controlled by a time scale τ

For each of these choices, we compare the resulting like-based prediction on the last day to the real election outcome, and visualize how the error depends on the window size and on τ.


##############################################################################################

In order to run the files .ipynb on your local machine you need to installed both python
(https://docs.conda.io/projects/conda/en/latest/user-guide/install/) and Jupyter notebook
(https://jupyter-notebook.readthedocs.io/en/stable/).

After downloading the jupyter files, you can open them simply by typing on your terminal:

jupyter notebook file_name.ipynb

See https://jupyter.readthedocs.io/en/latest/running.html
