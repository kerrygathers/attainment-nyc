# Lab Assignment 02

Reflect upon the advice the professor gave Chimero: that his portfolio, "Needs more love." Then read the task and requirements below. After you select a dataset to map, consider the following two questions:

1. In what ways do you believe in the map you're about to create?
2. How do you care about an intended audience for this map (imagine an audience other than your instructor)?

Use your answers to these questions to guide you through the process detailed here:

**Task:** Chose one of the two options below and create an interactive map meeting the following requirements:

- [ ] the map uses a choropleth thematic type to represent quantitative data
- [ ] the map provides the user with a UI widget (either a dropdown menu or radio buttons) for updating the map and legend with a new data attribute
- [ ] the map has a clear and descriptive title/subtitle that should establish 1.) **what** is being mapped, 2.) **where** the phenomena is geographically, and 3.) **when** the mapped phenomena occurred
- [ ] the map has a legend, including:
    - [ ] a descriptive legend title (i.e., not "legend")
    - [ ] indication of what numeric class ranges each color represents
- [ ] the page includes supplementary information about the map, including a description, links to data sources, the map author (and links to the author's GitHub profile or portfolio)
- [ ] the map and page are uniquely styled with novel typography and colors
- [ ] the page loads smoothly and the code contains no errors
- [ ] the code is well-written with appropriate comments
- [ ] the repository includes timely commits of progress with descriptive commit messages

**Save the _index.html_ file for the map within the _lab-02/_ directory and commit your work with Git as you go**.

Feel free to restructure the HTML as you see fit, or use another CSS boilerplate/framework for help with the structure and basic styling. 

**Option 1**: Use one of the datasets provided within the [_lab-02/data/_](data/) directory (**5.5 pts**)

Look through the datasets provided within the _lab-02/data_ directory. The data describe statistics about labor and households, drawn from [American Fact Finder](https://factfinder.census.gov) and joined with county geometries from the [US Cartographic Boundary Shapefiles](https://www.census.gov/geo/maps-data/data/cbf/cbf_counties.html). See the [meta.md](data/meta.md) file for a description of the attribute field names.

**Option 2**: Use an original data source (**6 pts**)

Aim high and build a new map using an original data source (and a geography other than KY counties). Since you only have a week, the trick here is to get the dataset and format it correctly as soon as possible.

You'll likely want to use the _ky_counties_housing.json_ file (or the optional data files in the _lab-02/data_ directory) as a model for building your data file. It should be a GeoJSON file that includes the geometries of your mapped area and the quantitative data value as attributes within the properties of the file.

Choose data with attributes that are qualitatively different (such as owned with a mortgage vs. owned free and clear). Avoid data that are temporal time stamps (we'll be exploring this kind of data in the next Module and using a UI slider to sequence through those values to update the map).