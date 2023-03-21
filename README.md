# Discipline Specific Guidance for DMPs

This repository is the home of the discipline specific guidance documents for data management plans, that were created and can be added to by the community for various disciplines. The initial output was created by the [Discipline Specific Guidance for DMPs WG](https://www.rd-alliance.org/groups/discipline-specific-guidance-data-management-plans-wg "RDA Working Group page"). It is the intention that the guidance will be archived with a DOI in Zenodo while the Jupyterbook will be accessible [here](https://santoshilam.github.io/Discipline_Specific_Guidance_for_DMPs/). 

_h/t Nico and Jose for the worflow and design of the book. Apart from the actual content, the generation of the jupyter book is based on a fork of https://github.com/NZR/DS-BOK_


Instructions on how to work with the JupyterBook (from the repo linked above)

# How to contribute

Since this DMP guidance resource is developed with the intention that it will be maintained by the community and that researchers in any discpline and from anywhere can contribute. The most direct way to add to this guidane is to submit a pull request which will be reviewed and then approved. The chapter1.md file contains the template, which can be used to create the guidance for a new discipline. If you would like to submit an change to an existing guidance document, that too can be submitted as a pull request.


# Pre-requisites

Despite trying to keep things simple, we will still be relying on several Python packages to build the book from our files... 

You will need: 
- Ananconda 

That's it! It will bring Python3, pip, and virtual environments which we will use.

# First steps

Copy the repository locally. 

Turn on the virtual env. 
	source use-cases/Scripts/activate

Install the requirements
	pip install -r requirements.txt
 
Run the book building process: 
	jupyter-book build ./book/



# Notes on the virtual environment

Because we'll be creating jupyter books, we will need a few tools to create the book. The easiest way to ensure we all have the same environment is by creating a virtual one. 

Technically, you won't have to create one, but reuse the one provided here. 

This is only feasible from a command line interface (for now). 

Open Git Bash (if you are using Windows), or the Terminal (on MacOS/Linux). Navigate to your working directory (the use-cases folder - your local copy of the github repo).
There, execute the following command: 
	
	source use-cases_env/Scripts/activate

"source" is an existing command which execute a script (_activate_ in this case), and keeps all modifications to the runtime environment. 
Usually, the environment is set for a program, and is unloaded once it has run - but here, we want those variables to be available to use (such as the path to python.exe!).



# how it was created: 
 
	virtualenv -p python3 use-cases_env

All scripts to "activate" the virtual environment will be in the use-cases_env/ folder. 


