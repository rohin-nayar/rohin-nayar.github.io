---
layout: post
title:  "Stochastic Processes Series - Part 1"
date:   2024-03-13 17:52:00 +0000
categories: jekyll update
---

## Introduction

In 1973, Fischer Black and Myron Scholes published a groundbreaking paper titled '[The Pricing of Options and Corporate Liabilities][Pricing-Of-Options].' This paper introduced the Black-Scholes model, a revolutionary concept in finance that has come to be known as the trillion-dollar equation. This article marks the beginning of a series aimed at understanding and introducing the statistical mechanics underlying the financial world.

## Understanding Stochastic Processes

Before diving into the intricacies of the Black-Scholes model and option pricing, it's essential to grasp the concept of stochastic processes. At the heart of many financial models lies Brownian motion, making it a logical starting point for exploration.

## Brownian Motion

Brownian motion refers to the random movement of particles suspended in a fluid due to collisions with the rapidly moving molecules in the fluid medium. This phenomenon can be described using the Wiener process, a continuous-time stochastic process essential in models like the Black-Scholes option pricing model.

## Exploring Brownian Motion with Python

As part of the ongoing development of the Financial Modeling library, a Python script for Brownian motion modeling has been created. This script provides three methods for exploring Brownian motion:
1. Motion from a Random Walk process
2. Motion from the Normal Distribution
3. Modeling stock prices using Geometric Brownian Motion

The following sections delve into each of these methods, providing insights into their applications and implications in financial modeling.

![Brownian Motion](images/BrownianMotion.png)


[Pricing-Of-Options]: https://www.worldscientific.com/doi/epdf/10.1142/9789814759588_0001
