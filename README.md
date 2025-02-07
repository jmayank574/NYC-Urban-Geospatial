# NYC-Urban-Geospatial


# Overview

This project analyzes NYC’s urban infrastructure using geospatial data and an H3 hexagonal grid to assess accessibility. The data is normalized for consistency, and an index_score is computed by combining multiple features (schools, subways, parks, bike paths). A higher index_score results in a darker color on the visualization, indicating better accessibility.


# Why H3 Grid?

The H3 hexagonal grid is applied after initial visualizations to ensure uniform spatial units, enabling better comparisons and eliminating irregular neighborhood shapes. It improves spatial analysis accuracy and allows seamless aggregation of geospatial features.


# Features

Leafmap visualization of accessibility scores for NYC.

H3 hexagonal grid for spatial analysis and comparison.

Geospatial feature analysis (schools, subways, parks, bike paths).

Buffers (800m & 1600m) for accessibility assessment.


# Workflow

Load and visualize raw geospatial data using Leafmap.

Apply H3 hexagonal grid to divide NYC into uniform spatial units.

Analyze accessibility metrics for each hex cell (schools, subways, parks, bike paths).

Compare results between raw geospatial data and H3-based approach.

Final visualization on Leafmap with interactive data layers.


# Technologies Used

Python, GeoPandas, H3-Pandas, Leafmap, Shapely, Pandas


# Advantages

Uniform spatial representation across NYC.

Better data aggregation & comparison of accessibility features.

More intuitive visualization for urban planning insights.
