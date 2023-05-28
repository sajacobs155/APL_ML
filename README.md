# APL_ML
Repository for data used in machine learning paper
The first file (named ML_Input.txt) has the network inputs:
Column    Parameter
1         The offset (D) of the SiN layer
2         The dopant concentration D1
3         The dopant concentration D2
4         The end of the cap layer (in micrometers). The cap layer starts at 13.032 micrometers
5         The end of the Ti layer (in micrometers)
6         The dopant concentration D3
7         The dopant concentration D4
8         The dopant concentration D5
9         The dopant concentration D6
The dopant concentrations are given as values between 0 and 1000. A value of 0 corresponds to a dopant concentration of 2E 16 /cm^3. A value of 1000 corresponds to a dopant concentration of 2E19 /cm^3.
The second file (named ML_Output.txt) has the data labels (the mode properties that are needed to compute the threshold gain):
Column    Parameter
1         The effective index of the fundamental mode
2         The loss of the fundamental mode (in inverse cm)
3         The confinement factor of the fundamental mode
4         The reflectivity of the fundamental mode
5         The effective index of the first higher-order mode
6         The loss of the first higher-order mode (in inverse cm)
7         The confinement factor of the first higher-order mode
8         The reflectivity of the first higher-order mode
