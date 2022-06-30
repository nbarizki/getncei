# GetNCEI,  a Module to Retrieve NCDC's NCEI Climate Data

I developed a python module, named GetNCEI, with several functions to provide an easier approach for digging into *Climate Data Online* managed by *The United States National Climatic Data Center* (NCDC). 

GetNCEI has scripts to access the web services using API *requests* module that can be used to narrow down the request hopefully to find the most desired kind of data. GetNCEI has functions to find specific datatypes (i.e. temperature, wind, etc.) or stations by specifying a keyword, and also find the nearest stations by the given coordinate point, which we can also view the visualization of those recorded stations in a token-free Mapbox Basemap. 

# About NCEI CDO Data

NCDC's Climate Data Online (CDO) offers web services that provide access to current data. This API is for developers looking to create their own scripts or programs that use the CDO database of weather and climate data. An access token is required to use the API, and each token will be limited to five requests per second and 10,000 requests per day.

# Discover GetNCEI

GetNCEI is developed to make requests using Class Objects and each of object's own methods. Although the function and output are not in a fully-refined form, it is purposed to enable a flexible processing if any recursive process needed or useful at a later stage of data processing.

GetNCEI Documentation.html has a detailed information about the basic of NCEI data request, the objects and methods, and How-To section to show an example of working on a data gathering scenario utilizing GetNCEI.

The code is stored in [getncei.py](https://github.com/nbarizki/getncei/blob/main/getncei.py)

Proceed to the documentation [here](https://github.com/nbarizki/getncei/blob/main/GetNCEI_documentation_v1.ipynb), or download the html  file [here](https://github.com/nbarizki/getncei/blob/main/GetNCEI_Documentation_v1.html), or access the pdf file (for a better image render) [here](https://github.com/nbarizki/getncei/blob/main/GetNCEI_Documentation_v1.pdf).

Note: while opening ipynb file, try to right click on the broken image and select 'open link in new tab' to resolve it.
