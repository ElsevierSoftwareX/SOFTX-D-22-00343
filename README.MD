# pyFIRI

pyFIRI is a Python3 implementation of the FIRI-2018 (Faraday‐International
Reference Ionosphere), a semi-empirical D-Region model of the non-auroral 
Earth's ionosphere. Previous version of the FIRI (FT-2001) is incorporated
into a well-known mature International Reference Ionosphere (IRI, https://iri.gsfc.nasa.gov/ ) 
model.

If you use FIRI-2018 or pyFIRI directly or indirectly, please, cite in your research
the following TWO papers:

1. Friedrich, M., Pock, C., & Torkar, K. (2018). FIRI‐2018, an updated empirical model 
of the lower ionosphere. Journal of Geophysical Research: Space Physics, 123, 6737–6751. 
https://doi.org/10.1029/2018JA025437

2. Zolotov, O.,  Romanovskaya, Yu, & Knyazeva, M. (2021). pyFIRI - A free and open source 
Python software package of the non-auroral Earth’s lower ionosphere. SoftwareX., 16, 100885.
https://doi.org/10.1016/j.softx.2021.100885

PyFIRI provides a thin Python3 wrapper around the tabulated electron density Ne profiles supplied 
together with the research paper by Friedrich et al.(2018, https://doi.org/10.1029/2018JA025437 ). 
For internal data representation, selection, and interpolation pyFIRI relies on xarray.DataArray 
( https://xarray.pydata.org/ ) facilities.

