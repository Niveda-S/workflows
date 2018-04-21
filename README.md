This project provides an example of using ReactomeFIViz CyREST in a Python Jupyter notebook to perform a network comparison analysis between ovarian cancer and breast cancer using the TCGA mutation data sets.

## Prerequisites
* Python version 2.6 or later.
* Python pandas package version 0.22.0 or later.
* The latest version of Cytoscape with the latest version of the ReactomeFIViz app.

## Installation
* Install the required packages in a Python environment, e.g. in the Anaconda virtual environment:
    - conda create -n cytoscape pandas scipy statsmodels
    - source activate cytoscape
* Clone the example GitHub repository, e.g.:
    - mkdir ~/reactome-fi
    - cd ~/reactome-fi
    - git clone https://github.com/reactome-fi/workflows.git
    - cd workflows
    - The two TCGA MAF files were downloaded from the Broad Institute firehose server (http://gdac.broadinstitute.org) in April, 2018.
* In Cytoscape, select Help > Check for Updates to ensure that ReactomeFIViz is current.

## Usage
* Start Cytoscape.
* In a console, start Jupyter on the notebook directory, e.g.:
    - jupyter notebook --notebook-dir=~/reactome-fi/workflows
* Run all notebook cells in the web browser Jupyter window.
