# ESPD Exchange Data Model (EDM)
# Version 3.0.1

## Introduction

The ESPD Exchange Data Model is the technical representation of the legal European Single Procurement Document. It is used to support interoperability between ESPD services provided all over Europe.

## ESPD Wiki

To have a comprehensive view of what ESPD-EDM is and how to use it, we **strongly** recommend visiting the [ESPD-EDM Wiki](https://github.com/ESPD/ESPD-EDM/wiki), that aims to be the **Unique Access Point** for all of its resources: documentation, tools, assets, etc.

## Documentation

* v3.0.1
* [v3.0.0](https://docs.ted.europa.eu/ESPD-EDM/3.0.0/index.html)
* [v2.1.1](https://docs.ted.europa.eu/ESPD-EDM/2.1.1/index.html)
* [v2.1.0](https://docs.ted.europa.eu/ESPD-EDM/2.1.0/index.html)
* [v2.0.2](https://docs.ted.europa.eu/ESPD-EDM/2.0.2/index.html)
* [v1.0.2](https://docs.ted.europa.eu/ESPD-EDM/1.0.2/index.html)

## Version 3.0.1 (Early 2022)
This new version of the ESPD-EDM includes:
* Reorganisation of the distribution package folders

  ![image](https://user-images.githubusercontent.com/67598083/154528710-f29c4d2b-7a23-49e0-9cb4-7448a5056821.png)

  * **\__ESPDTeam__**: contains files for ESPD Team internal use in maintenance tasks of the ESPD-EDM;
  * **codelists**: contains the different code lists used in ESPD in Genericode format and the criterion structure definition.
  * **conceptual-model**: contains the UML conceptual model of the ESPD in .eap, .xmi and HTML format.
  * **java-library**: contains the XML schemas used to generate the JAXB annotated Java classes.
  * **ubl-2.3**: contains a redistribution package from UBL 2.3.
  * **validation**: contains business rules validation files for Schematron and Testbed.
  * **xml-examples**: contains default ESPDRequest and ESPDResponse xml samples and the criterion xml schema.
* Updated ESPD-EDM conceptual model
* Documented handbook migration to [Ted Developer Docs](https://docs.ted.europa.eu/home/index.html)

For more information regarding the release, please refer to the [release notes](https://docs.ted.europa.eu/ESPD-EDM/3.0.1/release_notes.html).

## Use
The ESPD-EDM is made publicly available through Github. 
* If you just want to browse or access the model, you don't need to be registered in Github.
* If you want to create issues concerning the ESPD-EDM you have to be a registered user in Github.
