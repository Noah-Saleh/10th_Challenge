# 10th_Challenge  

---

NOTE: This is technically my 8th challenge, but I'm calling it the 10th because my 1st group project for Bootcamp Spot replaced 2 challenges.

### For those who don't know:  
Principal Component Analysis (PCA) is a technique that reduces the dimensionality of a data set. In this analysis, I reduced  
8 dimensional (7 dependent variables, 1 independent variable) data to  
4 dimensional (3 dependent variables, 1 independent variable) data. Each of the 3 new variables is a consolidation of some of the 7 old variables; this consolidation is based on which variables are similar. Obviously the units for each new variable are fuzzy, but the numerical values are still meaningful, as they preserve *most* of the information. This consolidation is done automatically through a library, but if you're curious, one performs PCA through a linear combination.

---

## Summary of Purpose  

This is not a program. 

This is just an analysis of the impact of using PCA when trying to group data into clusters.  

---

## Required/Compatible Technologies

**Compatible OS's:** Mac, Windows, or Linux  
**Programming language:** Python inside of Jupyter Lab  
**Required libraries:**  
    pandas ,  
    hvplot.pandas ,    
    Path from pathlib ,  
    KMeans from sklearn.cluster ,  
    PCA from sklearn.decomposition ,  
    StandardScaler from sklearn.preprocessing ,  

Using a conda environment from anaconda is preferable.

To view it, download the repository & open it with Jupyter Lab or some program that can run .ipynb files (e.g. VS Code using some extensions/add-ons). The cells should have already been run. If some haven't been run, then restart the kernel and run all the cells.

---

## Contributors

Noah Saleh

email: noahgsaleh@gmail.com

---


