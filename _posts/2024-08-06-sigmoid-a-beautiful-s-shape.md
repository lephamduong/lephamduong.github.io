---
title: Sigmoid - A beautiful S-shape
tags: [MachineLearning, LogisticRegression]
style: fill
color: success
description: Explore the properties of the sigmoid function and its role in logistic regression.
---

An essential part of logistic regression is the sigmoid function. By mapping predicted values to probabilities, it ensures that the result stays between 0 and 1. Any real value can be entered into this function, and it will output a probability score. The sigmoid curve has an "S"-like visual representation.

<img src="https://i.imgur.com/OQNgLMr.png" alt="sigmoid" width="400"/>

The sigmoid function's mathematical expression looks like below:
{% include elements/mathjax.html math="s(z) = \frac{1}{1 + e^{-z}}" %}



Key Properties of the Sigmoid Function
## 1. Output Range: 
One of the most crucial properties of the sigmoid function is its output range. For any real number input the sigmoid function outputs values strictly between 0 and 1. This characteristic makes it especially useful for binary classification tasks, where the goal is to predict probabilities.

<img src="https://i.imgur.com/EHo2uOV.png" alt="sigmoid" width="400"/>


## 2. S-Shaped Curve:
The sigmoid function creates an S-shaped curve. When plotted, the curve transitions smoothly from 0 to 1, with a point of maximum steepness at 0
z=0. This steepness is crucial for distinguishing between probabilities close to 0 and those close to 1, providing a clear gradient for the learning algorithm to work with.

## 3. Gradient and Derivative: 
The sigmoid function’s gradient is another important property. The derivative of the sigmoid function can be expressed as:

{% include elements/mathjax.html math="σ'(z)=σ(z)⋅(1−σ(z))" %}


This property is essential for optimization algorithms like gradient descent, as it helps in adjusting the model parameters during training.

## 4. Symmetry: The sigmoid function is symmetric around 

z=0. This symmetry means that if z is positive, the sigmoid function’s output will be greater than 0.5, and if z is negative, the output will be less than 0.5. This property is useful in binary classification where the decision boundary is centered around 0.5.

Asymptotic Behavior: As 
𝑧
z approaches positive or negative infinity, the sigmoid function asymptotically approaches 1 and 0, respectively. This means that extreme values of 
𝑧
z result in probabilities very close to 1 or 0, effectively making predictions more confident.





## 1. Unsubscribe from irrelevant emails



## 2. Unfollow people on social media

someone’s posts, stories, and other notifications without explicitly unfollowing them and not tarnishing your (probably nonexistent) relationship with them.

## 3. Take occasional social media purges



Another strategy, courtesy of Kenton Prescott is to enact a recurring purge, where you keep your phone in airplane mode (or even Do Not Disturb) for some amount of hours a day, limiting the time you spend catching up on notifications. The idea is that everyone can wait a few hours for your attention, even in the case of emergencies.

## 4. Turn off notifications for non-essential things

This one is pretty simple, just turn off notifications for things that are not essential. Every time your phone or wearable buzzes, you’re losing precious mental bandwidth which can take up to 23 minutes to get back!

In similar fashion to the previous steps, this takes some time and conscious effort daily where you take note of all notifications you get, evaluate if each one is worth the time, and turn off as necessary.

## 5. Learn how to use built in tools

One of my favorite features on my phone is Do Not Disturb. It allows you to silence all non-critical notifications for an indefinite amount of time. This is what I use when I’m working on school work, personal projects, or even this article. On both iOS and Android, you’re given fairly granular control over what is considered critical so you can pick and choose what is worth the focus lost from a distraction.

{% include elements/figure.html image="https://cdn-images-1.medium.com/max/1000/0*MAeS-4fEc0Y7T4VB.jpg" caption="iOS" %}
{% include elements/figure.html image="https://cdn-images-1.medium.com/max/1000/0*nF_H2-8oTY7C0a54.png" caption="Android" %}

Apple and Google also fairly recently rolled out time management tools which allow the user to be restricted from certain applications after a given amount of use. This really helps to add an extra layer of discipline if you’re trying to build the habit of using your phone less.

Minimalism isn’t a philosophy that demands you to sell everything you own, wear the same outfit for the rest of your life, and live out of your van. Rather, it’s taking a hard look at everything in your life and determining whether something truly provides happiness for you. Digital Minimalism is a subset of this way of thinking and is a philosophy that has allowed me to work in tech and be an active participant of social media, but also maintain my own level of free thinking and choose what I focus on.

I hope this has helped at least one person out there better manage their digital engagement. When I was first starting my foray into this way of thinking, this documentary by Matt D'Avella really helped me understand what minimalism was all about and is something I’d recommend if you’d like to learn more!