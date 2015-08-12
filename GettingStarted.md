Netflux comes in two flavors:
  1. MATLAB Independent (For users without access to MATLAB)
  1. MATLAB Dependent (For users with access to MATLAB)

As such, there are two different ways to get started.  Choose the link below that best describes you.



# MATLAB Independent #
## Installation ##
  1. Download and extract Netflux.zip to your desired directory. The contents of this zip file are:
    * Documentation
    * exampleNet.xls – An example Network Excel File
    * license.txt – license for the program
    * Cytoscape\_vizmapper.props – visual property file for Cytoscape
    * Netflux.exe
  1. Download and install MATLAB Component Runtime 4.11 (file can be found [here](http://people.virginia.edu/~jjs3g/netflux/MCRInstaller_Windows4p11.exe))

## Starting Netflux ##
  1. Double click Netflux.exe to start the GUI
  1. In the File menu, select Open Model. A dialog box will prompt you for an Excel file that contains your network; input your network Excel file (or exampleNet.xls if you do not have one).
  1. The [GUI](GUIOverview#GUI.md) Status Text will indicate that your file was loaded successfully.






# MATLAB Dependent #
## Installation ##
  1. Download and extract NetfluxSC.zip to your desired directory. The contents of this zip file are:
    * Documentation
    * exampleNet.xls – An example Network Excel File
    * license.txt – license for the program
    * Cytoscape\_vizmapper.props – visual property file for Cytoscape
    * Netflux.m – The main Netflux program
    * +gui - m files needed for the Netflux Gui
    * +util - m files needed for Netflux to run

## Using Netflux with MATLAB ##
  1. Run Netflux.m.
  1. In the File menu, select Open Model, then input your network Excel file.
  1. The [GUI](GUIOverview#GUI.md) Status Text will indicate that your file was loaded successfully.