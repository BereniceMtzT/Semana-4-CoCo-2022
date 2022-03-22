# CoCo2022: Learning Exploratory Data Analysis with Seismic Data 
_by [Berenice](https://github.com/BereniceMtzT) and [Mich](https://github.com/sainosmichelle)_
    
    
## About

In this notebook we are going to learn how we can solve research questions using Python, specifically the Plotly library, this Notebook is part of the [crash course of data science for Geosciences] (https://github.com/sainosmichelle/sainosmichelle.github.io).

In this example we will use historical seismic data. This database is a collection of more than 23,000 earthquakes in USA. It contains data from 1638 to 1985. The database includes information corresponding to the coordinates of  epicenter, magnitudes, focal depth, names, coordinates of reported cities, reported intensities and the distance from the city to the epicenter. More information on this dataset can be found at [Kaggle](https://www.kaggle.com/srijya/us-earthquake-intensity-database).

The idea is not to become experts in seismology, this topic will be a great excuse to <span style="color:black"> <b>solve questions about a set of historical data 😎</b></span>

## Goals
- Import new libraries
- Data cleaning and manipulation using pandas
- Dynamically display historical data
- Solve questions using these visualizations

## Setup

There two ways to follow this tutorial:

- Use [JupyterHub](https://lab.openearthscape.org) where the notebook in this repository can be run
- Or run the notebook in your computer through Anaconda and/or Jupyter Lab.

### Run it in your Anaconda Navigator Enviroment and/or Jupyter Lab
The code is developed and tested using Python 3.x. You can use this notebook through the creation of an Anaconda enviroment.

<h4>Anaconda enviroment installation</h4>
<p>First you need to create an enviroment in the Anaconda prompt with the following specifications:</p>

```
conda create -n coco_seismic numpy pandas pathlib seaborn notebook
```
<p>Then activate the enviroment:</p>

```
conda activate coco_seismic
```
<h4>Install jupyterlab and it's plotly extension</h4>

```
pip install "jupyterlab>=3" "ipywidgets>=7.6"
```
<h4>Then install jupyter -dash extension</h4>

```
conda install -c conda-forge -c plotly jupyter-dash
```
<h4>Finally you can load jupyter lab in your enviroment and run the code or use it directly in a jupyter notebook</h4>

```
jupyter-lab 
```

## Run the code
Clone this repository in you local enviroment, the data available in this notebook is from [Kaggle](https://www.kaggle.com/srijya/us-earthquake-intensity-database). The interactive maps should look like this:
<img src="https://github.com/BereniceMtzT/Semana-4-CoCo-2022/blob/master/img/img_seismic.jpeg"
  width="800"
  height="300">



## License

The full text of these licenses is provided in the LICENSE.txt file.
