# Working with Bokeh and postegresql/csv and ngnix/systemd configuration and Django
This document explains how to use Bokeh and pull data from a postgresql database or a csv to power a visualization you've created. 

End goal: give Bokeh data from postgresql database or a csv while being able to run the Bokeh server simulanteously as the current server you are working on.

## Step 1: Make sure Bokeh is downloaded
  Go to Bokeh's documentation and gallery in order to see the installation process and inspiration on what kind of visualization you want: https://bokeh.pydata.org/en/latest/
## Step 2: Create the Bokeh visualization
  First create a separate python file for the visualization you want to create in the project folder. Import all the necessary Bokeh packages that pretain to your visulization.
  ### Using 