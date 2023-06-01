# Repo for 2023 python course
Tutorial on pandas.

[link to binder](https://mybinder.org/v2/gh/LeonieMei/python-course-2023/HEAD)

You can find a quick intro to Jupyter notebook [here](https://www.dataquest.io/blog/jupyter-notebook-tutorial/).

## Setting things up

* clone git repo from https://github.com/LeonieMei/python-course-2023: 
	* `cd` into directory that you want the repo to exist in
	* `git clone git@github.com:LeonieMei/python-course-2023.git`
* create a `conda` environment with all the necessary libraries
	* `cd` into python-course-2023
	* create the environment from `data/environment.yml`
		* `conda env create -f data/environment.yml`
	* alternatively:
		* create and activate a new empty `conda` environment:
			* `conda create --name python-course-pandas python=3.10
			* `conda activate python-course pandas`
		* ... or activate an existing environment:
			* `conda activate existing-environment`
		*  install all the necessary packages manually:
			* `conda install pandas`
			* `conda install openpyxl`
			* `conda install matplotlib`
			* `conda install seaborn`
			* `conda install numpy`
			* `conda install jupyter`
			* `conda install -c conda-forge jupyter_contrib_nbextensions`
	 * start `jupyter notebook`:
		 * `jupyter notebook`
