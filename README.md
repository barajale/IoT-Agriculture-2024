# IoT-Agriculture-2024

Lets use some basic data science to learn git!

# Good practices

- Always pull before you push
- Use a branch, never push to master
- Use commit messages that make sense (brief, clear, interpretable)
- Use enviroment like conda or virtualenv

# How to connect to github with SSH

- To easily use github from the terminal you need to connect your computer to github with SSH
- You can find some handy steps at the following links
  - Generating an SSH key [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
  - Connecting to github [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=windows)

# How to use git

- `git clone  <url>`
  - To pull this repo try `git clone git@github.com:barajale/IoT-Agriculture-2024.git`
- `git pull <branch>`# "pull" / download the most recent changes of your branch
- `git branch` # get a list of available branches and show you which one you are currently on
- `git checkout <branch>` # switch to an existing branch
- `git checkout -b <branch>` # create a new branch
- `git add <file> ` # When a file is added it is put in a staging area so it can be "committed" to the repo
  - try to not use git add . and specify the files
- `git status` # Get a list of currently staged changes
- `git commit -m "message"`
- This [doc](https://education.github.com/git-cheat-sheet-education.pdf) has some more handy basic commands

# How to use conda

- `conda create -n <env_name> python=3.8` # create a new enviroment with pythion 3.8
- `conda activate <env_name>` # activate the enviroment
- `conda install <package>` # install a package

# packages you should install

- jupyter
- pandas
- numpy
- matplotlib
- kagglehub

# Using an IDE like Visual Studio Code, PyCharm or Jupyter Notebook is best

- I would avoid install packages within the IDE, use the terminal instead
