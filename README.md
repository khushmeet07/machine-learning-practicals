# Applied Machine Learning Practicals

A collection of practical implementations exploring machine learning concepts through business-oriented problems and Python-based experimentation.

## Overview

This repository focuses on applying machine learning concepts to practical business scenarios rather than only studying theoretical models.

The current practical covers two major areas:

* **Unsupervised Learning** — Customer segmentation using K-Means clustering
* **Reinforcement Learning** — Route optimization using actions, rewards, exploration, and exploitation

The practical is designed to connect machine learning techniques with real-world business decision-making.

## Current Practical

### 01 — Unsupervised & Reinforcement Learning

#### Customer Segmentation — K-Means Clustering

An online retailer's customers are grouped based on:

* Monthly spending
* App visits

K-Means clustering is used to identify three customer segments and interpret their behaviour from a business perspective.

Potential business applications include:

* Customer segmentation
* Loyalty programs
* Personalized recommendations
* Customer re-engagement campaigns

#### Reinforcement Learning — Route Optimization

A simplified delivery-route scenario demonstrates the fundamental reinforcement learning cycle:

**Action → Reward → Learning from Result**

The practical introduces:

* Agent
* Environment
* Action
* Reward
* Exploration
* Exploitation

Two delivery routes are evaluated using their historical reward values to demonstrate how an agent can favour actions that produce better outcomes.

## Technologies

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Jupyter Notebook

## Project Structure

```text
applied-machine-learning-practicals/
│
├── part-a/
│   └── unsupervised-learning/
│       └── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│
├── README.md
└── .gitignore
```

## Key Concepts

### Unsupervised Learning

Unsupervised learning identifies patterns or groups in data without predefined target labels.

In this practical, K-Means is used to divide customers into three groups based on spending and app activity.

### K-Means Clustering

K-Means assigns observations into a predefined number of clusters.

For this practical:

```text
K = 3
```

The resulting cluster numbers are labels assigned by the algorithm and do not inherently represent customer quality or value.

### Reinforcement Learning

Reinforcement learning involves an agent taking actions within an environment and learning from the rewards received from those actions.

```text
Agent → Action → Environment → Reward → Learning
```

### Exploration vs Exploitation

**Exploration** involves trying different or less-used options to gather information.

**Exploitation** involves selecting an option that is already known to perform well.

## Business Applications

The concepts demonstrated in this repository can support applications such as:

* Customer profiling
* Marketing segmentation
* Personalized campaigns
* Customer retention
* Recommendation strategies
* Delivery-route optimization
* Decision-making systems

## Learning Objectives

By completing the practical, the learner develops an understanding of:

* Customer segmentation using K-Means
* Interpreting clusters from a business perspective
* The basic reinforcement learning framework
* Agent, action, environment, and reward
* Exploration and exploitation
* Business applications of machine learning

## Notebook

The primary practical notebook contains the complete implementation, visualizations, business interpretation activities, and reflection questions.

## Status

**Learning Project / Academic Practical**

This repository is intended for educational and portfolio purposes and can be extended with additional machine learning practicals and business applications.

## Author

**Your Name**

Machine Learning | AI | Business Analytics
