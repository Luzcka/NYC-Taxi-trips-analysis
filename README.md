# NYC-Taxi-trips-analysis
# A simple analysis

## The final report including results and code you can find opening the file "Data_Sprints_Final.html" 

Obs.: Inside the "Reports" directory you can find reports gerated by a EDA library.


### Preparing the environment

- You need to have the Anaconda distribution installed, if you don't have it, please follow the steps on the following website: <https://www.anaconda.com/products/individual#Downloads>

- It is advised to use a separate development environment, follow the steps below.
 - Open your terminal and run the following commands:
  - conda create -n dataenv python=3.7 pylint 
  - conda install nb_conda
  - conda install -c anaconda numpy
  - conda install -c anaconda scipy
  - conda install -c anaconda unidecode
  - conda install -c anaconda pandas 
  - conda install -c anaconda markdown
  - pip install jsonlines
  - conda install --channel conda-forge geopandas
  - conda install -c conda-forge descartes
  - pip install sweetviz
 - Inside the terminal you must clone this repository to the location of your choice. Execute the command below.
  - git clone https://github.com/Luzcka/NYC-Taxi-trips-analysis.git
  - Enter to the directory "NYC-Taxi-trips-analysis".
  - Activate the "dataenv" environment using: conda activate dataenv
  - First of all you need to put in this directory the data files, you can find the links to download in the PDF file Located inside "Docs" directory.

### Execution
- Open Jupyer Notebook using the command (Linux): jupyter notebook
- Inside the Jupyer UI you can open the  solution file clickin on "Data_Sprints_Final.ipynb".
- To execute every cell code you can use [CTRL]+[ENTER] keys combination. But if you don't want it you can only navegate on this file and see the results.






