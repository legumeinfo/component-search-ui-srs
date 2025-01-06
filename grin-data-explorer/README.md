# GRIN trait data query and explorer - to search or explorer the GRIN trait data 

This is the requirements doc for the SoyBase GRIN data explorer. This component should be enable users to select one or more traits from a selected "traitClass" or "traitName". For the users to learn more info about the traits, the "traitDescription" from the traits-Genus.json file, should be available to view.

## Specification version
Version: 0.1

<details>
This specification was completed in late December 2024 and was initally designed for a single species. 
Currently all 
</details>

## Input
  - Limited search to choosen GRIN accessions
    - Text box for choosen GRIN accessions
    - Same input as below
  - Search all GRIN accessions
    - Select at least one trait
    - Select value of trait
      - Use a range slider if the trait value is digital (numerical)
      - Use a multi select dropdown if the trait value is a character (alphabetical)

### Input Mockup Images
![GRIN Explorer ALL accessions](https://github.com/legumeinfo/website-ui-specs/blob/GRIN-data-explorer/grin-data-explorer/GRIN_Explorer_all_accessions.png "Search all accessions")

![GRIN Explorer SELECTED accessions](https://github.com/legumeinfo/website-ui-specs/blob/GRIN-data-explorer/grin-data-explorer/GRIN_Explorer_selected_acessions.png "Search selected accessions")

## Output
The output will be in a tabular layout, with the following content in each GRIN accession anchored row:
  - 


### Output Mockup Images
![GRIN Explorer output](https://github.com/legumeinfo/website-ui-specs/blob/GRIN-data-explorer/grin-data-explorer/GRIN_Explorer_output.png "GRIN Data Explorer Results Table")

## Implementation notes







