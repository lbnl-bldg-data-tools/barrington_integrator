# barrington_integrator
Generate FieldServer config files from Barrington Reader 3 output files

## Purpose 
The goal of this project is to have a general pipeline to merge files from Barrington
files and FieldServer config files to files acceptable by BACnet.

## Getting Started
The primary source file to run is webserver.py.
It contains a Flask application that runs a webserver on localhost:8080, 
which is where the AquiSuites will be pushing data to.
Note that the first few cells have certain inputs for respective files, which need
to be in the local directoary. The Barrington file is currently there, but future
FieldServer config files need to be uploaded.

### Prerequisites 
Code runs with Python 3.6 and above. Note that the main file runs in a Jupyter Notebook. 

## Deployment
Project is deployed by inputting the files necessary and running all cells.  

### Running
Simply run the cells like a normal Jupyter Notebook.

## Authors
* **Thomas Huo** - *Data Engineer* - [Thomas Huo](https://github.com/JinhaoHuo)

## Acknowledgements 

* Chris Weyandt - provided data for the project and helped with conceptualization 

* Erik First - gave information on relationship between files, provided direction, and helped with ideas on merging files
