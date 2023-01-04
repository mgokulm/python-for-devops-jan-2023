# python-for-devops-jan-2023
From Zero Repository for doing Python DevOps work

## Create a project scaffold

* Create development environment that is cloud-based:

### Colab Notebook

* This is an example of how to use [colab](https://colab.research.google.com/github/mgokulm/python-for-devops-jan-2023/blob/main/getting_started_python.ipynb#scrollTo=7AktpJo785Tc)

### Github Codespaces

Build out python project scaffold:

* Makefile
* requirements.txt
* test_library.py
* python_library
* Dockerfile
* command-line-tool
* Microservice

1. Create a virtualenv: 'virtualenv ~/.venv'
    More control over where python puts packages, eleminate issues with software/package installation

2. edit my '~.bashrc' 
    so that venv is activated when you open up terminal
    vim ~/.bashrc
    Add line to end - source ~/.venv/bin/activate
    Open a new terminal to check if your venv is automatically activated/loaded

3. Psuh changes to git
    git status - to check what are the changes
    git add *
    git commit -m "adding structure"

4. to see what are the packages installed in your env
    pip freeze | wc -l



### AWS CloudShell
### AWS Cloud9

## Command-line Tools

## Microservices

## Containerized Continuous Delivery
