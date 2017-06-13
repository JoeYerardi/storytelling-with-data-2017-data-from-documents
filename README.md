# Storytelling With Data 2017 Liberating Data from Documents: Free and Reliable Methods
This repo contains information used in an introductory class on extracting data from PDFs taught at the [Boston University Storytelling with Data Workshops](https://www.bu.edu/com/data-storytelling/index.html) on 6/13/17.

We will convert two files from PDFs into machine-readable data using three different tools, import that data into Excel, clean and analyze it.

## [Sublime Text](https://www.sublimetext.com/)
Sublime Text is a good text editor that'll help you understand what your raw, converted text file looks like before importing it into Excel.

## [Xpdf](http://www.foolabs.com/xpdf/)
Xpdf is a command line-based tool for converting PDFs to text files.

## [Tabula](http://tabula.technology/)
Tabula is a browser-based tool for extracting tables within PDFs and converting them to other file formats.

## [Cometdocs](https://www.cometdocs.com/)
CometDocs is a web-based service for converting between many different file formats.

### Useful Excel formulas, the =left and =right functions allow you to quickly pull data from one column into another. This is particularly useful in data cleaning.
=left(text, [number of characters])
=right(text, [number of characters])

### Two tips and a warning for checking the integrity of your newly-converted data.
1. Does your original PDF file contain a row with the sum of each column? Sum your converted data for each column to make sure it matches the figures in that row.
2. Use column sorting liberally. It'll help you quickly get rid of blank rows and other artifacts that tend to accompany data converted from PDFs.
3. Beware errant text (e.g. page numbers, header rows that repeat on every page, rows of summary data) in the PDF. That stuff can easily sneak into your data columns and seriously trip up your analysis.
