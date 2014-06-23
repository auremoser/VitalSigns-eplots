
![VS-logo](https://raw.githubusercontent.com/auremoser/VitalSigns-eplots/master/assets/logo-small.jpg)
## Vital Signs - Eplots
a test repository for e-plot data visualizations + water gauging stations

### Description
* This map uses the e-plot data as a csv (located in the `data` folder), and for the last example, water gauging station lat/long locations.
* It plots topojson administrative districts from the Tanzanian geojson files available on GADM 2.0: <http://gadm.org/country> (located in the `public/topo` folder).
* The visualization colors and different map backgrounds depending on the aesthetic plan for the project (these are the tests)
* The `js` code is geared toward a d3 map, and there are other topojson references in the `data` folder that incorporate some cleanup functions to reorganize the data values and make them available for plotting as we refine the goals for the project.

* These are all sketches, subject to change and interation.

### Next steps
Visualizations for these data might fall into two categories, the first of which is visualized here, the following (cat-2) is forthcoming.
* Cat-1: Maps to illustrate where the eplots fall to show correlation to other mapped data
* Cat-2: Plots to illustrate the values collected by sensors at the subplots

### Demo
You can find the work in progress demo [here](http://auremoser.github.io/VitalSigns-eplots/).

It should look something like this:
![Eplot Points](https://raw.githubusercontent.com/auremoser/VitalSigns-eplots/master/assets/eplot-points.png)

And here is a binned map of eplot density:
![Eplot Bins](https://raw.githubusercontent.com/auremoser/VitalSigns-eplots/master/assets/eplot-bin.png)

And here is an example of eplot locations (green) and water gauging stations that are in proximity (blue):
![Eplot + Water Gauging](https://raw.githubusercontent.com/auremoser/VitalSigns-eplots/master/assets/eplot-watergaugeoverlay.png)
