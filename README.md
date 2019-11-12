# FinalProject

**Scientific Question:
Barium and Salinity concentrations in the global ocean typically show 1:1 correlation.
Are there locations where the correlation is weaker?

**Links to datasets:
Discrete Sample Data - netCDF file —> global ocean water trace element (Ba) data
CTD Sensor Data - netCDF file —> global ocean water salinity data
https://www.bodc.ac.uk/geotraces/data/idp2017/

IODP drilled holes - KML file 'Drilled Holes file' —> shows all latitude & longitude values for drilled sites
https://www.iodp.org/resources/maps-and-kml-tools
*this KML file will be turned into a pandas DataFrame

**Analysis plan (3 sentences summary)
Global ocean water concentrations of Salinty and Barium will be plotted separately.
Their correlations and dissimilarities will then be calculated and plotted using cartopy to show which, if any, global locations
  show departure from the 1:1 ratio that is typically assumed between the two variables.
Both river data (via cartopy.features) and IODP core sites will be added on top of the plot described above in order to try to understand
  a) where any excess Barium inputs can be attributed to (ie coastal estuary environments)
  b) which cores are best to use for paleoproductivity studies which rely on the assumption that Ba:Salinity is correlated in a 1:1 ratio.
