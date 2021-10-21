---
layout: post
title:  "Random Forest"
date:   2021-10-18 15:58:02 +0530
categories: jekyll update
---

### AdaBoost
AddBoost:
- It is supervised learning algorithm, used to solve calssificaitn problem 
- Idea behind AddaBoost add more weight to miss calssifed entity and giv less weight correctly classifed ,
- In AddaBoost each observation  is classifed into Stump. Stump is nothing but a tree have only one root node and one 2 leafe node

Following are the algorithm steps:
1. Assign equal weight for each observation. 
 > $$ weight  $$
2

1. Train the decision stump on the initial dataset with no weights (the same as each element having weight = 1).

2. Update weights of all elements, using the formula from AdaBoost algorithm. Weights of correctly classified elements should become less, weights of incorrectly classified - larger.
3. Train the decision stump using the current weights. That is, minimize not just the number of mistakes made by this decision stump, but sum of the weights of the mistakes.
4. If the desired quality was not achieved, go to pt. 2.

**Reference**:

[Bagging and Boosting](https://stats.stackexchange.com/questions/18891/bagging-boosting-and-stacking-in-machine-learning)

[Adaboost](https://stackoverflow.com/questions/38829052/decision-trees-stumps-with-adaboost?rq=1)

[Why do we need XGBoost and Random Forest?](https://datascience.stackexchange.com/questions/23789/why-do-we-need-xgboost-and-random-forest/23913#23913)