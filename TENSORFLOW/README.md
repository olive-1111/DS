# TensorFlow 2.0: Deep Learning & Reinforcement Learning (Legacy Refactoring)

This project documents a comprehensive deep-dive into the TensorFlow ecosystem. Because this curriculum was based on the 2020 TensorFlow 2.0 release, it required significant code refactoring and library updates to remain functional in a 2025/2026 development environment.


## CURRICULUM OVERVIEW

* **Module 1 & 2:** Machine Learning Fundamentals and the TensorFlow Architecture.
* **Module 3:** Core Learning Algorithms (Linear Regression, Classification, Clustering).
* **Module 4:** Deep Neural Networks (Hidden Layers, Activation Functions, Optimizers).
* **Module 5:** Deep Computer Vision (Convolutional Neural Networks).
* **Module 6:** Natural Language Processing (NLP) with Recurrent Neural Networks (RNNs).
* **Module 7:** Reinforcement Learning (Q-Learning and Markov Decision Processes).

## THE "LEGACY TO MODERN" CHALLENGE

Following a 2020-era tutorial in 2025 required an "active debugging" mindset. I successfully modernized the following areas:

* **Library Migration:** Navigated the industry-wide shift from the deprecated `gym` library to the modern `gymnasium` for Reinforcement Learning modules.
* **API Updates:** Adjusted to changes in the `tf.keras` API, including updated import paths and modified function arguments that have evolved since the original tutorial.
* **Dependency Management:** Resolved version conflicts between old tutorial requirements and current Python environments using AI-assisted troubleshooting.

## CHALLENGES & OBSERVATIONS

* **The Waiting Game:** Practiced extreme patience while waiting for training epochs to complete on a legacy machine, ensuring hardware stability throughout the process.
* **Meticulous Debugging:** Identified that even a minor version difference (e.g., TF 2.0 vs TF 2.15+) could break a model, requiring a high level of precision in manual code entry.
* **Algorithmic Complexity:** Moving from standard Regression to **Q-Learning** and **RNNs** presented a steep learning curve that required multiple iterations to get right.

## SOLUTIONS

* **AI-Partnered Refactoring:** Used AI extensively as a "translation layer" to convert outdated 2020 syntax into modern, executable TensorFlow code.
* **Hardware Management:** Monitored system resources during the Reinforcement Learning and CNN phases to ensure the training process didn't overwhelm the local CPU.
* **Persistent Practice:** Maintained a "dirty hands" approach, typing every line of code to ensure a deep understanding of the underlying logic, even when the tutorial's code was no longer plug-and-play.