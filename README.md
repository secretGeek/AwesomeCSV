# Awesome CSV

CSV remains the most futuristic data format from the distant past.

XML has risen and fallen. JSON is just a flash in the pan. YAML is a poisoned chalice. **CSV will outlast them all.**

When the last cockroach ceases to live, her final act will be to scratch her date of death in a CSV file, for posterity.

Here are some awesome tools for dealing with CSV:

## Awesome CSV Tools

* [NimbleText/Live](https://NimbleText.com/Live)<sup><a href='#footnote1'><strong>*</strong></a></sup>: Use simple patterns to manipulate separated data into any shape you wish.
* [PapaParse](https://www.papaparse.com): A powerful, in-browser CSV parser
* [CSVKit](http://csvkit.readthedocs.org/en/0.7.3/): CSV utilities that includes csvsql, csvgrep, csvstat, and more
* [XSV](https://github.com/BurntSushi/xsv): A fast CSV command-line toolkit written in Rust
* [Miller](http://johnkerl.org/miller/doc/): like sed, awk, cut, join, and sort for name-indexed data such as CSV
* [ParaText](http://www.wise.io/tech/paratext): CSV parsing at 2.5 GB per second
* [CSVGet](http://github.com/fizx/csvget/tree/master): Get structured data from sites as CSV
* [CSVfix](https://code.google.com/p/csvfix/): a tool for manipulating CSV data
* [StreamingPivot](http://streamingpivot.com/): Pivot and visualize CSV data purely in the browser
* [Tad](http://www.tadviewer.com):  A fast, free cross-platform CSV viewer
* [Nvd3-tags](http://blog.tryolabs.com/2015/02/27/nvd3-tags-a-tiny-library-for-making-charts-from-csv-data/): A tiny library for making charts from csv data
* [Mockaroo](https://www.mockaroo.com/): Random Data Generator for CSV / JSON / SQL / Excel

### Repair or Validate CSV

* [Csvlint.go](https://github.com/Clever/csvlint): Command line tool for validating CSV files against RFC 4180
* [csvstudio](http://www.csvstudio.com): A smart app to repair syntax errors in very large CSV files

### Treat CSV as SQL:

* [TextQL](http://dinedal.github.io/textql/) Execute SQL Against CSV or TSV
* [Datasette Facets](https://simonwillison.net/2018/May/20/datasette-facets/): Faceted Browse and a JSON API for any CSV File or SQLite DB


### Convert to or from CSV:
* [CSV to Table](https://github.com/vividvilla/csvtotable): Convert CSV files to searchable and sortable HTML table

## CSV <-> JSON

* [Agnes](http://www.secretgeek.net/agnes/twoWay.html)<sup><a href='#footnote2'><strong>**</strong></a></sup>: two way Csv to Json


## CSV Essays
* [Thinking about CSV](https://blog.datacite.org/thinking-about-csv/)
* [In Praise of CSV](https://usopendata.org/2015/03/10/csv)
* [Stop Rolling Your Own CSV Parser!](http://www.secretgeek.net/csv_trouble)



## Reference Data in CSV

See:
* [Reference data in csv](https://datahub.io/collections/reference-data)


## Awesome CSV Standards

>The wonderful thing about standards is that there are so many of them to choose from.<br />&mdash;(Possibly) Grace Hopper

* [RFC 4180](https://tools.ietf.org/html/rfc4180) &mdash; "Common Format and MIME Type for Comma-Separated Values (CSV) Files"
  * [Definition of the CSV Format](https://tools.ietf.org/html/rfc4180#section-2)
  * [MIME Type Registration of text/csv](https://tools.ietf.org/html/rfc4180#section-3)
* [W3C: Model for Tabular Data and Metadata on the Web](https://www.w3.org/TR/tabular-data-model/)
* [CSV Schema Language – A Language for Defining and Validating CSV Data](http://digital-preservation.github.io/csv-schema/csv-schema-1.2.html)

* [CSV 1.1](https://csv11.github.io/) &mdash; CSV Evolved (for Humans) - Easy-to-Write, Easy-to-Read


# Meta: Other Lists of CSV Tools and References

* [List of command line tools for manipulating CSV, XML, HTML, JSON, INI, etc.](https://github.com/dbohdan/structured-text-tools)
* META: this list as csv

* [Awesome Comma-Separated Values (CSV) - What's Next? - Frequently Asked Questions (F.A.Q.s) - Libraries & Tools)](https://github.com/csv11/awesome-csv)



-----

`*` <span id='footnote1' ></span> I'm the author of NimbleText. Of course I put it first on the list. If I didn't personally rate it I wouldn't have spent so much time making and improving it!

`**` <span id='footnote2' ></span> I wrote Agnes but don't really endorse it for others to use (thus haven't migrated the source code to github). It's a slow and non-streaming. On the plus side, it has a more comprehensive test suite and simpler api than most.
