---
title: "The Effects of Image Distribution and Task on Adversarial Robustness"
collection: talks
type: "Talk"
permalink: /talks/effects-of-image-distribution-task-robustness-talk
venue: "Hunter College Applied Mathematics Seminar"
date: 2021-03-11
location: "New York, New York"
---

Currently, few studies testing the theories of adversarial robustness take into consideration that when doing comparisons across each dataset, both the image distributions (e.g. digits vs objects) and classification task (to classify digits vs objects) are different. To unravel the causal factors of the inherent adversarial robustness of a model, we propose an unbiased metric to compare adversarial robustness and perform a series of experiments. In these experiments, we equalized several training hyperparameters on networks for the MNIST and CIFAR-10 datasets to determine whether the image distribution and task played a role in adversarial robustness. We find that networks trained for digit classification on MNIST digits are more adversarially robust than networks trained to do object classification on CIFAR-10 objects. In addition, to pin-point whether the contribution of adversarial robustness is mainly due to the image distribution or the task, we create a fusion image dataset that overlapped MNIST digits with CIFAR-10 objects such that image statistics were matched and train networks to perform a digit or object classification task. We find that models performing digit recognition on the fusion images were more robust than those performing object recognition, empirically verifying the role of the classification task in the adversarial robustness of a model, independent of the image distribution a network is trained on. Comparing the fusion model performances to their non-fusion counter-parts, we find that image distribution also plays a role.

[Watch talk here](https://us02web.zoom.us/rec/share/pSbEzwI-pEn5IvRNeNxZ9ST8t7qJSad0bkllmXhAUmJHOk_7n4qADctjapC0ADjJ.r6qLxr_OUEFrOhHj)
