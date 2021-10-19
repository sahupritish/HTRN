## Challenges in Procedural Multimodal Machine Comprehension:A Novel Way To Benchmark

[Link](Challenges in Procedural Multimodal Machine Comprehension: A Novel Way To Benchmark)
Pritish Sahu, Karan Sikka, Ajay Divakaran
SRI International and Rutgers University
WACV 2020
[Link](Paper) [Link](code)

### Introduction

We focus on Multimodal Machine Reading Comprehension (M3C) where a model is expected to answer questions based on given passage (or context) and the context and
the questions can be in different modalities. Previous works such as RecipeQA have proposed datasets and cloze-style tasks for evaluation. However, we identify three critical biases stemming from the question-answer generation process and memorization capabilities of large deep models. These biases makes it easier for a model to overfit by relying on spurious correlations or naive data patterns (image background). We propose a systematic framework to address these biases through three Control-Knobs that enable us to generate a test bed of datasets of progressive difficulty levels. We believe that our benchmark (referred to as Meta-
RecipeQA) will provide, for the first time, a finer grained estimate of a model’s generalization capabilities. We also propose a general M 3 C model that is used to realize several prior SOTA models and motivate a novel hierarchical transformer based reasoning network (HTRN). We perform a detailed evaluation of these models with different language and visual features on our benchmark. We observe a consistent improvement with HTRN over SOTA (∼ 18% in Visual Cloze task and ∼ 13% in average over all the tasks). We also observe a drop in performance across all the models when testing on RecipeQA and proposed Meta–RecipeQA (e.g. 83.6% versus 67.1% for HTRN), which shows that the  proposed dataset is much less biased. We conclude by highlighting the impact of the control knobs with some quantitative results.


