
# How to run Jupyter notebooks

To run the notebooks you first need to install [Anaconda Python](https://www.anaconda.com/download/).

## Create a conda environment

The notebooks use various libraries that you need to install too to be able to run them. The best way to set this up is to create a conda environment with the proper libraries installed. To do that, copy/pasete this long command into your command prompt/Terminal and run it.

    conda create -c anaconda -c conda-forge -c bioconda --name pg2019 python=3 biopython jupyter matplotlib mpld3 nbconvert numpy pandas scikit-learn scipy seaborn statsmodels pytables pyfaidx

Press enter once asked if you want to install a long list of libraries. 

## Running Jupyter

Once it finished there are two ways to run Jupyter:

- On Windows the easiest way is to find and open the program called Anaconca Navigator. Then under "Home" you can choose the environment "pg2019" and then launch Jupyter.
- On linux and mac you can just type `source activate pg2019` or `conda activate pg2019` depending on your version of conda.

Jupyter opens a file browser. Navigate to the folder where you downloaded the notebook files from Blackboard and click on one of them. Then the notebook open and you can see the code.



