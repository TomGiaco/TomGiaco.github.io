---
title: "Finding the optimal visual input for cortical neurons"
excerpt: "Generating Most Excitatory Inputs for single neurons in mouse visual cortex with CNNs, benchmarked against Gabor filters."
collection: portfolio
---

A group research project using deep learning to identify and generate the **Most Excitatory Input (MEI)** for individual neurons in the visual system of the mouse.

An MEI is the visual stimulus that maximally activates a given neuron. Because it is synthesised rather than drawn from a stimulus set, it reveals which features inside a neuron's receptive field that cell actually responds to — making it a way of characterising a single cell's function *in silico*. The approach: train an end-to-end CNN to predict a neuron's response to an image, then optimise an input image against that trained model to drive the predicted firing rate as high as possible.

**My contribution** was the code that generates the MEIs: given a CNN that predicts neural response from an image, it produces the stimulus that maximally excites the target neuron.

We then examined the properties of these artificially optimised stimuli and tested how robust the findings were by using **Gabor filters** as a benchmark — a sensible control, since Gabors are the classical model of early visual receptive fields.

Built on the [AllenSDK](https://allensdk.readthedocs.io/en/latest/index.html) dataset, and inspired by Walker et al., *"Inception loops discover what excites neurons most using deep predictive models"*, Nature Neuroscience (2019).

**Code:** [github.com/TomGiaco/Investigating-Optimal-Visual-Inputs-newline-for-Cortical-Neurons](https://github.com/TomGiaco/Investigating-Optimal-Visual-Inputs-newline-for-Cortical-Neurons)
