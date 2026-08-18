# DogSim 
<img src="https://github.com/YahyaGamal/DogSim_Aberdeen_summerschool/blob/main/Data/logo.png?raw=true" alt="drawing" width="125"/>

## (Version for Aberdeen Summer School)

This repository includes a constrained version of DogSim. The model is built on the pedestrians movement module in the Multiple Activities Transport and Mobility (MATraM) Agent-Based Model (ABM)[^reference].

The model includes two types of agents:
    - Pedestrians: They move in looped traips in green spaces. Some of them own dogs.
    - Dogs: They move with their owner. They get attracted to each other and to trees in space.

This version runs on two case studies in Oxford, UK:
    1. Ports Meadow
    2. Burgess Field
Please note that modifying the `Area` chooser in Netlogo from one case study to another will require saving the model and restarting NetLogo to avoid errors caused by loading the GIS files into the model space.

The Burgess Field case study can be initialised with different scenarios designed to showcase the model and the different types of agents.

To view the movement of agents, it is recommended to slow down the model speed (approximately 25% of the full speed should produce smooth visuals)

[^reference]: Gamal, Y., Colasanti, R., Polhill, G., Mitomi, T., Suel, E., & Heppenstall, A. (2026). *MATraM: A Multi-Activity Transport and Mobility Agent-Based Model for Activity Modifications*. arXiv. https://doi.org/10.48550/arXiv.2605.30547