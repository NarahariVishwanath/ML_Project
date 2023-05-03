# ML Project end to end

### Setting up the environment for Project.


It is basically a good practice to create new environment for all the project that you work on.


For creating an environment we need to go to the directory in conda prompt by using commends 'cd H:'
It will change the directory and you need to go to your folder where you want to setup the environment.
Once you change the directory you need to type command "code .", which will redirect you to VS Code IDE.
Here you need to type the code "conda create -p vern python=="version number" -y" this code will create the new environment with name venv at that path.

The new environment is basically for this project and all the modules that we use are installed into this environmet which will help us out.

Activation of the environment can be done by "conda activate venv/"


### Github repository creating, cloning and sync with our environment.

After logging into the github account, create new repository give the relevent name of the project.
Type "git init" command to initialize the rmpty git repository.
Create a README.md file in environment. We can create README.md file at the environment or in github.
If creted in the environment then use the command "add README.md" which will add the README file to the repository.

After that run the command "git commit -m "First commit" "

git branch -m main

git remote add origin github_repository_link

to check if the repository is in sync with the environment execute the command git remote -v which will show you 2 linch one is fetch and the other is push.

If you are doing this for first time you need to setup your github account credentials by using the git global configuration.
The commands to do the above are "git config --global user.name "John Doe" "


After cofiguration is done you can push and pull the files from environment to repository and vise-versa to push we need to execute the command as "git push -u origin main"


### Initializing setup.py file.

1. Created src folder in which we cleated a '__init__.py' file. In Python, the `__init__.py` file is used to mark a directory as a Python package, making it possible to import modules and sub-packages from that directory. It is automatically executed when the package is imported. You can also use it to define some initialization code or package-level variables.

This __init__.py file is basically created in all the folders where we want to create the sub parts of codes. eg:- under component folder and pipeline folder we will add __init__.py file.

