Knowledge and Data final project group 76
In this README we will explain how to run our Jupyter Notebook designed to help the user find them the perfect artmuseum in Amsterdam. 

########### setting up the repository 
You will need to use GraphDB to run a local SPARQL endpoint in order to use our application. 
First open GraphDB and create a new 'GraphDB Free' repository, name it however you prefer.
For the ruleset choose the option 'owl-max (optimized)'.The rest of the settings can be left on default. 
It is important to note that the repository must be set as active.
After setting up your repository, please upload the two included Turtle files 'ontology.ttl' and 'external-ontology-1.ttl' and make sure to import them. 
For the final step, click on the GraphDB logo and copy the repository URL. This URL will be needed to run the application smoothly.. 

########### setting up the notebook
Before you open the notebook, please make sure you have the following installed:
Note that varying versions may work but have not been validated.
python version 3.9.1 
pandas version 1.3.3
folium version 0.12.1
geopy version 2.2.0

Open the notebook 'Group 76 - Final Project.ipynb' in your favorite notebook editor like jupyterlab or visual studio code. 
For each cell marked 'SPARQL' change the URL and the repository name in the second line to the URL you copied from GraphDB. 
For example 'http://CHANGE-THIS-URL:7200/repositories/CHANGE-THIS-NAME' -> 'http://computer-name:7200/repositories/YOUR-REPOSITORY-NAME'
We suggest you use a find and replace function to change all cells in one go.

########### using the notebook
Cells marked 'SETUP' and 'SPARQL' are meant to be run only once, if they are accidentally run twice you should restart/rerun the whole notebook.
Cells marked 'USER' are meant to be interacted with by the user, they can be run multipe times and contain information on how to use them. 
