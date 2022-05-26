# Crypto Portfolio Proposal

This program uses clustering and the K-Means algorithim to find the best crypto portfolio strategy to propose. The program clusters cryptocurrencies by their performance in different time periods and plots the results to show their performance.

----

## Technologies
This application is written in Jupyter Lab Notebook in the Python programming language. The Python libraries, tools, and modules used in this application are Pandas, hvPlot, and scikit-learn.

[Pandas](https://pandas.pydata.org/docs/index.html),[hvPlot](https://hvplot.holoviz.org/),[scikit-learn](https://scikit-learn.org/stable/user_guide.html) 


----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

This program also uses hvPlot and scikit-learn. To confirm that theses libraries are installed in your environment, open a terminal window and complete the following steps:

1. Activate your dev environment

2. Run the following command to ensure installation:

        conda list scikit-learn
        
        conda list hvplot
        
If scikit-learn and hvPlot are successfully installed, 'scikit-learn' and 'hvplot' along with their version number will display in your terminal.

If one or both are not installed, complete the following steps:

1. Run the following command to install scikit-learn:

        pip install -U scikit-learn
       
2. Run the following command to install hvPlot:

        conda install -c pyviz hvplot
        
6. Confirm the installation:
    
        conda list scikit-learn
        
        conda list hvplot
        
If scikit-learn and hvPlot are successfully installed, 'scikit-learn' and 'hvplot' along with their version number will display in your terminal.
    
*This program is run in an Anaconda environment. Installation for libraries may be different for other environments. User may follow the installation guide for scikit- learn [here](https://scikit-learn.org/stable/install.html), and hvPlot [here](https://hvplot.holoviz.org/developer_guide/index.html).*

----

## Usage
For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import pandas as pd
    
    import hvplot.pandas
    
    from path import Path
    
    from sklearn.cluster import KMeans
    
    from sklearn.decomposition import PCA
    
    from sklearn.preprocessing import StandardScaler


**The program is comprised of 4 parts:**

1. 

2. 

3. 

4. 


----

## Contributors

Arlie Jones

[E-mail](arliejones98@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/arlie-jones-020092159/)

----

## License

None
