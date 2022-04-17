# epfl_showcases
As I do the [Data Visualisation and Communication](https://www.extensionschool.ch/applied-data-science-communication-visualization) course by the [EPFL extension school](https://www.extensionschool.ch/), I would like to share what I learn. This is possible for the optional parts where I go and find data myself to plot in ways I learnt during the course.

# Running this yourself
This project uses `{renv}`, a virtual environment managing the dependencies. The dependencies can be installed with `renv::restore()`, and then all packages required for running the code are available. 

# What I plot

## 1. Timeseries  
here the task was to find some timeseries data and plot it. I looked at the population in Switzerland over time, separately for the number of people who are allowed to vote, those who are not but are still swiss, and those who are not because they are not Swiss. Code in [this folder](https://github.com/shaenzi/epfl_showcases/tree/main/01_timeseries)

## 2. Maps/cartograms
and another pretty open task: to find some geographic data and plot it. I decided to make a cartogram per canton in Switzerland showing the number of female representatives in parliament. plus some other related plots, can be found in [this folder](https://github.com/shaenzi/epfl_showcases/tree/main/02_cartograms)

## 3. Networks
From the second part of the course, I plotted some networks of my choice: of course I chose a brain, but a simple one, namely the one of *C. elegans*. These network plots are shown in [this folder](https://github.com/shaenzi/epfl_showcases/tree/main/03_networks_neurons), as usual with a markdown file as well as a knitted html.

## 4. Volcanoes
Based on a #TidyTuesday dataset on volcanoes, one of the small course projects was to generate some visualisations and a table, generating a story on volcanoes. I did some exploration in the Volcano_exploration, and then a more polished version in A_story_on_volcanoes, again both in R markdown and html versions. [This is the folder.](https://github.com/shaenzi/epfl_showcases/tree/main/04_volcanoes)

## 5. Beautiful city maps
In [this folder](https://github.com/shaenzi/epfl_showcases/tree/main/05_osmdata) I plot some features from open street map, and make some pretty city maps.
