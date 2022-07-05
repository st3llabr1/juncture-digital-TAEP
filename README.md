<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Edison Notebook NP-122"
       author="Erin Mustard"
       banner="https://edison.rutgers.edu/templates/sas-red/images/rutgers/red_banner.png" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.archivelab.org/iiif/taepnotebook-NP122$1/manifest.json">

# Basic usage

## Image

Some of the chemicals mentioned in this notebook include [Camphor Bromide](https://pubchem.ncbi.nlm.nih.gov/compound/Camphor-Bromide) 
<param ve-image
       label="Chromium III Bromide" 
       description="chemical formula of Chromium III Bromide" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/2/2e/Kristallstruktur_Bismut%28III%29-iodid.png">

## Image

This notebook dates from ca. April 1919. The pocket notebook contains notes by Thomas A. Edison relating to experiments on chemicals, Portland cement, phonograph records, storage batteries, resin, shellac and x-rays. There is a list of chemicals for iron experiments and notes about expenses, cement sales and foreign record prices. The notebook was originally found in Thomas A. Edison's desk at Glenmont.
<param ve-image 
       abel="Glenmont, Edison's Estate" 
       description="photo of Glenmont" 
       license="public domain" 
       url="https://en.wikipedia.org/wiki/Thomas_Edison_National_Historical_Park#/media/File:Edison_home_NJ.jpg">
       
## Map

All notebooks in this collection were found at Edison's Glenmont Estate, located in West Orange, New Jersey. It is the current site of [Edison National Historical Park](https://www.nps.gov/edis/index.htm). 
<param ve-entity eid="Q220">
<param ve-map center="Q220" zoom="10" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.archivelab.org/iiif/taepnotebook-NP122$4/manifest.json">
<param ve-map center="Q36600" zoom="11">

# References
