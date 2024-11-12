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

##############################################################################################

In order to run the files .ipynb on your local machine you need to installed both python
(https://docs.conda.io/projects/conda/en/latest/user-guide/install/) and Jupyter notebook
(https://jupyter-notebook.readthedocs.io/en/stable/).

After downloading the jupyter files, you can open them simply by typing on your terminal:

jupyter notebook file_name.ipynb

See https://jupyter.readthedocs.io/en/latest/running.html
