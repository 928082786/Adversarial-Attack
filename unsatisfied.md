---
description: An overview of Adversarial attack
---

# Overview

## Introduction

Deep learning has become an important role in machine learning in decades, whose algorithms in many domains,such as computer vision, nature language process and many others,has achieved perfect performance. The classifier accuarcy of network models has been proved that surpass the human.There are many applications of deep learning in industry and commerce,etc.however, there exits adversarial examples causing model output uncorrect labels. **Szegedy** et.al.first discovered that the models are susceptible to adversarial attacks that adversarial examples imperceptible to human.Despite the model has high accuarcy at clean images, while model accuarcy will drop in a low level when the clean images are changed into adversarial exmaples. The existence of adversarial examples and the robustess of model is widely concerned and **the arms race between adversarial attacks and defenses has accelerated（**Adversarial Examples in Modern Machine Learning: A Review\).Thus, it is necessary to have extermly acknowledge aboue the adversarial attack which we will discuss in this paper.

##  Adversarial Attacks

In this section, we will list some pulishing adversarial attack techniques. Through surveying existing adversarial attacks, we could study the basic ideas of these methods.

![Figure1 Main adversarial attack mehods](.gitbook/assets/1911%20%281%29.jpg)

### Fast Gradient Sign Method

The Fast Gradient Sign Method \(FGSM\) is designed to quickly find a perturbation direction for a given input such that the training loss function of the target model will increase, reducing classification confidence and increasing the likelihood of inter-class confusion.FGSM method don't need to iterate, the compete





