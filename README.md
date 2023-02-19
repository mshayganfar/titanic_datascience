# Analysis of the Titanic dataset

This projects aims at analysing Kaggle's Titanic dataset and build a predictive model for the Titanic data science challenge.

The command line tool is run from the terminal using the following command — Note that the virtual environment titanic has to be active to run this command.

titanic_analysis --filename exploration/data/titanic.csv

Once a product is ready, most people just use the Python package without contributing to it. In this case, the package can be conveniently installed in a single line of code.

pip install -e 'git+https://github.com/mshayganfar/titanic_datascience.git#egg=titanic'

This commands installs only the titanic package, as specified in setup.py, and omits other files, like the exploration/ folder or requirements.txt.
