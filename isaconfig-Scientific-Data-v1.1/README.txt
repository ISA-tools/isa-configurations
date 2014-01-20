Modification to SciData configuration (from v1 to v1.1)

1. reuse all ISA-default-config technology specific table definitions to address failure to validate BII-I-1 with SciData Config v1.
2. add Comment[Data Repository] and Comment[Data Record Accession] to every table definition and make fields mandatory [note: these must be present for the validation to be succesfull however no reqiurement is made for those fields to hold a value]
3. Switch 'is-multiple-value' attribute from 'false' to 'true' for 'Data Transformation Name' and 'Derived Data File'. 
3. Addition of a generic assay table definition xml file implementing the Scidata specificiations with wild-card characters for Measurement and Technology Type. This allows catch-all and user defined MT and TT to be reported.
4. Modification of the study sample definition making the 'Material Type' field to be an ontology term (initially a string) in the configuration. This is to allow the URI reannotation functions now implemeneted in the latest release of ISAcreator to be performed on Material Type fieds.
5. Editing of Investigation configuration file to remove the white space in the 'Commment[Created with configuration]' & 'Comment[Last Opened With Configuration]' fields used to track the information about the configurations used to create or last save isatab archives


