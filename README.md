# MasterThesis
To determine whether cloud reflections affect radio signal transmission from the horizon, a preliminary simulation study was conducted. This work was carried out during a traineeship at the Radio Group of Deutsches Elektronen-Synchrotron (DESY) in Zeuthen, Germany.

The full [thesis](Writing/main.pdf) can be consulted in the [Writing section](Writing).

## Framework
A radio observatory for astroparticles is an extremely sensitive receiver. Therefore, understanding and modeling anthropogenic signals is of great importance to reduce the impact of background signals on astroparticle research.

## Research topic
This project focuses on signals originated near the **receiver's horizon**. This category is heavily affected by atmospheric refractions and reflections, making the description and modeling of the received signal more difficult. It is hypothesized (and here confirmed) that atmospheric **clouds can reflect radio signals**, scattering their power in every direction. To quantify the voltage received from such reflections, simulations of radio wave transmission through the atmosphere were performed.

## Project overview
This work considers a generic transmitter (the radio interference source) and transmitter (the radio observatory). A more case-specific study can be carried out with the same approach in future developments.

The approach adopted:
- The **radar simulation software** used is a pre-existing tool developed for modeling radar echoes from particle cascades in dense media.
- A **realistic cloud model**, incorporating liquid water content, droplet size, and cloud height, was implemented in the simulation code.
- Several simulations were run, taking into accout
  - distance of the transmitter;
  - orientation of the scattering;
  - transmitter's frequency;
  - transmitted signal's power.
