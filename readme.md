#Radio National program data

Here are some CSV files containing program metadata from ABC Radio National harvested through the [Trove API](http://help.nla.gov.au/trove/building-with-trove/api).

See [here](http://www.nla.gov.au/blogs/trove/2014/04/17/harvesting-radio-national) and [here](http://www.nla.gov.au/blogs/trove/2014/05/01/whats-in-a-word) for more about the RN data in Trove.

##Data available

###All years

* A complete dump of ABC Radio National records in Trove up to 31/12/2014 is available here -- abcrn-all.zip

###2000 - 2014 ([on GitHub](https://github.com/wragge/radio-national-data))

* AM (current affairs) -- one record per segment
* The World Today (current affairs) -- one record per segment
* PM (current affairs) -- one record per segment

##Format

CSV files with the following fields:

* title
* contributor (multiple values separate by semicolons)
* date (YYYY-MM-DD)
* isPartOf (program title -- see programs.txt for a complete list)
* abstract
* subject (multiple values separate by semicolons)
* publisher
* rights
* url (link to ABC website)
* troveUrl (link to Trove record)

##Example apps

* [In a word...](http://inaword.dhistory.org/)

##More information

* [GitHub repository](https://github.com/wragge/radio-national-data)
* Compiled by [Tim Sherratt](http://discontents.com.au/about-me) ([@wragge](http://twitter.com/wragge))

