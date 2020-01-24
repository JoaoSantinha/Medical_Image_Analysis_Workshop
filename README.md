Installation
------------

To set the virtual environment to run this tutorial we will use conda. If you do not have you can install one of these two options:
- `Anaconda (management system with some packages already built in) <https://docs.anaconda.com/anaconda/install/`_
- `Miniconda (management system without packages) <https://docs.conda.io/projects/conda/en/latest/user-guide/install/`_

Clone this repository or download the .zip file to your documents folder:
- clone repository in Windows:: 
  cd C:\Users\<current user>\Documents\
  git clone <repository_name>
- clone repository in Mac/Linux::
  cd ~/Documents
  git clone <repository_name>

Then create environment (called MIAW) and install required packages automatically::
  cd Medical_Image_Analysis_Workshop
  conda env create -f environment.yml
  
Activate environment and install required Jupyter Lab extensions::
  conda activate MIAW
  jupyter labextension install @jupyter-widgets/jupyterlab-manager jupyter-matplotlib jupyterlab-datawidgets itkwidgets