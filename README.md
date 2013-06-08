abcd
============

This is my project for the TechSummitPR Hackathon on June 6, 2013.  Our goal is to study a data-set given to us by the Center for Youth Development in relation to the geography of the municipalities of Puerto Rico.

The data set had information from all 78 municipalities regarding

- populations by age
- child poverty levels
- educational attainment

Information oft his depth and quality enables us to 

Due to time constraints, we limited ourselves to one statistic:
- **years of school completed by persons of age 25 in the year 2011**

We created a dashboard with a map of Puerto Rico and charts demonstrating these statistics:

![](https://dl.dropboxusercontent.com/u/17949100/OGP/screenshot.png)

On the right, you can click on your *municipio* and on the left, statistics will appear.

### Technical Challenges

During the hackathon, I had to learn to use Miguel Rios' [AtlasPR](https://github.com/miguelrios/atlaspr) library, a special collection of JavaScript maps build with d3.js data visualization library.  This library include very accurate polygons for the *municipios* of Puerto Rico for map-drawing.

In addition, we drew bar charts using [nvd3](http://nvd3.org/), a simplified version of d3.js which contains pre-made chart templates, which can be modified with the general d3.js library.

Using some [jQuery](http://jquery.com/) we linked the users clicking actions on the map to display statistics related to the chosen *municipios*.  Mixing these graphics leads to a simple but effective presentation of these statistics, and the ground-work for further work.

