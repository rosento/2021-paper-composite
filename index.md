This is the digital appendix to a paper under review for publication at CALCO 2021. If accepted, we will update this site as necessary to reflect the camera-ready version of the paper and include information on how to cite us.

# Included Files

The following files are included:

- the main CASL specification
  - [in raw form](./casl/atm.casl)
  - [on github](https://github.com/rosento/2021-paper-composite/blob/gh-pages/casl/atm.casl)
  - [in HTML](./casl_html/atm.pp.html),  with automatic formatting and light syntax highlighting by Hets
- an auxiliary CASL specification
  - [in raw form](./casl/atmAux.casl)
  - [on github](https://github.com/rosento/2021-paper-composite/blob/gh-pages/casl/atmAux.casl)
  - [in HTML](./casl_html/atmAux.pp.html), with automatic formatting and light syntax highlighting by Hets
- the KIV project
  - [as an auto-generated XHTML project description](./kiv_html/index.xml)
  - [as a ZIP archive importable in KIV](./kiv/ATM-kiv-project.zip)

# Installing our KIV Version
KIV is offered as an eclipse plugin, which is recommended to be used as part of the Eclipse-based Scala IDE.

We use Scala IDE version 4.7.0. Scala IDE is available [here](http://scala-ide.org/download/prev-stable.html).

We use KIV version 9. To install this:
  1. install and start Scala IDE
  2. choose the menu "Help" and then "Install New Software"
  3. in the text field "Work with" enter the installation source "http://scala-ide.org/download/prev-stable.html"
  4. select the items "KIV" and "KIV Dependencies"
  5. click on "Finish" at the bottom of the window
  6. restart Eclipse

More information on KIV installation and usage can found on [this site](https://www.uni-augsburg.de/en/fakultaet/fai/isse/software/kiv/) by Augsburg University.

To import our project:
  1. download the [ZIP file](./kiv/ATM-kiv-project.zip)
  2. start a Scala IDE with KIV installed
  3. in the "File" menu, select "Import"
  4. in the dialog that will open, select "KIV", then "Projects from KIV Archive"
  5. choose the file you downloaded in step 1
  6. click on "Finish"

# Our Hardware
We verified the safety property on a laptop with the following hardware specification:

| Model Name 	             |  MacBook Pro    |
|:---------------------------|:----------------|
| Model Identifier 	         |  MacBookPro14,1 |
| Processor Name 	         |  Intel Core i5  |
| Processor Speed 	         |  2,3 GHz        |
| Number of Processors 	     |  1              |
| Total Number of Cores      |  2              |
| L2 Cache (per Core) 	     |  256 KB         |
| L3 Cache 	                 |  4 MB           |
| Hyper-Threading Technology |  Enabled        |
| Memory 	                 |  8 GB           |

