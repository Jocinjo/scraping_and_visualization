# scraping_and_visualization
In this readMe we will write:
- The steps
- The data
- The scraping
- The visualization

It is possible that we will use docker in the future. If we would use docker then it will contain:
- Requirements.txt
- Python files
- Tests
- And this README

Our goal is to scrape a dataset and visualize it. But most of all we want to learn how to collaborate on git with branching. Momentarily we are with two people and divided our tasks among us two.

The scraping will be done by KageNeko89 and the visualization by Jocinjo. The tests will be written by both of us.

We will use branching so the main branch always works. We will check each other's work to keep the main-branch working.

As we go along this README will be changed.

# Our goals and journey
Our goal is to make something we are proud of. For now we want to do the scraping and visualization. Should this change in the future then we are okay with that because we want to make a learning experience out of it and make something we are proud of. 

# The data
The data that will be used in this case is coming from CBS. Down here you can see a link so you can see which data is used:
[Data](https://opendata.cbs.nl/statline/#/CBS/nl/dataset/85702NED/table?dl=9F945)

We wanted a small dataset and landed on a dataset about graduation-level per region and province in The Netherlands. 
Rows: The graduation-levels are from highschool through a university master degree. The rows are divided per kind of degree but also a total of school-kind. For example, in the Netherlands we have multiple levels of highschool, as is shown in the dataset, but also a total sum of highschool graduates.
Columns: 12 provinces and 1 undefined one and 4 regions and 1 undefined one. The dataset also defined an undefined region and an undefined province. So in total there are 18 columns.

# The scraping

# The visualization
For now the plan is to use the Dash module as visualization tool.