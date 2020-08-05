# **RadVis-Plotly Example**

## Contributors: 
   - [x]  **Abdelrahman Elewah**
   - [x]  **Abeer Badawi**
   - [x]  **Haytham Aboulabbas**
   
**Submitted to: Prof. Shahryar Rahnamayan**  
## **We propose a RadViz3D visualization method, we distributed uniformly the N points on the surface of the sphere, then we obtained formulas for x, y, and z mappings using scatter 3D method.**

## *Follow the below simple steps to run the code:*

### 1- open the following link [link to the code in jupyter notebook](https://mybinder.org/v2/gh/elewah/RadViz-Plotly-Examples/master)

### 3-you can now run any of the folders (the folders are named with the dataset name) with a total of 3 datasets

### 4- Example:
    * Open Iris Dataset folder
    * Check the dataset by clicking on the file called Iris.csv 
    * Open Abalone Data Set.ipynb to run the code, click on 'cell' tab and then 'run all' to run the code
    * The code consist of two parts
        1- The first part simply calls the core function
        2- The second part calls the dataset then divide the dataset to y (labels) and X (the variables)
        3- We assume the boundary points with 10000 point
        4- We call our function (RadViz3D) with the given inputs to plot the 3D and 2D visualization successfully
    * To see the plot more clearly you can click on 'sphere' in the legend (right of the figure) to remove the sphere boundaries and see more details in the figure.
    * Furthermore, you can click on any of the label names in the legend (right of the figure) to remove or add it again if you want to see specific labels in the plot.
    * Besides, you can zoom in and out by clicking on the left button of your mouse or laptop and move the touchpad. Also, you can move the figure placement by repeating the same steps except clicking the right button instead of the left.
        
### 5- Hint: To plot a 3D visualization the dataset should consist of one label only. Some of the datasets had more than one label so we used Label Encoder technique to Encode other labels with a range of values to plot them accurately ###


### 6-Locally Installing RadViz-Plotly package using pip command 
#### RadViz-Plotly package is released on 4 August 2020
#### The package repository on PyPI, click [here](https://pypi.org/project/RadViz-Plotly/)
#### To use this library locally please use this command
pip install RadViz-Plotly 