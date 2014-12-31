#Radio National program data

Here are some CSV files containing program metadata from ABC Radio National harvested through the [Trove API](http://help.nla.gov.au/trove/building-with-trove/api).

See [here](http://www.nla.gov.au/blogs/trove/2014/04/17/harvesting-radio-national) and [here](http://www.nla.gov.au/blogs/trove/2014/05/01/whats-in-a-word) for more about the RN data in Trove.

##Data available

###2014

* AM (current affairs) -- one record per segment -- [am-2014.csv](https://github.com/wragge/radio-national-data/blob/master/2014/am-2014.csv)
* The World Today -- one record per segment -- [world-today.csv](https://github.com/wragge/radio-national-data/blob/master/2014/world-today-2014.csv)
* PM (to come soon)

##Format

CSV files with the following fields:

* title
* contributor (multiple values separate by semicolons)
* date (YYYY-MM-DD)
* isPartOf (program title)
* abstract
* subject (multiple values separate by semicolons)
* publisher
* rights
* url (link to ABC website)
* troveUrl (link to Trove record)

