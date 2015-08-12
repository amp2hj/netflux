# Netflux #

Netflux is a modeling and simulation tool of different signaling pathways/networks that do not require any parameter data (such as time constants or species concentrations). Netflux simply requires knowledge of whether species “A” activates or inhibits species “B”, and by how much (the reaction "weight").  A user generated Network XLS (Excel) spreadsheet contains all of the species and reaction rules, and the spreadsheet is used as input for Netflux.  Running Netflux will create a graphical user interface (GUI) and output a specie's fractional activation, which can then be used for different analyses, such as identifying important nodes of a network, etc.

**With Netflux, you can do such things as:**
  * Easily share networks among the scientific community with the [Excel format](XLS.md)
  * Find the roles of feedforward and feedback loops
  * Examine potential crosstalk between species
  * Locate the relative position of a species in the pathway (e.g., you introduce an agonist, and the time it takes for one species to respond to it indicates its position in the signaling pathway relative to other species)
  * Assess how various network architectures drive signaling dynamics
  * Easily integrate new findings into the model
  * Use other system analyses tools such as quantitative sensitivity analysis, bifurcation analysis, and parameter estimation to study network relationships


![http://people.virginia.edu/~jjs3g/netflux/NetfluxWikiPics/flow.gif](http://people.virginia.edu/~jjs3g/netflux/NetfluxWikiPics/flow.gif)

<a href='Hidden comment: 
http://people.virginia.edu/~std6n/netflux/NetfluxWikiPics/networkpic.jpg
http://people.virginia.edu/~std6n/netflux/NetfluxWikiPics/Netflux2.jpg
'></a>

## Netflux for all ##

Netflux comes in two flavors:
  1. MATLAB Independent (For users without access to MATLAB)
  1. MATLAB Dependent (For users with access to MATLAB)

Documentation can be found [here](http://code.google.com/p/netflux/downloads/list).

Current version is **0.07 alpha**