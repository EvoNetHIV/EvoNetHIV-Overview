
# EvoNetHIV -- Agent based model for simulating HIV epidemics

Evonet Team: Steven Goodreau, Joshua Herbeck, John Mittler, James Murphy, Kathryn Peebles, Sarah Stansfield, Juandalyn Burke, Neil Abernethy, Geoffrey Gottlieb

2017-10-18 (in progress)

EvonetHIV is a stochastic agent-based simulation model that incorporates sexual network structure, behavior, HIV evolution, and treatment. Each simulation first estimates a statistical model that governs sexual network structure, and then proceeds through a burn-in period and epidemic simulation. At each time step of both the burn-in period and epidemic simulation, (1) partnerships form and dissolve; (2) sexual acts take place within a subset of existing partnerships; (3) HIV transmission occurs probabilistically within a subset of sexual acts; (4) viral dynamics and disease progression are updated for each infected agent; (5) vital dynamics, such as aging, are updated, and (6) testing and treatment are implemented at user-specified intervals.

![](./img/Prev_mean_degree_network_pic.png)

#### Model Information (in progress)  

[EvoNet Technical Summary](./files/EvoNet_Technical_Summary.pdf)  
[Overview of model dynamics](./files/overview_link.md)  
[Annotated EvoNet run script (simple example)](./files/Quick_start_overview.md)  
[Agent attributes overview](./files/EvoNet_Agent_Attributes_Overview.md)  
User Guide and Tutorials (coming soon)

#### Abstracts for In Prep / Submitted papers

[Goodreau SM, Stansfield SE, Murphy JT, Peebles KC, Gottlieb GS, Abernethy NF, Herbeck JT, Mittler JE. (submitted). Sexual network structure, HIV prevalence, and the evolution of set point viral load.](./files/abstractsGoodreau1.md)    

[Herbeck et al. HIV population-level adaptation can rapidly diminish the impact of a partially effective vaccine.](./files/abstractsHerbeck1.md)  
[(Complete Herbeck et al. paper at bioRxiv website)](https://www.biorxiv.org/content/early/2017/02/22/110783)

[Mittler et al. Agent-based network model predicts strong benefits to youth-centered HIV treatment-as-prevention efforts.](./files/abstractsMittler1.md)
