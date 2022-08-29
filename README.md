# Cellular-Automata

 The CA model implemented here is a binary CA model with the droplet rule. Its state-transition function can be understood as a model of panic propagation among individuals sitting in a gym after a fire alarm goes off. Here is the rule (which uses the Moore neighborhoods):
1. A normal individual will get panicky if he or she is surrounded by four or more panicky individuals.
2. A panicky individual will remain panicky if he or she is surrounded by three or more panicky individuals. Otherwise he or she will revert back to normal.

The result of the simulation is as follows (for a probability of 0.1):
The various images represent the simulation after different timepoints. 
![Screenshot (1322)](https://user-images.githubusercontent.com/56737677/187119311-33f531f3-cfcb-4e90-9595-68f6cebd817b.png)
![Screenshot (1323)](https://user-images.githubusercontent.com/56737677/187119316-10348551-8099-4045-97ca-e21f750473d1.png)

The simulation is based on an inline book which can be found here:
https://math.libretexts.org/Bookshelves/Scientific_Computing_Simulations_and_Modeling/Book%3A_Introduction_to_the_Modeling_and_Analysis_of_Complex_Systems_(Sayama)/11%3A_Cellular_Automata_I__Modeling/11.03%3A_Simulating_Cellular_Automata
