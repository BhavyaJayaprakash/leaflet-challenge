# leaflet-challenge
Module 15 challenge
![1-Logo](https://github.com/user-attachments/assets/5ac8c044-dada-4d95-8d92-b923753029e4)

# Deployment Link

# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# Before You Begin
Create a new repository for this project called leaflet-challenge. Do not add this Challenge to an existing repository.
Clone the new repository to your computer.
Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: Leaflet-Part-1 and Leaflet-Part-2.
This Challenge uses both HTML and JavaScript, so be sure to add all the necessary files. These will be the main files to run for analysis.
Push the above changes to GitHub.

# Instructions
The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data (Optional with no extra points earning)

Part 1: Create the Earthquake Visualization


# Level-1: Basic Visualization
Get the Data Set
The USGS provides earthquake data in a number of different formats, updated every 5 minutes
The "All Earthquakes from the Past 7 Days" data set was selected from the USGS GeoJSON Feed page
The data was given in JSON format which was used to pull in the data for the visualization
Import and Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color
Earthquakes with higher magnitudes appear larger and earthquakes with greater depth should appear darker in color
Popups that provide additional information about the earthquake were included when a marker is clicked
A legend was created to provide context for the map data
![Screenshot 2025-04-16 003904](https://github.com/user-attachments/assets/09f417ef-4887-4144-80d3-3c0a5d78509e)

# Level-2: More Data
Plot a second data set on the map above to illustrate the relationship between tectonic plates and seismic activity.

Pull in Tectonic Plates data set
Visualize it along side the original set of data
Add a number of base maps (Satellite Map, Grayscale Map, Outdoors Map and Dark Map) to choose from
Separate out the two different data sets (earthquakes and tectonic plates) into overlays that can be turned on and off independently
Add layer controls to the map
![Screenshot 2025-04-16 004018](https://github.com/user-attachments/assets/8730eb2e-519b-4774-8e4e-ae79a6b29d06)



