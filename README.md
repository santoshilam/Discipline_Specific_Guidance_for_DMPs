# Discipline Specific Guidance for DMPs
h/t Nico and Jose for the worflow and design of the book. Apart from the actual content, the generation of the jupyter book is based on a fork of https://github.com/NZR/DS-BOK


Instructions on how to work with the JupyterBook (from the repo linked above)
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


