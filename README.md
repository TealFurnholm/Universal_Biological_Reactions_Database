# Universal_Biological_Reactions_Database
A compiled and cross-id mapped enzymatic database with reaction direction, product and reactant compounds.

This is #3 of a series of pipelines that create-curate a Universal Reference for various 'omics data.
    <br>1. Universal Taxonomy Database: [found here](https://github.com/TealFurnholm/Universal-Taxonomy-Database)
    <br>2. Universal Compounds Database: [found here](https://github.com/TealFurnholm/Universal_Biological_Compounds_Database/)
    <br>3. Universal Reactions Database: *this repository*
    <br>4. Universal Protein Alignment Database: [found here](https://github.com/TealFurnholm/Universal_Microbiomics_Alignment_Database)
    <br>5. Universal ncRNA Alignment Database: [found here](https://github.com/TealFurnholm/Fix_RNACentral_Taxonomy)

## How Universal?
These databases span all kingdoms of life. The databases allow the simultaneous identification of microbial community phylogeny and functions. All the biological molecules/compounds and their data are linked to their enzymes and transporters to map the flow of metabolites in microbe-microbe or microbe-host interactions. 
The databases are used for (meta)transcriptomics, (meta)proteomics, metabolomics, metagenomics, and for novel binning and MAG quality control software I've created. This way many types of data can be combined into a secondary analysis, with taxonomy and functions being directly linked. It also covers both the protein and the non-coding fraction of sequencing. 

## One Manual Input: BioCyc
For the most part, this script is automated - except the BioCyc collection. You'll need to request a license to download their flat files. They will give you a username, password, and link to the download site - you'll be asked to asked to provide these for downloading the files. 

## Automation
This script automatically downloads data it needs off the various public repositories.
 - Upshot - you shouldn't have to do anything but run it
 - Downside - those repositories may change their links, so you may have to fix the links in the code
<p></p>I put as many "wget" commands as I could near the top of the script so you could easily mod them if need be.

## Get Started Here:
https://github.com/TealFurnholm/Universal_Biological_Compounds_Database/wiki#4-create-reactions-database
