# Satellite Laser Ranging Station Data and Operational Anomaly Detection Model (SLR SAM)

* title: "Satellite Laser Ranging Station Data and Operational Anomaly Detection Model (SLR SAM)"
* author: "Justine Woo"
* date: "2024-12-27"
* description: "Isolation forest is an unsupervised machine learning algorithm commonly applied to anomaly detection.  This notebook serves as a tool that may be used to track anomalies within satellite laser ranging station performance using isolation forest with publicly available satellite data from NASA's Crustal Dynamics Data Information System (CDDIS)."
* tags: \["SLR", "Isolation Forest", "Satellite Laser Ranging"]
* version: 1.0

## Version

|Version Number|Description|
|-|-|
|1.0|Initial software release|

## Overview

This notebook provides an example of how isolation forests can be used to detect data and operational anomalies in station hardware or software based on LAGEOS and LARES data which may signal a change in the system. A paper on this approach is available at: https://ilrs.gsfc.nasa.gov/lw22/posters/papers/S06-P10\_Woo\_Paper.pdf.

## Prerequisites/Set-up

* This notebooks was created using Anaconda Navigator where additional packages were downloaded to support this software.
* Two directories for NPT data need to be created: downloadedData and csvData/
* An earthdata account; to create an Earthdata Login: https://urs.earthdata.nasa.gov/
* .netrc or \_netrc file containing your Earthdata Login username and password; For more information on creating a .netrc or \_netrc file: https://cddis.nasa.gov/Data\_and\_Derived\_Products/CreateNetrcFile.html

## Familiarity with the following is suggested

* Python, numpy, pandas
* Basic machine learning covering decision tree classification - this will allow users to understand how the model works, how to improve it, and to assess the quality of the results
* CRD Format: https://ilrs.gsfc.nasa.gov/data\_and\_products/formats/crd.html - this is needed if there are additional features you'd like to extract from the data

## Notices:

“Copyright © 2024 United States Government as represented by the Administrator of the National Aeronautics and Space Administration.  All Rights Reserved.”

## Special Note

Please be sure to cite our software and our data.  To cite our data please see our DOI landing page here: https://cddis.nasa.gov/Data\_and\_Derived\_Products/SLR/slr\_data\_monthly\_npt.html

## References

International Laser Ranging Service (ILRS), SLR monthly normal point data, Greenbelt, MD, USA:NASA Crustal Dynamics Data Information System (CDDIS), Accessed 2024-12-20 at doi:10.5067/SLR/slr\_data\_monthly\_npt\_001.

