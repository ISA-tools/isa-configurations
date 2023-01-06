## What are ISA configurations

ISA configurations are set of XML files defining ISA tables and associated annotation requirements, which can be used by the ISA validators (java or python) to check an instance ISA archive. The checks cover both that
  * correct ISA syntax is used.
  * annotation requirements defined in the ISA configuration are met (e.g. mandatory presence of a value for a specific field).

ISA configurations are created in the ISAcreator configurator.

The latest version of the tool is downloadable from the ISA GitHub site (https://github.com/ISA-tools/ISAconfigurator/downloads) or from the main ISA website (http://www.isa-tools.org).


🚩: **but please note that this java desktop tool is no longer supported nor maintained**


The configurations are designed to meet the requirements of one or more checklist(s) ( [http://www.mibbi.org minimum information), specifying the required fields, and/or enabling values to be drawn from a set of ontology terms.

## Download ISA configurations

* All available ISA configurations produced by the ISA tools team and collaborators (ISA commons, http://isacommons.org/) can be viewed via a table at the dedicated ISA-tools Configuration File page:
(http://www.isa-tools.org/format/configurations/)

* ISA configurations are also available at:
(https://github.com/ISA-tools/Configuration-Files/wiki/ISA-tools-Configuration-Files)

* ISA configurations maintained by specific communities also exist:

  * Plant Phenotyping ISA Configuration: https://github.com/ISA-tools/ISA-Tab-for-plant-phenotyping/ forked from https://github.com/MIAPPE/ISA-Tab-for-plant-phenotyping

  * Cell Migration Assay ISA Configuration: https://github.com/ISA-tools/MIACME-1 forked from https://github.com/CellMigStandOrg/MIACME


## ISA configuration XSD

An ISA configuration is comprised of a set of XML files following a schema available here https://github.com/ISA-tools/ISAvalidator-ISAconverter-BIImanager/blob/master/import_layer/src/main/resources/xsd/isatab_configurator.xsd


## Get help
Contact the ISA team ([http://www.isa-tools.org/contact.html) if you need a new configuration that fits your specific needs, e.g. a different, or checklist, or set of ontologies/controlled vocabularies.

## Notify us
If you have created an ISA configuration for your community, do get in touch for registering your resource and making it findable from the ISA community page. We could also review and advise on the newly created configurations.
