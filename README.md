# Audio-Reactive-Particle-System
 Audio reactive Particle System controlled by a series of neural networks to control various aspects.

This Patch takes audio input either from the ADC or from another Max patch (via the mc.r~ object) and uses it to control a particle system based of Chaotic Attractors. It is based on a tutorial from Hearing Glass|Umut Eldem on [Youtube](https://www.youtube.com/watch?v=xBM9C9ADK8w).

The Speed and Shae of the particles are controlled by 3 analysis: Pitch, Onset, and Novelty. 

Colour is controlled by a neural netowork which interprets a 12 band chroma analysis. This repository contains a JSON file with training data based on Messiaen's synesthesia. However, this NN can be trained to whatever colours are desired. 

This patch was originally intended for use in performance with my [SHIFT controller](https://github.com/FinnHeathfield/SHIFT-Granular).

## Dependancies
This patch requires the [Flucoma](https://learn.flucoma.org/) Package which is avaliable from the Max package manager.
