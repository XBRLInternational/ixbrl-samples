# iXBRL sample documents

This repository contains a number of Inline XBRL (or
[iXBRL](https://www.xbrl.org/ixbrl)) sample documents created by [XBRL
International](https://www.xbrl.org).

These samples were created to demonstrate that the requirement to use XHTML in
iXBRL documents imposes no practical constraints on the design and styling of
the documents.

The samples also demonstrate some of the practical benefits and features of
using HTML+CSS rather than PDF for financial reports, including the ability to
make the reports mobile-friendly through the use of responsive CSS, and the
ability to target print media in order to create high quality, printable
documents (and PDFs).

As well as including the final iXBRL documents, this repository includes
documentation on how these samples were prepared, and the source from which
they were generated (see [iXBRL creation](#ixbrl-creation))

## GLEIF Annual Report 2017

This sample is based on an extract from the Global Legal Entity Identifier
Foundation's ([GLEIF](https://www.gleif.org)) 2017 annual report.  

* [Original PDF][1]
* [iXBRL][2] (GitHub Preview)
* [Browse iXBRL files](https://github.com/XBRLInternational/ixbrl-samples/tree/master/ixbrl/gleif-annual-report-2017)


[1]: https://www.gleif.org/content/1-about/9-governance/11-annual-report/2018-04-19_gleif_annual-report_2017-final.pdf
[2]: https://htmlpreview.github.io/?https://github.com/XBRLInternational/ixbrl-samples/blob/master/ixbrl/gleif-annual-report-2017/gleif-annual-report-2017.html

### Features

Where screen space allows, the iXBRL recreates the A3 landscape formatting of
the original PDF, switching to portrait A4 formatting on narrower screens.

The stylesheet also includes a basic effort to make the document more usable on
mobile devices by removing the pagination effect at lower screen widths,
avoiding the use of columns, and other formatting changes to make better use of
the available width.

The stylesheet includes print-specific formatting which removes the pagination
effect so that the document is formatted onto real pages.  

## XBRL International Financial Statements 2018

TODO

## iXBRL creation

TODO





