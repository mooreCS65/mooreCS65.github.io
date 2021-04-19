---
layout: default
title: Introduction to Machine Learning
markdown: kramdown
permalink: /intro2ML/
---

# Introduction to Machine Learning

[Slides](https://docs.google.com/presentation/d/1F5BRlNr6tW1SfAwn-zhKSfE5s-Y1r1Olx50ZYldFa8Y/edit?usp=sharing){:target="_blank" rel="noopener"} \| 
Video \| Code

## Table of Contents:
- [What is Machine Learning?](##What-is-Machine-Learning) <br>
  - [Two approaches to Intelligence](###Two-approaches-to-Intelligence)<br>
    - [The Artificial Intelligence Approach](####The-Artificial-Intelligence-Approach) <br>
    - [The Machine Learning Approach](####The-Machine-Learning-Approach) <br>

## What is Machine Learning?

A sub-discipline of Artificial Intelligence.
- **Definition \#1**: creating machines (e.g., computer programs) that improve automatically with experience
- **Definition \#2**: the field of study that gives computers the ability to learn without being explicitly programmed.

### Two approaches to Intelligence:
Let's talk about programming a computer to play chess. There are two main approaches the classic **artificial intelligence** 
approach and the **machine learning** approach. 

#### The Artificial Intelligence Approach:
Develop a heuristic (some sort of way to tell the value of a given piece)... let's say:


| Piece  | Points |
|--------|--------|
| Queen  | 12     |
| Rook   | 8      |
| Bishop | 7      |
| Knight | 7      |
| Pawn   | 1      |

An artificial intelligence approach would, for any configuration of a chess board:
- establish valid moves
- **search** all possible moves in the future
- **select** te move that maximizes the possible points. 

#### A Machine Learning Approach:
In contrast to the **artificial intelligence** approach, a **machine learning** approach would be based on data. The idea would be to 
gather a bunch of chess game examples and for any configuation:
- examine the database of moves of winning games
- find the board configuration that is the 'closest' and make the appropriate move that previously led to winning. 

So, the main idea is that often times **artificial intelligence** refers to rule and heuristic based appraoches to solving problems, while
**machine learning** approaches refer to utilizing data from previous occurences to predict what the best approach would be. 
