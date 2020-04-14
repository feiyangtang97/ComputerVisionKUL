# ComputerVisionKUL
This repo contains assignments related to CV course of MAI programme in KU Leuven.

### Project 1: Crafting and learning features
The goal of this assignment is to explore more advanced techniques for constructing features that better describe objects of interest and perform a few tasks using these features.

More practical, this assignment is broken down into four main parts:
* construct your own dataset of faces;
* build some feature representations using handcrafted (HOG) and non-handcrafted techniques (PCA and transfer learning);
* use and compare the feature representations in context of classification of faces and assessing similarity between faces;
* discussion.

We picked images from four different celebrities A, B, C, and D. C looks like A and D looks like B. The classifiers are trained on 40 images of A and B then predict labels on 40 images of A, B, C, D. The identification step provides *k* similar faces from training faces on a randomly picked testing face.

### Project 2: Deep learning problems