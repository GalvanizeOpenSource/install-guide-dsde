
NOTE: these install instructions will install a Python 3 default environment with a Python 2 backup.


# PYTHON INSTALLATION GUIDE


## Install Python 3 as the default envrionment

If there is an old version of anaconda you can remove it with

   ```
   ~$ rm -rf ~/anaconda*
   ```
Download the latest Python 3.X image or install script from https://www.continuum.io/downloads


### On Ubuntu


1. install via the command line

   ``` 
   ~$ bash ~/Downloads/Anaconda3-4.4.0-Linux-x86_64.sh
   ```
   
Answer yes to the path adding question
   
2. Restart terminal


### On OSX


1. Run the installer on the downloaded image

Answer yes to the path adding question

2. restart terminal


## Then run this to create a working python 2 environment


   ```
   ~$ conda create -n py2 python=2 anaconda
   ```

To activate the python 2 environment

   ```
   ~$ source activate py2
   ```
   
To toggle back to a Python3 environment

   ```
   ~$ source deactivate py2
   ```
   
## Then ensure you can run Jupyter with Py2


   ```
   ~$ source activate py2
   ~$ conda install notebook ipykernel
   ~$ ipython kernel install --user
   ```
   
## Keeping conda up-to-date

   ```
   ~$ conda update conda
   ~$ conda update --all 
   ```
