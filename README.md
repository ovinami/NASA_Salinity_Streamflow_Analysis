The jupyter code ('PNAS_Paper_SSS_Streamflow.ipynb') was used to analyze data for my paper published in the PNAS journal, titled, 'Continental freshwater discharge influences sea surface salinity variability near world's megadeltas' (https://www.pnas.org/doi/10.1073/pnas.2412551121).

The code uses Object Oriented Programming in Python to analyze statistical associations of continental streamflow and sea surface salinity near global mega deltas. In the code, a total number of 48 deltas were each read as objects and associated data were processed, analyzed, and partitioned into the objects to produce high impact figures. The hydrological variables (streamflow and water storage) were obtained from NASA's LIS and HyMAP models from the Goddard Space Flight Center's Discover supercomputer cluster. All other data used are publicly available from open access platforms. Below I provide a step-by-step sample of the code. To run the code, it is recommended to have all files saved in one directory, and to have access to necessary python libraries. Also, the user must download all input data before using any part of this code.

Below I am listing most of the data sources used in this analysis, and mentioning the contact persons responsible for some of the raw data which I cannot share publicly.

Processed Global SSS (NASA's SMAP sensor) and Streamflow (NASA's LIS and HyMAP models) data: Download from https://zenodo.org/records/14039482 Khadim, F., & Kumar, S. (2024). Analysis of streamflow and sea surface salinity near megadeltas [Data set]. Zenodo.

Reservoir storage data: contact Nishan Kumar Biswas (Associate Scientist, Earth Sciences) Email: n.biswas@nasa.gov

Delta Shapefile data: Download from https://www.globaldeltarisk.net/data.html Z.D. Tessler, C.J. Vörösmarty, M. Grossberg, I. Gladkova, H. Aizenman, J.P.M. Syvitski, E. Foufoula-Georgiou. Profiling Risk and Sustainability in Coastal Deltas of the World. Science 349(6248), 638-643 (2015) doi:10.1126/science.aab3574.

Further, I have uploaded some additional input files (.CSV file) in this github directory!
