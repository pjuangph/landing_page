# About Me
I enjoy talking to computers. I’ve been coding since high school in the 2000s. Initially, I learned by reading books published by Microsoft. I practiced using Visual Basic 6 because it was free. Later, I transitioned to C# and SQL. Currently, I work with Python, a bit of Rust, and I’m currently learning Julia. Since I value free resources, I prefer open-source software. 

## Education
I am interested in automation and design. I view computer science as a tool that can help achieve that. I believe that the next leap in aeronautics will be in AI. We won't be able to get there without sharing data, and codes with excellent tutorials. The next generation of engineers will have to be both proficient in Data Science as well as engineering. 

Below is my education summary: 

PhD Aeronautical Engineering
Research Topic: Bio-inspired design of gas Turbine Blade 
Purdue University Dec 2019
[Thesis Link](https://hammer.purdue.edu/articles/thesis/Bio-inspired_Design_of_a_Turbine_Stage/10055423)

MS Aeronautical Engineering
Purdue University Jun 2015 (not sure on the year, I skipped graduation) 

BS Aeronautical Engineering
Purdue University Dec 2010

# Public Repository Summary

## Bash 
### [Lock-file-testing](https://github.com/pjuangph/Lock-file-testing) 
When you are running and using licenses on a super computer, sometimes you don't have enough licenses. This is an example built in shell to demonstrate how you can create a lock file so that one execution at a time uses a license or in my case, i create about 8 lock files for 8 licenses. 


## Fortran 
### [Fortran-cmake-unit-tests](https://github.com/pjuangph/fortran-cmake-unit-tests)
This repository describes how to use fortran with cmake and apply unit tests with CTests

### [Fortran](https://github.com/pjuangph/fortran)
This repo was made before I learned about cmake. I used this repo to tryout fortdepend. fortdepend helps generate the dependancies for the makefile. Makefiles are very particular about what is built in what order. You need all the dependancies built first then the main code but waht happens when dependancies depend on other dependancies. This is where you use fortdepends
I also document how to install and configure your linux environment for nvfortran. 

# Contributions to NASA Open Source Projects
### [Airfoil-learning](https://github.com/nasa/airfoil-learning)
Airfoil Learning is a repository containing a tutorial on how to use Graph Neural Networks to predict coefficients of lift, drag, and moment. Graph Networks are a convolutional type of network that works with acyclic and cyclic graphs making the  useful in understanding the connection of points or point clouds. 

### [GlennOPT](https://github.com/nasa/GlennOPT) 
This is an Optimization Framework that is similar to [CADO](http://www1.dem.ist.utl.pt/engopt2010/Book_and_CD/Papers_CD_Final_Version/pdf/01/01297-01.pdf) except it is free and opensourced. It can be used to launch design optimizations on a super computer with Torque or Slurm queuing system. This is useful for generating designs to be used with machine learning. 

### [PeTaL Labeller](https://github.com/nasa-petal/PeTaL-labeller)
The petal labeller is a project that seeks to categorize biomimicry papers for engineers. Engineers are interested in lifeforms that have great thermal resistance, structural rigidity, ability to stick to things under water, etc. Life has has millions of years to evolve into the best version of itself. We as humans are in the beginnings of all our designs. If we can based designs off nature's evolution then perhaps we can have highly efficient airplanes with flapping wings or drones that look like bugs. Nature is one of our most valuable resources. There are many researchers dedicated towards understanding nature. Engineers often do not look at biology papers or know their terminology but we would like to search them. The goal of this tool is to help enable that. 

### [Plot3D Utilities](https://github.com/nasa/Plot3D_utilities)
This library is used inform CFD solvers of how the faces of each block/cube in a mesh is connected with other blocks. Plot3D is a mesh standard developed by NASA to represent computational domains as sets of structured blocks with 6 sides. With this type of geometry, you can wrap it to create an o-mesh or stretch it to create a H-mesh. Different blocks can be connected forming a shape. Information can be exchange through the connected sides of the blocks. This python tool can be used to automatically find the connectivity and periodic faces of the block; these are the informations that a Computational Fluid Dynamic (CFD) solver requires. 

### [Plot3D_Julia](https://github.com/nasa/plot3d_julia)
Same as plot3D python but rewritten to work in Julia because Julia is awesome like that.


### [PyTurbo-Aero](https://github.com/nasa/pyturbo-aero) 
Turbine Blade shape design tool. This tool allows for the entire airfoil shape to be designed in 2D then stacked to build a 3D geometry. This tool also allows for the flowpath to be created and blades positioned and stretched to match the streamline curvature.

### [Turbo Design](https://github.com/nasa/turbo-design) 
This is a code that solves the radial equilibrium equations. It is used to design Axial/Centrifugal Turbines, Compressors. The purpose of this project is to enable machine learning loss models to be integrated. 

### [ShockTube-AUSM](https://github.com/nasa/shocktube)
Implemented and corrected a minor detail in the AUSM scheme. This project shows the application of AUSM and AUSM+ to a shocktube application. 

## Machine Learning Projects
I treat machine learning like learning a new language. At first you speak the sentences from the book, how to order food, donde esta la biblioteca; but later as you get more comfortable, you learn new words and build your own sentences. To learn sentences, I dive into other people's code and try to understand what's being passed into what, what's the size and structure of the data, how do you visualize the data, and document the network model so that one day I can develop my own unique architectures. 

### [Mesh Graph Networks](https://github.com/pjuangph/MGN) \(MGN Pytorch Library\)
Added documentation and plotting. Documentation added includes the dataset, inputs and outputs of the model, code to automate the plotting and viewing of the results, the model architecture. Overall, this should help people who are new to Graph Networks understand how to structure their datasets and also understand the limitations of this type of network architecture. 

### [Probe ML](https://github.com/nasa/multihole-probe-calibration)
Example of how to calibrate a 5 hole probe using machine learning (MLP, KAN). This code supplements paper.
Mirhashemi, A., Juangphanich, P., & Miki, K. (2024, June). Application of Machine Learning Techniques in Calibration and Data Reduction of Multi-Hole Probes. In Turbo Expo: Power for Land, Sea, and Air (Vol. 87967, p. V004T05A044). American Society of Mechanical Engineers.

### [How to beat a 10 year old girl in battleship using Transformers](https://github.com/pjuangph/battleship)
Blog will be added soon
