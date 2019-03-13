# Playing with Data

This repository contains sample code and data, as well as links to the P5.js
editor, associated with the [Playing With Data](https://cdh.princeton.edu/events/2019/02/playing-data/)
series of workshops hosted by the
Princeton [Center for Digital Humanities](https://cdh.princeton.edu) and
the [Council on Science and Technology Studio Lab](https://cst.princeton.edu/studiolab).

## Workshop Outline

p5.js [editor](https://editor.p5js.org/), [reference](https://p5js.org/reference/), [examples](https://p5js.org/examples/)

### References
- [loadTable()](https://p5js.org/reference/#/p5/loadTable) [getColumn()](https://p5js.org/reference/#/p5.Table/getColumn) [getColumnCount()](https://p5js.org/reference/#/p5.Table/getColumnCount) (more p5 Table functions here)
- [line()](https://p5js.org/reference/#/p5/line), [beginShape()](https://p5js.org/reference/#/p5/beginShape)
- [random()](https://p5js.org/reference/#/p5/random), [map()](https://p5js.org/reference/#/p5/map), [min()](https://p5js.org/reference/#/p5/min), [max()](https://p5js.org/reference/#/p5/max)

### Code-Alongs
- [Intro to Animation](https://editor.p5js.org/slcruz/sketches/b2uP4YSNu)
- [Plotting Data](https://editor.p5js.org/slcruz/sketches/005jy4zME)
- [Warming Stripes](https://editor.p5js.org/slcruz/sketches/mCzhpwQ_7)
- [Data Sources](https://github.com/Princeton-CDH/playingwithdata)

### p5 Examples
- [Data to Text](https://editor.p5js.org/aatish/sketches/kwq05rOSP)
- [Global Average Temperature Graph](https://editor.p5js.org/aatish/sketches/4i-ATjzhH)
- [Climate Stripes Animated](https://editor.p5js.org/aatish/sketches/SCZoLYwc4)
- [Warming Spiral](https://editor.p5js.org/aatish/sketches/24yVBFcjc)

### Data Viz Examples
- [Gun Violence](https://guns.periscopic.com/?year=2013)
- [Breast Cancer Causation](http://www.cabreastcancer.org/causes/#)
- [Links in the Jazz Community](https://linkedjazz.org/network/?mode=wave)
- [Reimagining Elizabeth Palmer Peabody’s Historical Visualization Work](http://shapeofhistory.net/)
- [Warming Stripes](https://www.climate-lab-book.ac.uk/2018/warming-stripes/)
- [Warming Stripes Animated](https://twitter.com/kevpluck/status/1099369629766565888)
- [Our World in Data](https://ourworldindata.org/)

## Data Files

The data files can be downloaded for use from this repository or used in
in web application directly via CDN. They are found in the `data` folder.

All are in CSV format with one header row.

### Latin American Ephemera datasets

These files are generated from the Princeton Libraries
[Latin American Ephemera](https://lae.princeton.edu/) collection and list
the number of items for given country and subject bucketed into two year
increments.

The file names follow the pattern `country_name_of_subject`.

### Shakespeare and Co. Datasets

These files use preliminary data from the
[Shakespeare and Company Project](https://cdh.princeton.edu/projects/shakespeare-and-company-project/),
which collects the lending cards and log books of Sylvia Beach's
Shakespeare and Company lending library, a hotbed for American expatriates
and literary life in Paris during the early twentieth century.

`s-co_members_by_year.csv` details the number of members added per year.
`s-co_members_by_yearmonth.csv` details the number of members added by year and month.

### Derrida's Margins datasets

Data from [Derrida's Margins](https://derridas-margins.princeton.edu/),
which all of documents Jacques Derrida's references in _de la Grammatologie_
(_Of Grammatology_)and connects them to correponding annotations in his
own copies of the referenced books.

`ofgrammatology-references.csv` provides counts of references per page
for each page in _Of Grammatology_.


### Climate Datasets

This data is obtained from NASA's [Vital Signs](https://climate.nasa.gov/vital-signs/) website. The columns in the [temperature data](https://climate.nasa.gov/vital-signs/global-temperature) list the year, raw temperature offset, and smoothed temperature offset.

## CDN Links

### LAE

* [argentina_human_civil_rights.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/LAE/argentina_human_civil_rights.csv)
* [bolivia_agrarian_rural_issues.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/LAE/bolivia_agrarian_rural_issues.csv)
* [bolivia_minorities_ethnic_racial_groups.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/LAE/bolivia_minorities_ethnic_racial_groups.csv)
* [chile_human_civil_rights.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/LAE/chile_human_civil_rights.csv)

### S&Co.

* [s-co_members_by_year.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/s-co/s-co_members_by_year.csv)
* [s-co_members_by_yearmonth.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/s-co/s-co_members_by_yearmonth.csv)

### Derrida

* [ofgrammatology-references.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/derrida/ofgrammatology-references.csv)

### Climate

* [annual_temperature.csv](https://raw.githubusercontent.com/Princeton-CDH/playingwithdata/master/data/climate/annual_temperature.csv)


