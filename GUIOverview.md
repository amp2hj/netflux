# Introduction #

Netflux provides a simple graphical user interface (GUI) for users to manipulate their network.

# Access #

Users can access the GUI in 2 ways:
  1. Without MATLAB, run Netflux.exe ([follow the instructions for 'MATLAB Independent'](GettingStarted#MATLAB_Independent.md))
  1. Using MATLAB, run Netflux.m ([follow the instructions for 'MATLAB Dependent'](GettingStarted#MATLAB_Dependent.md))



# GUI #


![http://people.virginia.edu/~jjs3g/netflux/NetfluxWikiPics/Figure_1.jpg](http://people.virginia.edu/~jjs3g/netflux/NetfluxWikiPics/Figure_1.jpg)

  1. **_Simulation Time_** – Input the time (in seconds) that you want to simulate your reaction. The time starts from the previous simulation time. For example, if you Simulated the reaction for 10 seconds previously, and Simulated again for 10 seconds, the Graph and Data will show for 20 seconds. “Reset Simulation” in order to start from time zero.
  1. **_Species to Plot_** – The species highlighted will be the species plotted in the graph. Control+click in order to plot multiple species at once. The plotting occurs after you push “Simulate!”
  1. **_Simulate!_** – Causes the simulation to occur
  1. **_Plot_** – Replot the graph without running through another time step. For example, you forgot to plot Species B with Species A and you do not want to go through another time step.
  1. **_Reset Parameters_** – Resets all species and reaction parameters.
  1. **_Reset Simulation_** – Resets the starting time to zero and clears the graph. Does **NOT** reset the parameters.
  1. **_Status Text_** – Displays various messages depending on your actions
  1. **_Species List_**  - A drop down menu for you to select which species to alter
  1. **_Tau_** – A slider bar for you to alter the reaction time constant parameter of your selected species
  1. **_Yinit_** – A slider bar for you to alter the initial y parameter of your selected species
  1. **_Ymax_** – A slider bar for you to alter the ‘ymax’ parameter of your selected species
  1. **_Reaction List_** – A drop down menu for you to select which reaction to alter
  1. **_Weight_** – A slider bar for you to alter the reaction weight parameter of your selected reaction
  1. **_n_** – A slider bar for you to alter the hill coefficient parameter of your selected reaction
  1. **_k_** – A slider bar for you to alter the half-maximal effective concentration parameter of your selected reaction
  1. **_Open Model_** – Loads an Excel file. Doing so will reset all parameters and graphs.
  1. **_Copy Plot_** – Copies the current plot in a separate window.
  1. **_Export Data_** – Exports the data for each species at one-second intervals into a text file for use in programs such as Cytoscape (http://www.cytoscape.org/).
    * Note a: the data are space delimited.
  1. **_Export Cytoscape Network_** – Exports the data for each species into _yournetworkmodel.sif_ and _yournetworkmodel\_nodeAttributes.txt_ for use in Cytoscape.
  1. **_Export ODE List_** - Exports the ODE list
  1. **_About Netflux_** - Displays the About window

