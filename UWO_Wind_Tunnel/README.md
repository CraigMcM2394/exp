# UWO Wind Tunnel Measurements

The data in this directory has been extracted from HDF (Hierarchical Data File) files generated by the Alan G. Davenport Wind Engineering Group at the University of Western Ontario. A typical file name provides information on the originating facility, the roof slope, the exposure, the model scale, the leakage case for internal pressures, the building eave height and the wind angle:

Filename: ADW100o100S048a3250.HDF

Position 1-3 identifies the originating facility (ADW = Alan G. Davenport Wind Engineering Group)

Position 4-6 identifies the roof slope in 12ths multiplied by 100 (100 = 1:12 roof slope)

Position 7 identifies the exposure (o = open exposure)

Position 8-10 identifies the model scale to 3 digits (100 = 1:100 length scale)

Position 11 identifies the leakage case (S = small opening case)

Position 12-14 is the building eave height in full scale feet to 3 digits (048 = 48 feet building height)

Position 15 is the index for different cases with otherwise the same filename (a = case a)

Position 16-19 is the wind angle in degrees to be read as xxx.x (3250 = 325.0 degree wind direction)

.HDF identifies the data format as a Hierarchical Data File which is the standard file format
chosen for the exchange of the data.

The data extracted from these HDF files are organized by "lines" which are profiles of mean, rms, min, and max pressure coefficient from the leading edge of the building, up and over the roof, and down the leeward side. Thus, a file with suffix `_line_x.csv` are just the data along the line of interest. 
