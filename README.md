# Using Jupyter Notebook and Conda Environments for iPython Code Execution

## Steps to get started
1. [Download and install Miniconda/Conda](https://conda.io/miniconda.html).
2. Create the necessary Conda environment.  Specific install instructions are contained within each repository.  
3. Clone/download files in repository onto your computer.
4. Activate the Conda environment from the command line terminal on your computer (command: `source activate EnvironmentName`).
4. Launch Jupyter Notebook from the command line terminal on your computer (command: `jupyter notebook`).  We have included jupyter notebook installation in the conda environment installation.
5. From Jupyter Notebook, navigate to the iPython files and open them.  You can now run the code!  If you're new to Jupyter Notebook, you might check out some online tutorials.  There are tons.  [Here's one very simple one.](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)

### What is a Conda Environment?  
Conda is a package and environment manager that provides a convenient way to utilize different versions of Python and Python packages for different applications.  To give an example, perhaps a given application (Application1) was written using Python version 2.5 and MyPackage version 1.1.  Alternatively, a different application (Application2) was written with Python version 3.5 and MyPackage version 3.1.  Additionally, Application1 and Application2 won’t run using the alternative versions of Python and MyPackage.  This could quickly become a major pain.  What Conda allows one to do is create different ‘environments’ on your computer, each with different versions of Python and any other packages, which you can then flexibly activate.  That is, I could have an environment for Application1 and an environment for Application2, and all I have to do is activate the Conda environment for Application 1 to use it, and all this requires is a single command!

### Installing Conda and Creating a Conda Environment: 
Unless you have a reason for utilizing the full version of Anaconda, we recommend installing [Miniconda](https://conda.io/miniconda.html) which requires substantially less disk space.  Creating and activating a conda environment is easy to do using very few terminal commands.  See [here](https://conda.io/docs/user-guide/tasks/manage-environments.html) for details.  For each repository we have listed the terminal commands necessary to created the needed conda environment.

### What is Jupyter Notebook?  
Jupyter notbeook is an interactive development platform for programming.  It is in some ways similar to other text editors but has a much more logical flow.  Code is organized into distinct ‘cells’ or chunks of code that can be independently run in the order of the user’s preference, and output is displayed just below each cell.  This allows the user to step through the code in a manner that is intuitive and view the results as they go along.  It also makes debugging during development easy. 

