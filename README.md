# Project Type: Project Template
# Project Name : Template
this is scaffold template for python 
 Create the following:
 - Makefile
 - requirement.txt
 -Linux system:
    - virtial enviroment: python -m venv ~/.scrape
    - activate venv envi: source ~/.scrape/bin/activate
 - Windows system:
    - virtial enviroment: python -m venv c:\venv\scrapy
    - activate venv envi:   C:\venv\scrapy\Scripts\activate.ps1
 - hello.py file
 - test_hello.py file 
 - to check the python version:
    - in linux : which python  
    - in windows: Get-Command python | fl *
 - get pack version:
    - pip freeze | grep packName 
 - chanage bash to run venv :
    - vim ~/.bashrc
    - shift G to button, 
    -# Setup Virtual Env
    - source ~/.MLOps/bin/activate

## run jupyter notebook
  - jupyter noteboke: - install ipykernel
  - run command: - ipython kernel install --user --name=scrape
       
