# Precip_MultiPanel
A Jupyter Notebook to visualize precipitation products from a collection of different datasets. Usable in Python 3.x.

Version History:

V1.2 (23 December 2017):
---Added support for multiple day aggregations of precipitation.
---Added error-proofing prior to plot sequence
---Removed dependency of CSV file with datasets. File now uses all links for datasets and imports names and links into tupled array for easy access.
---Added multiple levels categories for precipitation contours based on total accumulation.

KNOWN BUGS:
---Contour lines are slightly out of phase with pcolormesh.
---Maximum precipitation value is calculated from the ensemble RMS and not from the global maxima.

V1.01 (13 November 2017):
---Added case selection parameters in cell 4 to eliminate hard-wired redundancies.

V1.00 (7 November 2017):
---Initial commit.
