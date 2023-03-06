---
title: "Research on Multi-dataset Pre-training and Single-dataset Active Learning Methods under 3D Perception Scene"
collection: talks
type: "Discussion"
permalink: /talks/2022-11-15-mdf_discussion-1
venue: "Room 6, Level 12, L1 Building"
date: 2022-11-15
location: "Shanghai, China"
---

[Slides here](http://exampleurl.com)

The current 3D perception model follows the single dataset train-test pipeline. Such a single-dataset train-test pipeline faces two main challenges: 1) The strong data- and taxonomy-level differences in 3D perception datasets: the existing 3D perception datasets are collected using different manufacturers with different types of sensors, thus having strong data-level distribution differences and taxonomy distribution differences; 2) The weak cross-dataset generalization ability of 3D perception models: when a perception model is trained on one dataset (or domain) and directly deployed to another dataset, it usually faces serious recognition performance degradation.

Therefore, this talk is mainly focused on the main challenges faced by the current 3D perception models (single-dataset train-test pipeline). Combining with some of our preliminary exploration experience, we will introduce and discuss how to achieve open-world applications at a low cost in autonomous driving field, including the following two perspectives: 1) Discussing the challenges of 3D perception datasets: how to effectively merge various 3D perception datasets to improve model generalization ability, and learn dataset-agnostic representations; 2) Exploring how to help the model adapt to a specific domain or dataset at a low cost.
