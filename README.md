#Regional Data Inventory
[Regional Data Inventory](https://docs.google.com/spreadsheets/d/1uNtA4GbBwky8PPdNUvmXXZCI1GLtH5cGF-Q0FqD90w0/edit?usp=sharing) (Google Sheets)

This workbook is maintained by Vyki Englert and Emily Forscher of Compiler LLC on behalf of California Community Foundation. The primary spreadsheet uses structured metadata to track datasets that describe or pertain to Los Angeles County. Other sheets track regional data advocates, publishers, data standards, and relevant data portals.

For the purpose of this effort, a dataset is defined by the W3C as “A collection of data, published or curated by a single agent, and available for access or download in one or more formats.” The regional landscape documents datasets, by collecting and maintaining metadata for each of these datasets. Metadata collected meets the minimum required fields of the [W3C Data Catalog Vocabulary (DCAT) metadata standard](https://www.w3.org/TR/vocab-dcat/). This standard was chosen as it’s already it’s the basis of the [Project Open Data Metadata Schema v1.1](https://project-open-data.cio.gov/v1.1/schema/) developed and adopted by the US Federal data.gov platform. Common adoption of metadata standards will facilitate comparison and federation of records across data portals. The properties in use and their definitions are listed below. 

This inventory is a landscape analysis for the Social Change Data Commons Project, as part of an ongoing collaboration with California Community Foundation. It is a work in progress. Please contact Vyki Englert (vyki@compiler.la) and Emily Forscher (emily@compiler.la) with concerns, questions, and suggestions.

#Data Sources
This repo was originally created and maintained by @vykster for use by the local civic tech community, in particular for use by local Code for America Brigade, Hack for LA. [Website](http://hackforla.org) [Meetup](http://www.meetup.com/hackforla/) [GitHub](https://github.com/hackforla).

Indiviual links and metadata for datasets pertaining to the Los Angeles region may be found the in Regional Data Inventory linked above. Links to many publishers, portals, and data tools may be found below.

##Cities
City of Glendale
+ [City of Glendale Performance Dashboar](https://performance.glendaleca.gov) (Socrata)

City of Long Beach
+ [Open Long Beach](http://www.longbeach.gov/openlb/) _Links to apps, searchable databases and more_
+ [Open Data Status Report August 2015](https://speakup-us-production.s3.amazonaws.com/uploads/attachment/file/55cd321a6c9d6f8d1a0014e8/Status_of_Long_Beach_Open_Data_Inventory_-_081315.pdf) (PDF)

City of Los Angeles
+ [City of Los Angeles Open Data Portal](https://data.lacity.org/)(Socrata)
+ [City of Los Angeles GeoHub](https://geohub.lacity.org)
+ [City of Los Angeles pLAn - Sustainability Performance Dashboard](https://performance.lacity.org/)
+ [City of Los Angeles - Mayor's Dashboard](http://dashboard.lamayor.org/)
+ [City of Los Angeles Budget Data](https://controllerdata.lacity.org/) 10 datasets from the City Controller aka "The Control Panel" uses Socrata platform
+ [City of Los Angeles ArcGIS REST Services Directory](http://services1.arcgis.com/p84PN4WZvOWzi2j2/ArcGIS/rest/services) (JSON APIs)
  
City of Pasadena
+ [City of Pasadena Open Data Portal](http://data.cityofpasadena.net/) (Junar)
+ [City of Pasadena GIS Open Data Portal](http://cityofpasadenaca.pasgis.opendata.arcgis.com/)

City of Santa Clarita
+ [City of Santa Claria Open Data Portal](http://www.santa-clarita.com/residents/open-data-portal) (OpenGov)

City of Santa Monica
+ [City of Santa Monica Open Data Catalog](https://data.smgov.net/browse)
+ [City of Santa Monica GIS Data](http://www.smgov.net/Departments/ISD/content.aspx?id=17850) shape files only, no services
+ [City of Santa Monica ArcGIS Open Data Hub](http://beta.smgov.opendata.arcgis.com/) _new!_
+ [City of Santa Monica GIS Data on Github](https://github.com/CityofSantaMonica/GIS) (geoJSON)(KML)
+ [City of Santa Monica / Big Blue Bus GTFS (static and real-time)](http://gtfs.bigbluebus.com/)
+ [City of Santa Monica Real-time Parking API](https://parking.api.smgov.net)
+ [City of Santa Monica Business Directory](https://data.smgov.net/Permits-Licenses/Active-Business-Licenses/wpc4-2j2n)
+ City of Santa Monica Annual Budgets [OpenGov](https://santamonicaca.opengov.com) [Socrata](https://data.smgov.net/browse?category=Finance&limitTo=datasets&utf8=%E2%9C%93)
+ [City of Santa Monica Landmarks](http://www.smgov.net/uploadedFiles/Departments/PCD/Programs/Historic-Preservation/Designated-Landmarks-Address.pdf) (PDF)
+ [City of Santa Monica Water Usage Records](https://data.smgov.net/Public-Services/Water-Usage/4nnq-5vzx)
+ [Open Santa Monica](http://open.smgov.net/) _Links to APIs, Socrata Portal, ArcGIS Open Data Hub, Apps and more_

City of West Hollywood
+ [City of West Hollywood Open Data Portal](https://data.weho.org/) (Socrata)

##County - Los Angeles
+ [Los Angeles County Open Data Portal](https://data.lacounty.gov/)(Socrata)
+ [Los Angeles County GIS Data Portal](http://egis3.lacounty.gov/dataportal/)
+ [Los Angeles County GIS Data Catalog](http://egis3.lacounty.gov/dataportal/data-catalog/)

##Other County Governmental Agencies
+ [LA County Bike Count Data Clearinghouse](http://www.bikecounts.luskin.ucla.edu/) Interactive map and data downloads available (CSV) (KML)
+ [Los Angeles Homeless Services Authority Counts](https://www.lahsa.org/homeless-count/results)
+ [Metro RSS Feeds](http://www.metro.net/news/metro-rss/) for News, Blogs, Meetings, Agendas, Jobs, and Service Advisories
+ [Metro Realtime API](http://developer.metro.net/introduction/realtime-api-overview/) overview and links to documentation
+ [Metro Bikeways KML/KMZ](http://developer.metro.net/introduction/bikeways-data/download-bikeways-data/)
+ [Metro Bike Share Data](https://bikeshare.metro.net/about/data/) Real-time station status (GBFS or GeoJSON), Quarterly GBFS usage data, Station Tables
+ [Metro GTFS Data](http://developer.metro.net/introduction/gtfs-data/download-metros-gtfs-data/)
+ [Metro GIS Data](http://developer.metro.net/introduction/gis-data/download-gis-data/) static shapefiles updated after each shakeup

##State - California
+ [List of State Agencies from CA Civic Lab](https://github.com/caciviclab/caciviclab.github.io/blob/master/state-agencies/js/data.json) (JSON) _Note maintained by [cacivicLa.org](http://caciviclab.org), not the State of CA_
+ [Division of Land Resource Protection Farmland Data](http://redirect.conservation.ca.gov/DLRP/fmmp/product_page.asp) county data includes biennial land use conversion tables, historic data summaries, field analyst reports, GIS data and metadata, and soil units
+ [Transporation Injury Mapping System - School Data and Maps](http://tims.berkeley.edu/resources/srts/main.php#summary)
+ [California Active Transporation Safety Information Pages](http://catsip.berkeley.edu/) links to laws, policies, master plans, publications and data
+ [State of California Office of the Attorney General - Criminal Justice Profiles](https://oag.ca.gov/crime/cjsc/criminal-justice-profiles) Interactive tables, export (CSV)
+ [State of California Office of the Attorney General - OpenJustice Data Portal](https://openjustice.doj.ca.gov/data)(CSVs)
+ [California Highway Patrol Statewide Integrated Traffic Records System (SWITRS)](http://iswitrs.chp.ca.gov/Reports/jsp/userLogin.jsp)
+ [California Health & Human Services Open Data Portal](chhs.data.ca.gov)(Socrata)
+ [Caltrans GIS Data Portal](http://www.dot.ca.gov/hq/tsip/gis/datalibrary/gisdatalibrary.html)
+ [California Board of Equalization](http://boe.ca.gov/dataportal/)
+ [California Landscape Conservation Cooperative](http://climate.calcommons.org/lists/datasets)

##Jobs
+ [City of Santa Monica Job Opportunities](http://agency.governmentjobs.com/santamonica/default.cfm)
+ [City of Los Angeles Job Opportunities](http://agency.governmentjobs.com/lacity/default.cfm)
+ [Los Angeles County Job Opportunities](http://hr.lacounty.gov/wps/portal/dhr/job_search)
+ [Metro Job Opportunities](https://jobs.metro.net/jobsearch.aspx)

##Other links
+ [Metro Developer](http://developer.metro.net/)
+ [National Day of Civic Hacking Datasets and Resources](http://hackforchange.org/datasets) Community sourced list
+ [OpenDataCatalog San Diego](http://catalog.opensandiego.org/) maintainted by CfA brigade
+ [City of Los Angeles Open Data Pilot](http://lamaps.maps.arcgis.com/home/) Currently just contains a few GIS datasets, see list of ArcGIS REST services above
+ [Democracy Map API](http://api.democracymap.org/) (JSON)(XML)
+ [Neighborland API](https://neighborland.com/docs)
+ [U.S. Census Tiger Shapefiles](http://forever.codeforamerica.org/Census-API/shutdown-2013.html) a list of where to find shp files not acccessbile through normal routes due to the shutdown
+ [City SDK from the Census Bureau](http://uscensusbureau.github.io/citysdk/)
+ [National Highway Traffic Safety Adminstration Fatality Analysis Reporting System and Data](http://www.nhtsa.gov/FARS) raw data available
+ [National Endowment for the Arts - Survey of Public Participation in the Arts](http://arts.gov/publications/additional-materials-related-to-2012-sppa) raw data available in multiple formats
+ [Experience LA Calendar RSS Feed](http://www.experiencela.com/calendar/rss)
+ [Google Civic Information API](https://developers.google.com/civic-information/)
+ [DataCatalogs.org](http://datacatalogs.org/) Searchable list of data catalogs from around the world
+ [Southern California Association of Governments GIS Portal](http://gisdata.scag.ca.gov/Pages/GIS-Library.aspx) _Seems to mostly be datasets uploaded from other authorities
+ [Homeland Infrastructure Foundation-Level Data (HIFLD)](https://hifld-dhs-gii.opendata.arcgis.com/)
+ [api.thirsty.la](http://api.thirsty.la/) scraped and compiled from some realtime LADWP water sensors in the Owens Valley, including the Los Angeles Aqueduct.
+ [EdDataZone](http://eddatazone.org/)
+ [Medicare](https://data.medicare.gov/) (Socrata)
+ [National Center for Education Statistics](http://nces.ed.gov/datatools/) _List of tools_

##Potential

+ [Cultivate LA](http://cultivatelosangeles.org/) interactive map and report on all urban ag sites in Los Angeles County

##Data Standards
+ [Compiler LA Civic Data Standards List](https://github.com/compilerla/civic-data-standards) _Now Maintained Separately_
