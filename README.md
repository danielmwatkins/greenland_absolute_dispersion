This code is in support of the analysis for an upcoming paper on absolute dispersion and eddy properties for the Greenland Sea. 

The main idea of the paper: using 2 decades of optical imagery, we examine the dispersion of sea ice floes in the Fram Strait region. Prior work on dispersion has primarily used buoys from dedicated experiments, meaning that there is insufficient data for analysis of interannual variability. Tracked floes are a novel source of information on ice dynamics. Traditional methods of estimating ice motion from buoy drift use cross-correlation, resulting in motion estimates representing area-averaged displacement. In the eddy-rich marginal ice zone, area averages have higher uncertainty and are only able to capture motion at larger-than-floe scales. In particular, typical eddies range in size from sub-kilometer to approximately 30 kilometers, meaning that they are unresolved by standard drift motion estimates. 

Main points that the analysis needs to address
1. Characterization of dynamics
    - Distribution of velocity perturbations (note difference in time scales relevant for velocity)
    - Autocorrelation
    - Absolute dispersion, including the error estimates
2. Connection of interannual spread to sources of variability
    - Sampling different periods?
    - Sea ice conditions for the region?
    - Binning trajectories by location, by sea ice concentration, by floe size?
3. Evidence of role of meso and sub-mesoscale ocean dynamics
    - Straight vs curved trajectories
    - Rotation rates, estimated area-averaged vorticity
    - Is there also a connection with low winds and closed loops?


The analysis includes the following steps:

1. Characterization of the retrieved data in terms of
    - Location of long trajectories
    - Length scale of retrieved floes
    - Distribution of lengths of retrieved trajectories
2. Retrieval of co-located sea ice concentration and surface wind data
    - NSIDC Sea ice concentration dataset
    - ERA5 surface winds
3. Retrieval of NSIDC Ice motion vectors
    - Averaging at designated timescales (7 day, 31 day)
    - Calculation of cross-track and along-track components
    - (Optional) Production of pseudo-trajectories
4. (Ideally) Reproducable code for running the Ice Floe Tracker
5. Data merging
    - Calculation of cross-track and along-track velocity components
    - Interpolation of wind data to floe positions
    - 


Writing: Standard length for a Research Report is 6 pages (4,000 words, 4 figures) but can go up to 12 pages in length. Currently at over 5,000 words, but can be tightened.
Significance statement: 150 words.

Fun idea: if we can make a really solid illustration, it can be submitted for the journal cover, which we be great visibility for the article.