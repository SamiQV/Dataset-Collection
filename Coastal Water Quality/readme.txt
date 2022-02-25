	*** SEDAC Indicators of Coastal Water Quality Collection  ***
                               (September 2009)

           Socioeconomic Data and Applications Center (SEDAC)
   Center for International Earth Science Information Network (CIESIN)
                        Columbia University

                http://sedac.ciesin.columbia.edu/es/seawifs.html


CIESIN follows procedures designed to ensure that data disseminated by 
CIESIN are of reasonable quality. If, despite these procedures, users 
encounter apparent errors or misstatements in the data, they should 
contact SEDAC User Services at tel. +1 845-365-8920 or via email at 
ciesin.info@ciesin.columbia.edu. 

Work supported by NASA under contract NAS5-03117 with Goddard Space Flight 
Center for the Socioeconomic Data and Applications Center (SEDAC). The views
expressed by the producers of these data are not necessarily those of CIESIN,
Columbia University, nor NASA. 

Neither CIESIN nor NASA verifies or guarantees the accuracy, reliability, 
or completeness of any data provided. CIESIN provides this data without 
warranty of any kind whatsoever, either express or implied. CIESIN shall 
not be liable for incidental, consequential, or special damages arising 
out of the use of any data provided by CIESIN.


DATA FORMATS

1) Annual chlorophyll-a concentrations 1998-2007

Annual composite chlorophyll-a concentrations (in nanograms/cubic meter) are 
provided in GRID and compressed GeoTIFF formats. The grids have a resolution of 
0.083333 decimal degrees, or approximately 9 km on a side at the equator, and 
are stored in geographic coordinates with the following parameters:

Projection: 	Geographic
Spheroid:	WGS84
Units:		Decimal Degrees

To obtain data in milligrams/cubic meter, divide the grid cell values by 1,000.


2) Change in clorophyll-a concentrations 1998-2007 

Based on the annual grids, we created a tabular time series of chlorophyll-a 
concentrations from 1998-2007 for each grid cell. The grid cells are organized by 
country, and statistics are calculated to show the percentage of change from 
1998-2007. The rows of the table are linked to a sequence grid to facilitate 
the mapping of the trend values for selected countries and areas of interest. The 
documentation that is bundled with the data contains detailed step-by-step 
instructions for different analysis scenarios.

The tabular data are provided in Excel 2007 (all countries) and CSV format 
(bundled by countries alphabetically in order to comply with row limits imposed by
earier versions of Excel). 

The data dictionary is as follows:

GRIDCODE 	= Links to sequence grid for mapping results (see ancillary data)
EEZ		= Exclusive Economic Zone
Country		= Country or territory
Sovereign	= Country underwhich the territory falls
Region		= Geographic region 
x1998		= Average annual chrlorophyl-a concentration in that grid cell in 1998
x1999		= Average annual chrlorophyl-a concentration in that grid cell in 1999
x2000		= Average annual chrlorophyl-a concentration in that grid cell in 2000
x2001		= Average annual chrlorophyl-a concentration in that grid cell in 2001
x2002		= Average annual chrlorophyl-a concentration in that grid cell in 2002
x2003		= Average annual chrlorophyl-a concentration in that grid cell in 2003
x2004		= Average annual chrlorophyl-a concentration in that grid cell in 2004
x2005		= Average annual chrlorophyl-a concentration in that grid cell in 2005
x2006		= Average annual chrlorophyl-a concentration in that grid cell in 2006
x2007		= Average annual chrlorophyl-a concentration in that grid cell in 2007
SLOPE		= Slope of the regression line through all average annual concentrations 
		  (1998-2007),indicating steepness of change over time
R2		= R-square of the correlation between annual chl-a concentration and year
CHANGE		= % change in the average 2005-2007 value compared to the average 1998-2000 value 
SCHANGE		= Statistically significant % change; same as CHANGE if signfiicant, otherwise -999999
p		= Significance level of the linear regression of chlorophyll concentration on year
		  (n.s. = not significant)



3) Ancillary data

These data can be used in conjunction with the tabular data, as described in the
documentation.

Sequence grid: Global sequence grid with a cell size of 0.08333 decimal degrees, 
to be used as a grid cell identifier in the context of raster calculations. 
Provided in ArcGIS GRID format.

Centroids: Centroids of sequence grid cells, useful for interactive selection of 
areas of interest. Provided in shapefile format. 

Country buffers: A buffer layer of the near-coastal zones (10-100 km off 
coastline) for each country, delineated by exclusive economic zones (EEZ). 
Provided in shapefile format. 


CITATION AND ACKNOWLEDGEMENTS

This work, including access to the data and technical assistance, is 
provided by CIESIN, with funding from the National Aeronautics and 
Space Administration under Contract NAS5-03117 for the continued 
operation of the Socioeconomic Data and Applications Center (SEDAC).

CIESIN would like to acknowledge the contribution of Ajit Subramaniam 
of the Marine Biology Department of the Lamont-Doherty Earth Observatory 
to the development of these data. The data were developed by Steffen Foerster, 
Malanding Jaiteh, and Alex de Sherbinin. 

Should you download and use these data, please ensure that any results are 
accompanied by the following data citation: 

"Center for International Earth Science Information Network (CIESIN), Columbia
University. 2009. Indicators of Coastal Water Quality: [Title of Constituent 
Data Set]. Data distributed by the Socioeconomic Data and Applications Center 
(SEDAC): http://sedac.ciesin.columbia.edu/es/seawifs.html. [Date downloaded]


METHODOLOGY

For information on the methods utilized to produce these data, please
visit http://sedac.ciesin.columbia.edu/es/seawifs.html and review the methodology 
section.
