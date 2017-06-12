# Storytelling With Data 2017 Liberating Data from Documents: Free and Reliable Methods
This repo contains information used in an introductory class on extracting data from PDFs taught at the [Boston University Storytelling with Data Workshops](https://www.bu.edu/com/data-storytelling/index.html) on 6/13/17.

## [Xpdf](http://www.foolabs.com/xpdf/)
Xpdf is a command line-based tool for converting PDFs to text files.

### Key Commands
.\pdftotext san_diego_school_lice.pdf sd_lice.txt
.\pdftotext -layout san_diego_school_lice.pdf sd_lice.txt
.\pdftotext -table san_diego_school_lice.pdf sd_lice.txt

## Tabula(http://tabula.technology/)
Tabula is a browser-based tool for extracting tables within PDFs and converting them to other file formats.

## [Cometdocs](https://www.cometdocs.com/)
CometDocs is a web-based service for converting between many different file formats.

### In Excel, the =left and =right functions allow you to quickly pull data from one column into another. This is particularly useful in data cleaning.
=left(text, [number of characters])
=right(text, [number of characters])
