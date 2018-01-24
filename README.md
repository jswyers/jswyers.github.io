
Enhancing the USDA Hardiness Model via Hourly NOAA Data Analysis:


Data analysis utilizing hourly temperatures at NOAA weather stations throughout the US.  Hourly resolution is required to improve the hardiness zone model developed by the USDA.

Text files provided on the NOAA ftp have a wealth of information related to weather conditions and are saved per year and zipped each year in a cumulative archive (i.e. every previous year is included in the current zip file).  The latest complete record unzips to more than 4GB of text files and includes years 2000-2017.  This project used the entire dataset, filtered to 2007-2017 to ensure a large number of stations, and also removed AK data to simplify the overall analysis.

Pandas was used to import, clean, sort, and organize the data.  New parameters were defined which attempt to better understand the temperature variation at the hourly level and apply to hardiness boundary conditions.  This parameter set will be updated as better hardiness models utilizing hourly data are developed.

Ultimately the site should evolve into an interactive tool where the user can input locations and make tweaks to the model coefficients as desired.  The end goal is to create a tool that helps a grower understand the limitations of a particular environment and make better choices about plant selection.
