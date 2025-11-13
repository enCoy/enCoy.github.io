---
title:  "The 80/20 Trap: How Common Data Splits Can Mislead Science"
mathjax: true
layout: post
categories: media
---

As a senior Ph.D. student working with temporal data every day, I can’t imagine finishing my degree without calling out an issue I see over and over again. I have encountered it countless times—not just in older papers, but even in recent publications. Whenever I see an “80/20 split” mentioned, my eyes immediately search for the details of how it was applied. By the way, even seeing any description at all is a rare gift—most authors don’t even bother.

I notice this particularly in biomedical papers as I am working in this field at the moment. A red flag often turns out to be the word “concatenate”. Authors frequently state that they “concatenate data from all subjects” before applying the 80/20 split and then report astonishing results—AUCs and accuracies above 0.9 (By the way, if the results are unbelievably good, do not believe them!). The problem is that concatenating before splitting effectively places samples that are temporally close to the test set into the training set. In most temporal datasets, this makes the test distribution nearly identical to the training distribution. In other words: you’re hacking your own evaluation.

Is this a minor slip? Not at all. It doesn’t just make that paper unreliable; it sets a trap for future research. Others will see these inflated numbers and try to beat them, assuming they reflect real generalization. Even when they suspect the numbers are “too good to be true,” proving it is difficult—and the flawed methodology keeps propagating.

Why does it happen? Often, it’s not a technical challenge. The issue arises when machine learning is treated as a tool rather than a focus. If no one on the team truly understands generalization, it’s easy to replicate mistakes from published papers, assuming that “published must be correct.”

So what’s the right way? In biomedical and biosensing applications, we care about real-world generalization—tools that work on new subjects in real time. Leave-one-subject-out cross-validation (LOSO-CV) or subject-based train-test splits are appropriate choices. Sometimes, it is not possible to use either one of these as one can notice that it is not possible to generalize to other subjects, pushing one towards subject-specific modeling choices. Even in such analyses, training and test portions must consist of different temporal chunks rather than random temporal indices. A simple example is using the first 80% of data for training and the remaining 20% for testing—a practice common in financial forecasting.

The takeaway is simple: the pressure to publish quickly is real, but rigor cannot be sacrificed. Thinking carefully about train-test splits is not just about protecting your results—it’s about serving the scientific community. Every time we take shortcuts, we risk creating a future built on shaky foundations. And that, as researchers, is something we cannot afford. 
