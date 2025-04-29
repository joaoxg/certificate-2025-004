### Preparation steps

 - Install Matlab 2023b in your machine
 - Download most recent version of code repository [here]https://data.4tu.nl/datasets/e06f14b2-d884-4d1a-88fd-4ee8ebc3a98e/1), e.g. by running `git clone` command shared at the bottom of the page
 - Open installed Matlab version

### Reproduce Results

#### Antenna Geometry Generation
 
 - In Matlab, navigate to the main folder of code repository
 - In the Command Window, run `REF` and follow instructions. Bellow you can find the instructions the codechecker followed in 3 different attempts:
  1. in [Attempt 1](./TWORIT_Results/Antenna_Geometry_Generation_REF/Attempt1/Instructions_antenna_geometry_generation_a1.md), the codechecker followed the same exact instructions as shared at the end of the code repository's README
  2. in [Attempt 2](./TWORIT_Results/Antenna_Geometry_Generation_REF/Attempt2/Instructions_antenna_geometry_generation_a2.md), the codechecker followed the same instructions but requested 200 frequency points instead of 100
  3. in [Attempt 3](./TWORIT_Results/Antenna_Geometry_Generation_REF/Attempt3/Instructions_antenna_geometry_generation_a3.md), the codechecker followed the same instructions but switched the instructions the radius and length between Elements 1 and 3.

#### Display geometry figure in README

 - In Matlab, navigate to the main folder of code repository
 - In the Command Window, run `Plot_Geomat` and follow instructions for the [first figure](./TWORIT_Results/README_Geometry_Figure/Instructions_readme_1stgeomfig.md) displayed in the code repository's README.