---
layout: post
title: Overview
permalink: /overview/
---

Deep learning relies on massive training sets of labeled examples to learn from - often tens of thousands to millions to reach peak predictive performance. However, large amounts of training data are only available for very few standardized learning problems. Even small variations of the problem specification or changes in the data distribution would necessitate re-annotation of large amounts of data. 

However, domain knowledge can often be expressed by sets of prototypical descriptions: For example, vision experts can exploit meta information for image labeling, linguists can describe discourse phenomena by prototypical realization patterns, social scientists can specify events of interest by characteristic key phrases, and bio-medical researchers have databases of known interactions between drugs or proteins that can be used for heuristic labeling. These knowledge-based descriptions can be either used as rule-based predictors or as labeling functions for providing partial data annotations. The growing field of weak supervision provides methods for refining and generalizing such heuristic-based annotations in interaction with deep neural networks and large amounts of unannotated data. 

In this workshop, we want to advance theory, methods and tools for allowing experts to express prior coded knowledge for automatic data annotations that can be used to train arbitrary deep neural networks for prediction. The ICLR 2021 Workshop on Weak Supervision aims at advancing methods that help modern machine-learning methods to generalize from knowledge provided by experts, in interaction with observable (unlabeled) data. 

In particular, we are interested in the following questions: 

- What tasks, not traditionally solved with weak supervision, can profit from knowledge-based labeling?
- What are the typical characteristics of a prediction task that make it amenable to weak supervision? 
- How can weak supervision best be combined with neural networks and representation learning? 
- What is the relationship of weak supervision to other machine learning paradigms, specifically, to semi-supervised learning, to active-learning, to label denoising and confidence estimation? 
- Can approaches to weak supervision from different fields, e.g, relation extraction (natural language processing) and image classification (vision) be unified? 
- What are good benchmarks for evaluating and comparing weak supervision approaches? 

Learning with weak supervision is both studied from a theoretical perspective as well as applied to a variety of tasks from areas like natural language processing and computer vision. This workshop aims at bringing together researchers from this wide range of fields to facilitate discussions across research areas that share the common ground of using weak supervision. A target of this workshop is also to inspire applications of weak supervision to new scenarios and to enable researchers to work on tasks that so far have been considered too low-resource. 

As weak supervision addresses one of the major issues of current machine learning techniques, the lack of labeled data, it has also started to obtain commercial interest. This workshop is an opportunity to bridge innovations from academia and the requirements of industry settings. 

For those new to the topic, we collected a <a href="https://github.com/michael-aloys/awesome-weak-supervision/">list of papers</a> to get an overview over the field.
