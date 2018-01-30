# opendata
This is a repository for open data sources to use with a JKAN platform

The use of GitHub as a potential repository for open source data is also being tested. Learning points will be added as the project progresses

## Advantages

* No hosting costs
* Deals with any file type
* Preview works really well for smaller .csv datasets and for geojson datasets - user friendly
* Files without preview (i.e. too large) give the option to download as a button
* Really quick and simple to upload files
* Can add markdown files as sources for additional/supporting information (which can be linked via JKAN)

## Issues

* Limit on GitHub repo size - not scalable
* Preview will not work for file sizes over a certain size (can't find this limit currently)
* No (obvious) preview for geocoded point data files
* Off-putting to see large files with an error message and the option to View Raw
* Downloading is not intuitive. If previewed then difficult for a new user to work out how to download
* Awkward to create a directory structure when uploading datafiles (but see suggestion below)

## But....
[Octopub](https://octopub.io/) offers a complementary interface that enables downloads more easily and includes metadata. Enables better management of datasets, and presents with .md files. [See an example](http://digital.oxford.gov.uk/hmo-simplified-register/)

## Ideas
* Devon use a separate repo for each category, which allows for a link to download all the data as a zip file using the 'clone or download' button
* If separate repos used for each data category, a README.md file can be automatically displayed with additional instructions
* Use Google Maps for point data files - easier than geocoding elsewhere, and can be downloaded as .kml or .kmz files
* Alternatively, just accept that files that need to be downloaded can be stored elsewhere in another repository (e.g. council website giving root URL for file)
