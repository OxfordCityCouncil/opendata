# opendata
(This was a repository used for open data sources to use with a JKAN platform. This has now transferred to https://github.com/oxopendata)

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

## Ideas
* Devon use a separate repo for each category, which allows for a link to download all the data as a zip file using the 'clone or download' button
* If separate repos used for each data category, a README.md file can be automatically displayed with additional instructions
* Use Google Maps for point data files - easier than geocoding elsewhere, and can be downloaded as .kml or .kmz files
* Alternatively, just accept that files that need to be downloaded can be stored elsewhere in another repository (e.g. council website giving root URL for file)

## But....
[Octopub](https://octopub.io/) offers:
* A means to upload and control datasets stored on GitHub
* Creates a repo for each dataset, overcoming most issues with size (would need a separate account to avoid clash with other repos)
* A better user interface, presented as a Markdown file and including metadata (incl. schema)
* Allows multiple files for one dataset
* Preview function allows large datasets to be seen as a sample table (unlike GitHub preview)
* Enables downloads more easily, either as a single file or grouped
* Enables datasets to be loaded and tested against schemas (you can upload your own)

However, currently only deals with .csv files
[See an example](http://digital.oxford.gov.uk/hmo-simplified-register/)

UPDATE: ODI are redeveloping Octopub which will allow all file types to be uploaded. Due to launch March 2018

Staging version of the redeveloped tool is at https://octopub-staging.herokuapp.com
