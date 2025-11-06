# Rainfall-Homogeneity-and-Consistency-Analysis-Pettitt-Test-
his repository contains Python scripts for evaluating the temporal homogeneity of rainfall datasets using the Pettitt non-parametric change-point test. The workflow examines whether long-term rainfall time series contain abrupt shifts or artificial inconsistencies that may result from changes in measurement instruments, station relocation, data merging, or processing bias.

Key Features
Loads monthly rainfall data from NetCDF format using xarray.

Computes spatially averaged regional mean rainfall over latitude and longitude dimensions.

Applies the Pettitt homogeneity test to detect statistically significant change points in time series.

Interprets and reports:

Change point location (year/month)

Test statistic value

P-value and homogeneity conclusion

Produces a publication-quality time series visualization that highlights detected change points.

Saves the figure as a high-resolution PNG file for use in reports, theses, and presentations.

Use Case
This method is used in climate trend evaluation, hydrological modeling, and observational rainfall data quality assessment.
Checking dataset homogeneity ensures that rainfall trends reflect true climate variability, rather than artificial shifts from observational inconsistencies.

Dependencies
xarray

numpy

pandas

matplotlib

seaborn

pyhomogeneity
