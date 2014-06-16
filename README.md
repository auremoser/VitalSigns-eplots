# Vital Signs
a test repository for e-plot data visualizations

## General

* This map uses the e-plot data as a csv (located in the `data` folder).
* It plots topojson administrative districts from the Tanzanian geojson files available on GADM 2.0: <http://gadm.org/country> (located in the `public/topo` folder).
* The visualization uses d3 to post e-plot lat/long data on a map of tanzania, with the hope that as we refine that
* The `js` code also incorporates some cleanup functions to reorganize the data values and make them available for plotting as we refine the goals for the project.

##Demo
You can find the work in progress demo [here](auremoser.github.io/vital-signs).

It should look something like this:
![Draft 1](https://raw.githubusercontent.com/auremoser/vital-signs/master/assets/draft-1-vs.png)

And here is the structure of an eplot: 
1[Eplot](https://raw.githubusercontent.com/auremoser/vital-signs/master/assets/eplot.png)
