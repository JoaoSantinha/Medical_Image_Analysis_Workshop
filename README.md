Installation
------------

1. To set the virtual environment to run this tutorial we will use conda. If you do not have you can install one of these two options:
  - [Anaconda (management system with some packages already built in)](https://docs.anaconda.com/anaconda/install/)
  - [Miniconda (management system without packages)](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

2. Clone this repository or download the .zip file to your documents folder (to clone the repository you need to have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) install): 
  - clone repository in Windows using the following commands on your command line (replace <current_user> by your user name):
  ```
    cd C:\Users\<current_user>\Documents\
    git clone https://github.com/JoaoSantinha/Medical_Image_Analysis_Workshop.git
  ```
  - clone repository in Mac/Linux using the following commands on your terminal:
  ```
    cd ~/Documents
    git clone https://github.com/JoaoSantinha/Medical_Image_Analysis_Workshop.git
  ```

3. Then create environment (called MIAW) and install required packages automatically:
  ```
    cd Medical_Image_Analysis_Workshop
    conda env create -f environment.yml
  ```
  
4. Activate environment and install required Jupyter Lab extensions:
  ```
    conda activate MIAW
    jupyter labextension install @jupyter-widgets/jupyterlab-manager jupyter-matplotlib jupyterlab-datawidgets itkwidgets
  ```
