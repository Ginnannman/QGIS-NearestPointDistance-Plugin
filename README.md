# Nearest Point Distance Algorithm
## General Description
This is an experimental QGIS plugin to search for a nearest neighbor point.
In QGIS porcessing, "nearestNeighbor" method sometimes does not work well, because this method is based on Approximate Nearest Neighbor Algorithm (maybe). 
This plugin is a little better than distance matrix in QGIS processing if you want to know nearest points.

## Notice
This plugin does not work if input layer and output layer are the same.

## Installation

You have to download this repository to your local by clicking "Download ZIP". Then start QGIS and open "Manage and Install Plugins" dialog in plugin menu. Install from ZIP, and you can use this plugin from "processing tool box". 

## System Requirements

This plugin was tested with QGIS version >= 3.0.
