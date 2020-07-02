---
description: 'arXiv:1801.02774'
---

# Adversarial spheres

## Contributions

> 1.Several models trained on this dataset are vulnerable to adversarial examples, _**that is most randomly chosen points from the data distribution are correctly classified and yet are "close" to an incorrectly classified input.**_ ~~~~This behavior occurs even when the test error rate is less than 1 in 10 million and even when we restrict the adversarial search space to the data manifold.
>
> 2.For this dataset, we prove a fundamental upper bound on  $$d(E)$$ in terms of $$\mu(E)$$. In particular, we prove that any model which misclassifies a small constant fraction of the data manifold will be vulnerable to adversarial perturbations of size $$O(1/\sqrt{(n)})$$ .
>
> 3.Neural networks trained on this dataset approach this theoretical optimal bound. This implies that in order to _**linearly increase**_ $$d(E)$$, the classification error rate $$\mu(E)$$  must _**decrease**_ significantly.

## Related Work

A simple framework：datasets is ideal sphere data points, network is simple yet.  And then, due to linear activate units maybe isn't suitable, there is a new called ‘the quadratic network‘ , where  $$\sigma(x)=x^2$$ ,$$\hat{y}=\sum(\alpha_{i}z_{i}^2-1)$$                                         

{% hint style="info" %}
In paper, they claim that a complex model is simliar with a simple model. whereas, in terms of model, maybe it is not necessary to build a deep model at least for adversarial example.
{% endhint %}

_**An image to explain manifold distribution**_

![](.gitbook/assets/sphere.png)

At section 4.1

