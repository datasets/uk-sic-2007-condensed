<a href="https://datahub.io/core/uk-sic-2007-condensed"><img src="https://badgen.net/badge/icon/View%20on%20datahub.io/orange?icon=https://datahub.io/datahub-cube-badge-icon.svg&label&scale=1.25)" alt="badge" /></a>

UK condensed standard industrial classification of economic activities (SIC) 2007 codes

## Data

List of the Office of National Statistics (ONS) codes for classifying economic activity of business establishments and other standard units. Only codes in the condensed list can be used on a company's annual return. SIC 2007 was adopted from 1st January 2008.

### Notes

UK condensed SIC 2007 codes issued by [Companies House](https://www.gov.uk/government/organisations/companies-house) are a subset of the codes published by the [ONS](http://www.ons.gov.uk/) whose [copyright page](http://www.ons.gov.uk/ons/site-information/information/creative-commons-license/index.html) supports an assumption of open data.

## Preparation

The [Condensed SIC list](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/376462/condensedSICList.pdf) was downloaded and converted using [PDFMiner](http://www.unixuser.org/~euske/python/pdfminer/) `pdf2txt.py -c UTF-8 -o condensedSICList.txt condensedSICList.pdf`. The text file was edited programmitically `find /v /c "" condensedSICList.txt` and manually, then sanity checked against [Nathan Pitman's Sic-Codes CSV](https://github.com/nathanpitman/sic-codes/blob/master/2007/sic_codes.csv). An error with code 14200 appended code 14190 was corrected.

## License

Adapted from [data](https://www.gov.uk/government/publications/standard-industrial-classification-of-economic-activities-sic) from the Office for National Statistics licensed under the Open Government Licence v.3.0.