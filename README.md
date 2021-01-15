# MScDM2020

Data Mining Project
209338R - KATS Jayathilaka
209379R - BPK Seneviratne

## **Instructions to run the code**

It is better to have a separate conda environment with python3. Follow the instructions to run the code.

1. [Install Anaconda](https://www.anaconda.com/products/individual)
2. Make sure conda is automatically added to
   - Environment variables in Windows OR
   - System path in Linux (Ubuntu)
3. Anaconda will come with a base environment with preinstalled Python3.8. You can that default base environment by activating it as follows.
   - `conda activate`
4. Or else, you can create your own separate anaconda environment with just for testing this assignment and delete that environment later.
   - `conda create -n yourenvname python=x.x anaconda`
5. To activate/deactivate your conda environment.
   - `conda activate yourenvname`
   - `conda deactivate`
6. ADDITIONAL STEP: To make sure Jupyter notebook and Ipykernel are installed in your conda environment.
   1. Check whether Jupyter notebok and Ipykernel
      - `conda list | grep notebook`
      - `conda list | grep ipykernel`
   2. If the above commands doesn't output anything to the terminal, install the packages as follows.
      - `conda install -c conda-forge notebook`
      - `conda install -c anaconda ipykernel`
7. Add your conda environment to jupyter notebook as a specific kernel as follows.
   - `python -m ipykernel install --user --name=yourenvname`
8. Install the following packages in the conda environment which are the dependencies of the assignment code.
   - `conda install -c conda-forge numpy`
   - `conda install -c conda-forge scipy`
   - `conda install -c conda-forge pandas`
   - `conda install -c intel scikit-learn`
   - `conda install -c districtdatalabs yellowbrick`
   - `conda install -c plotly plotly`
9. Now you can run the code cell by cell by at once.
10. You can change the configurations of the code and rerun also.
11. After finish grading the assignment, you can delete the conda environment you created if you want by the following command.
    - `conda remove -n yourenvname -all`
12. If you need any external assistance in conda environment setup, use this resource.
    - https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/
