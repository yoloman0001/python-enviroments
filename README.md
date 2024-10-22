# python-enviroments
A repository with environment configuration (in yaml format) to work with python

## How to clone this repository
You can clone this repository in a local repository by using the following command:

~~~
git clone https://github.com/yoloman0001/python-enviroments.git
~~~

## Creating an environment from a yaml file
Using the package manager of Anaconda; **Conda**, you can run the following command to create an environment  
with the configuration specified in the .yml file

~~~
conda env create --file filename.yml
~~~

## How to run the code
After creating the environment from our .yml file, activate the environment

~~~
conda activate environment-name
~~~

With the environment active, execute the file with the **python** command

~~~
python filename.py
~~~

