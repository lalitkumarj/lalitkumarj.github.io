---
layout: default
title: MKTG 596. PhD Seminar in Machine Learning. Adaptive Experimentation in Practice
aed: active
description: AED Course Description
---
# MKTG 596: Adaptive Experimentation in Practice

This course is about the algorithms and techniques that drive experimentation in online platforms. At many firms, thousands of experiments are run daily to gather the vast amount of data needed to enable data-driven decision making. For any one of these experiments, an experimenter faces the challenge of deciding what data to collect, how long to run the experiment, and how to glean insights from the data collected. As a result, there is an increased demand by practitioners for methods and algorithms that deliver statistically sound results faster and with less opportunity cost. This course develops a modern toolbox of experimentation, with a focus on *adaptive experimental design*. Rooted in classical statistical and machine learning techniques, AED decides what future data to collect based on past measurements in a closed loop. Due to both theoretical gains and empirical success, AED has quickly become one of the most commonly employed algorithmic paradigms in practice with a promise of cutting experimentation time by up to half. However, practitioners who employ AED blindly can easily bias their results, or potentially not collect the data needed to make any useful inferences.  

Students who take this course will learn how to a) design choose and develop adaptive experiments in practice, b) analyze the data coming from these experiments, c) conduct research in cutting-edge directions in AED.

Topics include:

- Sequential Experimentation
- Multi-armed and Contextual Bandits
- Interference in Experiments
- Multiple Hypothesis Testing
- Off-Policy Evaluation
- Orthogonal/Double Machine Learning
- Reinforcement Learning

Class sessions will be a mix of lecture and discussion of papers. There will be homeworks focused on implementing algorithms.

**Class Session: MW 1-2:30, Paccar Hall 490**

Class website: lalitjain.com/aed
MyPlan link:  https://myplan.uw.edu/course/#/courses/MKTG596

Class Notes: [Link](https://github.com/lalitkumarj/AEDClassNotes/raw/main/main.pdf)

**Homeworks**
All homeworks should be completed in groups. You have 3 weeks to complete each homework. No late assignment will be accepted without prior consent from the Professor. 

- Homework 1: Due at midnight May 8th. [Link](https://github.com/lalitkumarj/AEDClassNotes/raw/main/hw1.pdf)
- Homework 2: Due at midnight June 4th. [Link](https://github.com/lalitkumarj/AEDClassNotes/raw/main/hw2.pdf), [Associated Jupyter Notebook](https://github.com/lalitkumarj/AEDClassNotes/raw/main/HW2.ipynb)

**Projects**
Project drafts are due June 1st. Final versions are due June 9th. All projects should
- Be 10-12 pages not including references (I recommend the Neurips Template files [here](https://nips.cc/Conferences/2020/PaperInformation/StyleFiles))
- Have a summary abstract.
- Have a problem statement and motivation. 
- Have a thorough discussion of related works and background material.
- Include major results/algorithms.
- Have empirical evaluations.
- Propose a new problem. 
Merely summarizing papers will be unacceptable. I expect a narrative that ties existing works together.

<style>
.tablelines table, .tablelines td, .tablelines th {
        border: 1px solid black;
        }
</style>

| Date | Lecture | Topics | Resources |
| --- | --- | --- | --- |
| Mar 27  | Pillar 1                         | A/B Testing, Lower bounds, SPRT |  [Sequential Analysis](https://orbiscascade-washington.primo.exlibrisgroup.com/permalink/01ALLIANCE_UW/1juclfo/alma99153869880001452)|
| :------:| :-------:|
| Mar 29  | Pillar 2                         | Multi-armed bandits             |  
| :------:| :-------:|
| Apr 3   | Pillar 2 Continued               | Multi-Armed Bandits             | [Bandit Algorithms](https://tor-lattimore.com/downloads/book/book.pdf) |
| :------:| :-------:|
| Apr 5   | Pillar 3                         | Martingales, MSPRT              | [Peeking at A/B Tests](http://library.usc.edu.ph/ACM/KKD%202017/pdfs/p1517.pdf), [Time-uniform Chernoff bounds via nonnegative supermartingales](https://arxiv.org/pdf/1810.08240.pdf), 
| :------:| :-------:|
| Apr 10  | Pillar 3 Continued               |Anytime Confidence Intervals/Least Squares       |  [Spotify Blog Post](https://engineering.atspotify.com/2023/03/choosing-sequential-testing-framework-comparisons-and-discussions/)
| :------:| :-------:|
| Apr 12  | NO CLASS |                       |  |
| :------:| :-------:|
| Apr 17  | Linear Bandits                   |  Optimism and OFUL                             | Chapter 19,20 of the Bandit Book |
| :------:| :-------:|
| Apr 19  | Bayesian Methods                 | Thompson Sampling, Langevin Dynamics | [Learning to Optimize via Posterior Sampling](https://djrusso.github.io/docs/Learning_to_Optimize.pdf), Chapters 35-36 of the Bandit Book |
| :------:| :-------:|
| Apr 24 |Continue Thompson Sampling         | Thompson Sampling | [Colab Link](https://colab.research.google.com/drive/168C50Dm6CPy1SOpmU22pQi1gARkE9eYZ?usp=sharing) |
| :-------:| :-------:|
| Apr 26 | Posterior Sampling and Uncertainy Quantification  | |  |
| :-------:| :-------:|
| May 1 | Contextual Bandits                 | Policy Based vs Model Based  | Handwritten Notes, Chapter 18 of Bandit Book  |
| :-------:| :-------:|
| May 3 | Contextual Bandits                 | $\tau$-Greedy  | [Notes by Alekh and Sham](https://courses.cs.washington.edu/courses/cse599m/19sp/), [Taming the Monster](https://arxiv.org/abs/1402.0555), [Instance Dependent Bounds](https://arxiv.org/abs/2207.02357) |
| :-------:| :-------:|
| May 8 | Contextual Bandits                 | SquareCB       | [Beyond UCB](https://arxiv.org/abs/2002.04926), [Bypassing the Monster](https://arxiv.org/abs/2003.12699), [Online Learning Notes](https://arxiv.org/abs/1912.13213), Prediction, Learning and Games Chapter 2 |
| :-------:| :-------:|
| May 10 | Off-Policy Evaluation             | IPS and Friends| [Course Notes](https://courses.cs.washington.edu/courses/cse599m/19sp/notes/off_policy.pdf), [Recsys 2021 Tutorial](https://sites.google.com/cornell.edu/recsys2021tutorial)  |
| :-------:| :-------:|
| May 15 | Guest Lecture |  |  |
| :-------:| :-------:|
| May 17 | NO CLASS |  |  |
| :-------:| :-------:|
| May 22 | Non-Stationarity |  |  |
| :-------:| :-------:|
| May 24 | Non-Stationarity |  |  |
| :-------:| :-------:|
| May 29/31 |Group Meetings |  |  |
| :-------:| :-------:|
{: .tablelines}



