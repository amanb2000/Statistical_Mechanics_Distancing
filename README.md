# Statistical Mechanics Distancing

Simulations and calculations relating to a statistical mechanical analysis of disease spread in the context of social distancing in the COVID-19 viral pandemic.

## Introduction

Here I aim to elucidate the nature of 1-on-1 airborne disease spread utilizing principles of statistical mechanics and particle simulation.

Emphasis is placed on the relationship between `probability of disease spread` and `time`. Current legislation states that people should distance at "2 meters apart at all times". Is that a good approximation for the way disease spreads? Would it make more sense to contextualize it as "6 foot-seconds" apart? Is it better to be 7 feet apart for 4 hours of 5 feet apart for 4 seconds? 

The simulations contained herin aim to elucidate this. 

## Models

### 1: Parameterized Spheres in Maxwell-Boltzmann Distributed Gas

This model is the simplest possible (parameterized) model for disease spread at different distances. Normal particles are continuously converted to viral particles within the 'infected' sphere.

- Gas is an ideal Maxwell-Boltzmann distributed substance with no currents.
- Two individuals are modeled as spheres.
- Parameters:
	- Sphere size.
	- Number of particles.
	- Temperature.
	- Distance between two spheres.
	- Rate of viral particle conversion.
	- Threshold for infection of uninfected sphere (number of particles or concentration).

*Parameters to Research:*
- [ ] Boltzmann distribution formula.
- [ ] "Critical mass" of airborne virus concentration for infection.
- [ ] Concentration of viral particles eminating from an infected individual.
	- [ ] Rate of viral particle emision.

*Problems with model:*
- Does not account for wind, breathing onto other people, sneezing/coughing.
	- Wind is likely a turbulent property -- would not be a simple addition to the mean velocity along an axis. 
- People aren't spheres.
- It's unclear if viral concentration is the key factor.

The model could potentially serve as a lower-bound for transmission...



