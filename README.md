# Exploration of Heuristics in Information Retrieval in Applications of Approximate String Similarity

This was my final semester undergrad project. The report is [available here.](https://github.com/pranav-ust/ir-heuristics/blob/master/main.pdf) A part of this project resulted in [ACL paper](https://arxiv.org/abs/1811.08129)

## Abstract

Ranking functions used in information retrieval are primarily used in the search engines and they are often adopted for various language processing applications.
This project introduces some novel heuristics combined with probabilistic retrieval functions and are employed in the domain of approximate string similarity problem.
A lot of algorithms have been proposed in the literature to solve approximate string similarity problems, however none of them makes use of probabilistic retrieval functions.
We are the first to explore the intersection between these two areas and propose heuristic designs to resolve this problem.
First we propose chunking heuristic function, BREAK. 
We show the variants BREAK-1, 2, OFF which splits up the terms with the sequential notion.
Then we propose BREAK-n which generalizes these variants and scales to larger datasets.
In order to relate these split ups, we propose a graphical error modelling heuristics MAKE over the BREAK variants.
Finally, we propose TAKE curve, a novel feature engineering probabilistic distribution which replaces the prevalent normalization heuristics.
Taking the advantage of flexibility over the choice of heuristics, we assess the variants on the cognate detection, mutant identification, and isolated spelling correction based problems.
In the extensive evaluation methods, we found that our designs perform better than prevalent heuristics and are robust against database characteristics.

## Acknowledgements

Superb thanks to my thesis supervisor Prof. Rushi Kumar for helping me out. Thanks to NLP community for providing open-sourced datasets and resources to work on this project.
