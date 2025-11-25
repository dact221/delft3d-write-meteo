# delft3d-write-meteo

Write space- andt time-varying meteo files on curvilinear grid for Delft3D

**Authors:** Diego A. Casas (Federal University of Paraná, Brazil); Sofia M. G. Rocha (Lancaster University, UK)

**Version:** 20250804

**What's new?:** add a section to create spatialized input for radiation and wind magnitude in WAQ (segment function).

**Info:** this code can write up to 1.2 GB per minute. Writing all 7 meteo files for a 1.5-year-long time series with 10-minute data and 4 decimal places took about 13 minutes for the example .grd file in an SSD (16.7 GB).

**Warning:** writing large files in cloud folders (e.g., Google Drive, OneDrive, Dropbox) sometimes results in slow writing speeds because the cloud sofware tries to index and sync the content as it is being written. Prefer running this code in a local folder.
