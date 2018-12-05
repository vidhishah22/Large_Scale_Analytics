# Large_Scale_Analytics
This repository is used for all the projects related to Large Scale Analytics



Machine Learning Model for Patterns Involved in Traffic Accidents

Our project uses some machine-learning models to predict the severity of fatality that occurred during traffic accidents. From this the patterns involved in dangerous crashes could be detected. These patterns can then be useful in the providing the recommendations and improving traffic safety control policies across the United States. The motivation behind the development of such a prediction model has a direct connection to our routine life where in we travel daily from our home to various destinations and whenever there is a crash or a road accident we think that of safety measures that could have been taken to avoid it.

1. Set Up
(A) For this project, firstly, you have to install Python, Anaconda and Jupyter Notebook on your system.
a) To install Python on Mac:
- Install Homebrew
- On terminal run the command: $ brew install python3
This will download and install the latest version of python
b) To install Anaconda on Mac:
- Go to https://www.anaconda.com/download/#macos
- Choose the python version for which you want to download
- Double-click the downloaded file and click continue to start the installation.
c) To install Jupyter Notebook on Mac for Python3:
- $ python3 -m pip install --upgrade pip
- $ python3 -m pip install jupyter
This will download the Jupyter Notebook on mac or if you have Anaconda already installed in your system then you can directly launch Notebook from there.

(B) Secondly, you need to install some python libraries.
- Numpy 
Go to your terminal and run the following command:
$ pip3 install numpy
If that gives you permission or IO errors try using sudo
$ sudo pip3 install numpy
- Matplotlib   
Go to your terminal and run the following command:
$ pip install matplotlib
- Seaborn
Go to your terminal and run the following command:
$ pip install seaboard
- Plotly
Go to your terminal and run the following command:
$ pip install plotly 
or 
$ sudo pip install plotly 
- SkLearn
Go to your terminal and run the following command:
$ pip install -U scikit-learn
- Graphviz
Go to your terminal and run the following command:
$ pip install graphviz
- Pydotplus
Go to your terminal and run the following command:
 $ pip install pydotplus
- Warnings
 Go to your terminal and run the following command:
 $ pip install warnings-plugin
 
 2. Run
  
 After done with all the installations, launch Jupyter Notebook. It will run on local server at localhost:8888. To work on notebook you have to follow the following steps :
- Open "ML_Model_Patterns_Traffic_Accidents.ipynb"
- Click on Kernel from top menu on the notbook
- Select "Restart and Run All"

 Notebook will run and display the run output for each cell. Here are some commands to run the Jupyter Notebook:
- To run a particular cell - press Shift + Enter
- To run the current cell and insert a new one below - press Alt + Enter
- To run current cell and enters command mode - press Ctrl + Enter
- To run the entire code - press ‘Run’ button
- The ‘Cell’ menu has a number of menu items for running code in different ways.
- Code is run in a separate process called the Kernel. The Kernel can be interrupted or restarted. You will get different options for this by clicking on the ‘Kernel’ button.
 
 3. Other Instructions for the Users:
 
 a) When a notebook is opened, its “computational engine” (kernel) is automatically started. Closing the notebook browser tab, will not shut down the kernel, instead the kernel will keep running until it is explicitly shut down. To shut down a kernel, go to the associated notebook and click on menu File -> Close and Halt.
 b) When the kernel dies unexpectedly, you have to stop the kernel or have to select ‘Restart and Run all’ by clicking on the kernel button.
 c) User can navigate through the section of the notbook using "Table of Contents"
