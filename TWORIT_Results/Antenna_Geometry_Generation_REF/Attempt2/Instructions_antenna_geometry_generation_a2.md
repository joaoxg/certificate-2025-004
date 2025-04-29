``` 
>> REF
Select, 1: Cascaded cylinders, Select, 2: Cylinder base with Cascaded Cone structure: 1
Number of cylinders you want: 3
Radius of  Element 1 in [m]: 2e-2
Length of  Element 1 in [m]: 2e-2
Relative permittivity of   Element 1 [1]: 1
Relative permeability of   Element 1 [1]: 1
Radius of  Element 2 in [m]: 3e-2
Length of  Element 2 in [m]: 3e-2
Relative permittivity of   Element 2 [1]: 1
Relative permeability of   Element 2 [1]: 1
Radius of  Element 3 in [m]: 4e-2
Length of  Element 3 in [m]: 2e-2
Relative permittivity of   Element 3 [1]: 1
Relative permeability of   Element 3 [1]: 1
Do you want to plot the Geometry?: Select 1 for YES, Select 2 for NO, Default is NO: 1
=======================================================
Plotting the Antenna Geometry
Input the start frequency of the operation in [GHz]: 5
Input the end frequency of the operation in [GHz]: 10
Input the number of frequency points you need: 200
 Smart mode selection strategy starts: 
 Smart mode selection strategy ends: 
Want to print the modes? 1 for YES, 0 for NO [0]: 0
Give 0 is you agree with this options, 1 if you want to reintroduce them [0]:0
Calling the S parameter function: 
====================================================================================================
The number of cylindrical elements to solve for General Scattering Matrix: 
3
Number of waveguide Junction problems to be solved: 
2
Number of modes for all waveguides in succession: 
8  20  32
Junction
Junction
     1

of
     2

     2

of
     2

Frequency Iteration: 1 ... 200

S Parameters Computed: 
Save Data Section: 
Do you want to save the Geometry in a file? 1 for Yes, 0 for No: [1]: 1
Selct the folder in the UI: 
Input the file name you want: Use single quotes when writing file name such as: 'Test': '3DPlot_Antenna_Geometry_a2'
Data saved in/path/3DPlot_Antenna_Geometry_a2.mat
For plotting the Geometry from a mat file, please use Plot_Geomat.m File
Save Data Section: 
Do you want to save the results in a file? 1 for Yes, 0 for No: [1]: 1
Selct the folder in the UI: 
Input the file name you want: Use single quotes when writing file name such as: 'Test': 'Antenna_Geometry_Results_a2'
Data saved in/path/Antenna_Geometry_Results_a2.mat


>> Plot_Geomat
Do you want to plot the Geometry from a mat file? : 1 for Yes, 0 for No: [0]: 1
===========================================================
Plot section: 
========================File Selection===================================
User selected in/path/3DPlot_Antenna_Geometry_a2.mat

```