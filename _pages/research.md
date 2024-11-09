---
permalink: /research/
title: "Research"
header:
  overlay_image: assets/images/wbd.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

# Understanding Host-Pathogen Dynamics through individual decision making and population density

Infectious diseases are an increasing threat to biodiversity and human health. Developing a thorough understanding of the factors driving host-pathogen dynamics is therefore essential in both ecological and epidemiological research. Disease dynamics are fundamentally shaped by host-pathogen interactions at various spatial and temporal scales. Individual decision-making processes, especially movement choices as adaptive responses to environmental changes, play a central role in disease transmission. Accordingly, simulation models that aim to predict realistic host-pathogen dynamics must account for individual behaviours and life-history traits of host organisms. Individual- or agent-based models, which capture the variability in host behaviours, offer new approaches and insights into the study of disease dynamics.

## Wildlife disease dynamics: Linking host and pathogen traits

| Pathogens are a fundamental component of biodiversity, significantly impacting host population dynamics and playing a crucial role in shaping community structures. In this work, we aim to understand how species, acting as "mobile pathogen links" with their diverse movement patterns and life-history strategies, influence the distribution, spread, persistence, and evolution of diseases. | ![image-right](/assets/images/model1.gif){: .align-right width="75%"}| 

## :construction: Bridging the Gap: Integrating Management Practices into Wildlife Disease Models :construction: ![image-right](/assets/images/InteractionMap1.png){: .align-right width="50%"}

 *A highly detailed, scalable, spatially explicit agent-based model for African swine fever (ASF) management.*<br> The model in development is a comprehensive simulation of individual and group dynamics, incorporating various behaviours and processes such as movement, mortality, hunting, pathogen dynamics, dispersal, home range behaviour, roaming, reproduction, group dynamics, and interactions between different layers. Each module contributes to a specific aspect of the model, providing detailed logic and functionality to simulate realistic population dynamics. The model incorporates stochastic elements to capture the inherent randomness in natural systems, making it a valuable tool for understanding complex ecological and epidemiological processes. While most critical model components are functionally implemented, the parameterisation and fine-tuning of behavioural components, to achieve the desired model outputs is currently ongoing.<br> 
<br>Some of the key features are:

- **Movement module**<br>
The movement module handles the movement logic for individuals and groups within the model. It includes functions for moving individuals towards target cells, performing random walks, and moving to adjacent cells based on environmental quality. The movement logic is designed to simulate realistic behaviours, incorporating stochastic elements and decision-making processes based on environmental factors. This module is essential for modelling the spatial dynamics of the population and understanding how individuals interact with their environment. 

- **Hunting module**<br>
The hunting module models the hunting pressure on the population. It includes functions for simulating hunting events, determining the success of hunts, and managing the impact of hunting on population dynamics. The module incorporates stochastic elements to simulate the randomness of hunting success and its effects on individual and group survival. This component is important for understanding the role of hunting in population regulation and its impact on the ecosystem. As a novel approach, hunting is modelled spatially explicit, including avoidance behaviour from the hunted populations.

- **Pathogen module**<br>
The pathogen module handles the simulation of pathogen dynamics within the population. It includes functions for modelling the spread of infections, tracking infection status, and managing the impact of pathogens on individual health and mortality. The module incorporates stochastic processes to simulate the randomness of infection spread and its effects on population health. This functionality is essential for understanding disease dynamics and the impact of pathogens on population stability.

- **Homerange module**<br>
The homerange module models the home range behaviour of individuals and groups within the population. It includes functions for defining and updating home ranges, determining home range overlap, and managing the impact of home range dynamics on individual and group interactions. The module incorporates stochastic elements to simulate the randomness of home range establishment and its effects on population structure. This component is important for understanding territoriality, resource use, and the impact of home range dynamics on population stability and disease dynamics.

- **Roamers module**<br>
The roamers module handles the behaviour of roaming individuals within the population. It includes functions for simulating the movement and behaviour of roamers, determining their interactions with other individuals and groups, and managing the impact of roaming on population dynamics. The module incorporates stochastic elements to simulate the randomness of roaming behaviour and its effects on population structure. This functionality is essential for understanding the role of roamers in population connectivity and the impact of roaming on population resilience and disease dynamics.
Reproduction module

- **Dispersal module**<br>
The dispersal component models the dispersal behaviour of individuals within the population. It includes functions for simulating the movement of individuals away from their natal groups, determining dispersal success, and managing the impact of dispersal on population structure. The module incorporates stochastic elements to simulate the randomness of dispersal events and their effects on population dynamics. This component is important for understanding population connectivity, and the impact of dispersal on population resilience.

- **Interaction layer module**<br>
The interaction layer module handles the interactions between different layers of the model, such as individuals, groups, and the environment, disperser and roamers. It includes functions for simulating interactions between these layers, determining the outcomes of interactions, and managing the impact of interactions on population dynamics and pathogen spread. This functionality is essential for understanding the complex interplay between different components of the model and the impact of interactions on the population and disease dynamics.

- **Carcass module**<br>
The carcass module manages the creation and handling of carcasses within the model. It defines the Carcass Source trait, which is implemented by various entities such as Roamer, Group Member, and Dispersing Individual. This trait provides methods to retrieve an entity's ID, age class, position, creation time, and infection status. The file also includes logic for tracking the health status of individuals, particularly whether they are infected, and managing the spatial and temporal aspects of carcass creation. This functionality is crucial for modelling disease dynamics and the decomposition process. 






