# Using Jupyter Notebook and Conda Environments for iPython Code Execution
### What is a Conda Environment?  
Conda is a package and environment manager that provides a convenient way to utilize different versions of Python and Python packages for different applications.  To give an example, perhaps a given application (Application1) was written using Python version 2.5 and MyPackage version 1.1.  Alternatively, a different application (Application2) was written with Python version 3.5 and MyPackage version 3.1.  Additionally, Application1 and Application2 won’t run using the alternative versions of Python and MyPackage.  This could quickly become a major pain, uninstalling and reinstalling the correct Python/package versions so you can run a given application.  What Conda allows one to do is create different ‘environments’ on your computer, each with different versions of Python and any other packages, which you can then flexibly activate.  That is, I could have an environment for Application1 and an environment for Application2, and all I have to do is activate the Conda environment for Application 1 to use it, and all this requires is a single command!

### Installing Conda and Creating a Conda Environment: 
Unless you have a reason for utilizing the full version of Anaconda, I recommend installing Miniconda which requires substantially less disk space (https://conda.io/miniconda.html).  Creating and activating a conda environment is easy to do using very few terminal commands.  See here for details: (https://conda.io/docs/user-guide/tasks/manage-environments.html).  For each repository I have listed the terminal commands necessary to created the needed conda environment, at least when running on Mac.

### What is Jupyter Notebook?  
Jupyter notbeook is an interactive development platform for programming.  It is in some ways similar to other text editors but has a much more logical flow.  Code is organized into distinct ‘cells’ or chunks of code that can be independently run in the order of the user’s preference, and output is displayed just below each cell.  This allows the user to step through the code in a manner that is intuitive and view the results as they go along.  It also makes debugging during development easy. 

Note that in order to run Jupyter Notebook one must first install it in your Conda Enviroment

