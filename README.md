# APL_ML
Repository for data used in machine learning paper
The first file (named ML_Input.txt) has the network inputs:
Column 1 is the offset (D) of the SiN layer; Column 2 is the dopant concentration D1; Column 3 is the dopant concentration D2; Column 4 is the end of the cap layer (in micrometers), which starts at 13.032 micrometers;
Column 5 is the end of the Ti layer (in micrometers); Column 6 is the dopant concentration D3; Column 7 is the dopant concentration D4; Column 8 is the dopant concentration D5; Column 9 is the dopant concentration D6.
The dopant concentrations are given as values between 0 and 1000. A value of 0 corresponds to a dopant concentration of 2E16 /cm^3. A value of 1000 corresponds to a dopant concentration of 2E19 /cm^3.
The second file (named ML_Output.txt) has the mode properties that are needed to compute the threshold gain: Column 1 is the effective index of the fundamental mode; Column 2 is the loss of the fundamental mode (in inverse cm); Column 3 is the confinement factor of the fundamental mode; Column 4 is the reflectivity of the fundamental mode; Column 5 is the effective index of the first higher-order mode; Column 6 is the loss of the first higher-order mode (in inverse cm); Column 7 is the confinement factor of the first higher-order mode; Column 8 is the reflectivity of the first higher-order mode.
