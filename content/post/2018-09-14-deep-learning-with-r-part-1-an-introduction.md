---
title: 'Neural Networks and Deep Learning with an R (twist): Introduction.'
author: Oluwasegun Ojo
date: '2018-09-14'
draft: FALSE
slug: deep-learning-with-r-part-1-an-introduction
categories:
  - Data Science
tags:
  - Machine Learning
  - Deep Learning
  - Online Courses
---

## Motivation

I've always being interested in Machine Learning and AI. I'm just fascinated by machine intelligence, that you can train a 'machine' with data and have it learn from the data. As usual, whenever I am interested in learning about a new field, I get on Coursera to find interesting courses about this field. I took the popular Machine Learning Course by Andrew Ng on Coursera, and it was by far one of the best courses I have taken in my life! It was an excellent introduction to some popular machine learning algorithms, what makes them tick and how to implement them (in MATLAB, I hope to one day write about implementing these in R).

Deep learning (which is basically the art of training neural networks) has experienced a sudden surge in popularity and again, I decided to turn to Coursera and Andrew Ng to learn about neural networks and deep learning. I am currently enrolled in the first course of Andrew's Deep Learning Specialisation titled Neural Networks and Deep Learning. So far, the course is well taught as is to be expected of Andrew Ng's high standard. The programming assignments are implemented in Python and as an R fan, I decided I will try to implement all the algorithms  in R as I learn them in  this course in R.

And that is why I am starting this new blog series about deep learning, neural networks with some R spice! I believe writing about new concepts learnt helps to solidify understanding. Baiscally, posts will be in parts, (with this post being the first), and each part will be a succint summary of a concept I learn in my journey of mastering deep learning. My hope is that each part will culminate in an algorithm or an application of an algorithm (a project) implemented in R. 

To get the ball rolling, I will end this blog post with a list of short notes explaining terms  (that might be)  used regulary on this journey. Most of these are not formal definition, but rather intuitions I picked from the course. Also I hope to update this list regularly with more terms as I progress :)



## Useful Terms
1. *Deep Learning*: refers to training neural networks, sometimes really large neural networks.
2. *Neural Network*: a simple neural network takes in an input, which goes into a node (which can be a function) and then produces an output. Consequently, a simple neural network (with a single neuron) can be seen as a function that maps an input `$X$` to an output `$y$`. A (big) neural network is formed by stacking up multiple simple neural networks. This is then trained by supplying the input `$X$` and the output `$y$` (called training data) to the neural network. The best parameters of the network (that is likely to produce output `$y$` given the input `$X$` input are learned using an optimisation algorithm.
3. *Supervised Learning*: this is a type of learning problem where we have some input `$X$` and and some output `$y$` and we're interested in learning (the parameters of) a function mapping `$X$` to `$y$`
4. *Structured and Unstructured Data*: Structured data is data in a tabular format. In R terminology, this is basically a *tidydata* while unstructured data are (like the name implies) data with less structure, like audio, text, image etc.




### *Footnote*
*Since I am a learner myself, there's likely to be few errors and if you spot one, kindly leave a comment about this so I can correct it. I hope that you find my post(s) helpful and your comments are welcome. I'd be thrilled to read and respond to them :)*