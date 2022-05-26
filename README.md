# About Me
I like to solve data problems. I've been coding since I was in high school back in the 2000's. I started by reading books from microsoft back when they still published books. I practiced using vb6 because it was free. Later I went into C#, SQL. Now I do python, a little bit of rust, and I'm learning Julia. I love free stuff so open source is the way to go. 

## Education
I am interested in automation and design. I view computer science as a tool that can help achieve that. I believe that the next leap in aeronautics will be in AI. We won't be able to get there without sharing data, and codes with excellent tutorials. The next generation of engineers will have to be both proficient in Data Science as well as engineering. 

Below is my education summary: 

BS Aeronautical Engineering
Purdue University Dec 2010


MS Aeronautical Engineering
Purdue University Jun 2015 (not sure on the year, I skipped graduation) 


PhD Aeronautical Engineering
Research Topic: Bio-inspired design of gas Turbine Blade 
Purdue University Dec 2019
[Thesis Link](https://hammer.purdue.edu/articles/thesis/Bio-inspired_Design_of_a_Turbine_Stage/10055423)

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

# Contributions to Open Source Projects
### [GlennOPT](https://github.com/nasa/GlennOPT) 
This is an Optimization Framework that is similar to [CADO](http://www1.dem.ist.utl.pt/engopt2010/Book_and_CD/Papers_CD_Final_Version/pdf/01/01297-01.pdf) except it is free and opensourced. It can be used to launch design optimizations on a super computer with Torque or Slurm queuing system. This is useful for generating designs to be used with machine learning. 

### [Plot3D Utilities](https://github.com/nasa/Plot3D_utilities)
This library seeks to help people connect mesh with solvers. Plot3D is a mesh standard developed by NASA. You can think of it as a block with 6 sides. With this type of geometry, you can wrap it to create an o-mesh or stretch it to create a H-mesh. Different blocks can be connected forming a shape. Information can be exchange through the connected sides of the blocks. This python tool can be used to automatically find the connectivity and periodic faces of the block; these are the informations that a Computational Fluid Dynamic (CFD) solver requires. 

### [PeTaL Labeller](https://github.com/nasa-petal/PeTaL-labeller)
The petal labeller is a project that seeks to categorize biomimicry papers for engineers. Engineers are interested in lifeforms that have great thermal resistance, structural rigidity, ability to stick to things under water, etc. Life has has millions of years to evolve into the best version of itself. We as humans are in the beginnings of all our designs. If we can based designs off nature's evolution then perhaps we can have highly efficient airplanes with flapping wings or drones that look like bugs. Nature is one of our most valuable resources. There are many researchers dedicated towards understanding nature. Engineers often do not look at biology papers or know their terminology but we would like to search them. The goal of this tool is to help enable that. 

## [Airfoil-learning](https://github.com/nasa/airfoil-learning)
Airfoil Learning is a repository containing a tutorial on how to use Graph Neural Networks to predict coefficients of lift, drag, and moment. Graph Networks are a convolutional type of network that works with acyclic and cyclic graphs making the  useful in understanding the connection of points or point clouds. 



