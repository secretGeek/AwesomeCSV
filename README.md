Awesome CSV 
A carefully curated list of CSV-related tools and resources

CSV remains the most futuristic data format from the distant past.

XML has risen and fallen. JSON is just a flash in the pan. YAML is a poisoned chalice. CSV will outlast them all.

When the final cockroach breathes her last breath, her dying act will be to scratch her date of death in a CSV file for posterity.
Contents
- Tools
  - Repair or Validate CSV
  - Treat CSV as SQL
  - Convert to or from CSV
  - CSV <-> JSON
- Essays
- Data
- Conferences
- Standards
- META: Other similar lists
- Code of Conduct
- Funtribute
- Footnotes
Here are some awesome tools for dealing with CSV:
Tools
- NimbleText/Live - Use patterns to manipulate CSV; the world's simplest code generator *.
- PapaParse - A powerful in-browser CSV parser.
- d3-dsv - d3.js parser and formatter module for delimiter-separated values.
- CSVKit - CSV utilities that includes csvsql / csvgrep / csvstat and more.
- QSV - A fast CSV command-line toolkit written in Rust, (an update to xsv).
- sed (gnu tool) - Stream editor.
- gawk (gnu tool) - Text processing and data extraction using awk.
- awk by example - Comprehensive examples of using awk.
- Miller - Like sed / awk / cut / join / sort etc for name-indexed data such as CSV.
- ParaText - CSV parsing at 2.5 GB per second.
- CSVGet - Get structured data from sites as CSV.
- CSVfix - A tool for manipulating CSV data.
- Tad - A fast free cross-platform CSV viewer.
- csvtodashboard - Convert, clean, query (SQL) and visualize CSV entirely in the browser - local-first, nothing is uploaded.
- Nvd3-tags - A tiny library for making charts from csv data.
- Powershell: Import-CSV - Powerful in-built facility for dealing with CSV (example).
- CSV Tools - A collection of useful CSV utilities.
- graph-cli - Flexible command line tool to create graphs from CSV data.
- CSV to SQL - Online tool to create insert/update/delete etc from CSV data.
- C#: kbCSV - An efficient, easy to use .NET parsing and writing library for CSV.
- csvprintf - UNIX command line utility for parsing and formatting output based on CSV files.
- Ron's Data Edit (new modern version of Ron's CSV Editor) - Handles big files, does miraculous things. A timeless editor for a timeless format.
- Rainbow CSV plugins - Collection of text editor plugins for CSV/TSV syntax highlighting. Available for Vim, VS Code, Atom, Sublime Text and other editors.
- ExtendsClass - A simple CSV comparator.
- Mighty Merge - join/union csv files.
- Modern CSV - A tool for editing CSV files and viewing large files.
- Data Wrangler - Data Wrangler is a code-centric data cleaning tool that is integrated into VS Code and VS Code Jupyter Notebooks.
- CSV to SQL - Upload a CSV file, set a table name, and generate SQL inserts instantly.
- SmoothCSV - A fast, powerful, and intuitive CSV editor for Mac, Windows, and Linux.
Repair or Validate CSV
- Csvlint.go - Command line tool for validating CSV files against RFC 4180.
- csvstudio - A smart app to repair syntax errors in very large CSV files.
- scrubcsv - Remove bad records from a CSV file and normalize (requires rust)
- reconcile-csv - Find relationships between a set of related CSVs
- CSVUndo - Free browser-based tools to repair Excel-damaged CSV files (scientific notation, lost leading zeros, mojibake, wrong encoding); includes a public privacy-verification guide.
Generate Table Schema
- CSV Schema — Analyzes a CSV file and generates database table schema, all within the browser
- Wanted: More tools in this category.
Treat CSV as SQL
- TextQL - Execute SQL against CSV or TSV.
- Datasette Facets - Faceted browse and a JSON API for any CSV File or SQLite DB.
- q - Run SQL Directly on CSV Files
- RBQL - Rainbow Query Language, a SQL-like language with JavaScript or Python backend.
- PSKit Query — Powershell module lets you run simple queries over objects, including imported with csv
Convert to or from CSV
- CSV to Table - Convert CSV files to searchable and sortable HTML table.
CSV <-> JSON
- Agnes - Two way Csv to Json **.
- csv2json - online tool to convert your CSV or TSV formatted data to JSON and vice versa.
- csv-to-json - Easy, privacy-friendly and offline-first online csv to json converter.
Essays
Once you've found the perfect data serialization file format, you stop looking

David Wengier

- Thinking about CSV - Martin Fenner.
- In Praise of CSV - Waldo Jaquith.
- Stop Rolling Your Own CSV Parser! - Leon Bambrick ***.
- So You Want To Write Your Own CSV code? - Thomas Burette.
- Falsehoods Programmers Believe About CSVs - Jesse Donat.
- ASCII Delimited Text - Not CSV or TAB delimited text - Ronald Duncan.
Generate Data
- Fake Name Generator - Generate fake names with other identity data in bulk for testing.
- Mockium - Test data generator for CSV / JSON / SQL / XML.
- Mockaroo - Random data generator for CSV / JSON / SQL / Excel.
Data
- US Data.gov - 18789+ CSV datasets.
- Australian Government Open Data - 2715+ CSV datasets.
- Reference data in csv - Easy-to-use reference data in CSV and JSON formats.
- awesome-public-datasets - A topic-centric list of high-quality open datasets in public domains.
- United Nations data - Data from the UN
Conferences
- csv,conf - A community conference for data makers everywhere.
Standards
The wonderful thing about standards is that there are so many of them to choose from.
—(Possibly) Grace Hopper.

- RFC 4180 (html version) - "Common format and MIME Type for Comma-Separated Values (CSV) Files".
  - Definition of the CSV Format
  - MIME Type Registration of text/csv
- W3C: Model for Tabular Data and Metadata on the Web
- CSV Schema Language - A language for defining and validating CSV data.
- csv,specs - Comma-Separated Values (CSV) Format Specifications (and Tests) incl. CSV v1.0, CSV v1.1, CSV Strict, CSV <3 Numerics, CSV<3 JSON, CSV <3 YAML.
- Tabular Data Resource - A Data Resource specialized for describing tabular data like CSV files or spreadsheets
- CSVY - A standard for adding a YAML header to CSV files to describe their format
META: Other similar lists
- structured-text-tools - List of command line tools for manipulating CSV / XML / HTML / JSON / INI etc.
- META-META - This list as CSV.
- META-META-META - A NimbleText pattern that produces this markdown page from this list as a CSV.
Code of Conduct
See [Code of Conduct](code-of-conduct.md)
Funtribute
To experience the fun of contributing, see [Contributing](contributing.md)
Footnotes
* <span id='footnote1' ></span> I'm the author of NimbleText. Of course I put it first on the list. If I didn't personally rate it I wouldn't have spent so much time making and improving it.

** <span id='footnote2' ></span> I wrote agnes but don't particularly endorse it for others to use (thus haven't migrated the source code to GitHub). It's slow and non-streaming. I'd go with papa-parse. On the plus side, agnes has a more comprehensive test suite and simpler api than most.

*** <span id='footnote3' ></span> Mine too.
License

To the extent possible under law, Leon Bambrick has waived all copyright and related or neighboring rights to this work.
