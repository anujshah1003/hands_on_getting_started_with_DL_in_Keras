#To setup the deep learning following softwares/libraries need to be installed

  1. Anaconda 3 for windows - https://conda.io/docs/user-guide/install/index.html
                            - https://www.anaconda.com/download/
  2. python >=3.5 (default 3.6 is installed , to get 3.5 create a anaconda environment)
  3. Pandas (will be default installed by anaconda)
  4. scikit-learn (default installed by anaconda)
  5. numpy (default installed by anaconda)
  6. opencv >= 3.3
  7. tensorflow = 1.4.0
  8. keras - 2 - https://keras.io/
  
#To create an anaconda environment
  
  conda create -n env_name(eg py35) python=3.5
  
  ## To activate environment
    activate env_name
    
To install and uninstall libraries using pip and conda
    
    # Using pip
    pip list
    pip install lib_name
    pip install lib_name==ver
    pip uninstall lib_name
    
    # Using conda
    conda list
    conda install lib_name
    conda uninstall lib_name=ver
    conda uninstall lib_name
    
 Installing libraries for our DL environment
 
    pip install opencv-python==3.3.0.10 
    pip install tensorflow==1.4.0
    pip install keras


  
