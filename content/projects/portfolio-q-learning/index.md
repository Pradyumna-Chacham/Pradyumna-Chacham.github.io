---
title: "Portfolio Optimization with Deep Reinforcement Learning"
date: 2025-05-23
summary: "Applied Deep Q-Learning to develop an AI agent that dynamically optimizes financial portfolio allocations, achieving a high risk-adjusted return."
tags: ["Reinforcement Learning", "Deep Learning", "Python", "Finance", "Deep Q-Network"]
weight: 30
# Optional image to display on the page.
image:
  caption: 'A chart showing portfolio performance'
  focal_point: 'Smart'
---

This project, based on my published research, explores the application of deep reinforcement learning to the complex problem of financial portfolio optimization.

### Goal
The objective was to create an intelligent agent that could learn to manage a portfolio of assets by interacting with a simulated market environment. The agent's goal was to maximize returns while effectively managing risk.

### Method
I implemented a **Deep Q-Network (DQN)** agent, a model that learns optimal actions through trial and error. The agent was trained to perform actions (buying, selling, or holding assets) that were evaluated based on key financial metrics, including:
- Daily and cumulative returns
- **The Sharpe Ratio**, a critical measure of risk-adjusted performance.

### Results
The trained agent successfully learned a sophisticated trading strategy. It achieved a **Sharpe Ratio of 2.61**, indicating that it generated strong returns relative to the risk it took on. This performance was highly competitive when benchmarked against market indices, demonstrating the effectiveness of reinforcement learning in this domain.

For a more detailed technical explanation, you can read the full research paper.

[**Read the Paper**](https://ieeexplore.ieee.org/document/11140422)