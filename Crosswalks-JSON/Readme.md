JSON Crosswalks
===============

This folder contains JSON crosswalks from individual organizational metadata profiles that were collected and documented by the ESIP Data Stewardship Committee to a common reference metadata schema (Schema.org). The crosswalks are only developed for the essential dataset metadata for discovery and citation, consisting of those defined in Fenner et al (2019) and several additional fields (Peng et al. 2026).

---------------------------------------------------
File Namning Convention:
---------------------------------------------------
crosswalkType_sourceSystem_destinationSystem_resourceType_version_creationDate.json

where,

crosswalkType = Metadata-Crosswalk

sourceSystem = Individual organizational metdata profile IDs (see Table 3.2 in Peng et al., 2026; also listed below)

destinationSystem = schemadotorg

resourceType = dataset

creationDate = Creation date of the JSON crosswalk file (YYYYMMDD)

---------------------------------------------------
Versioning Convention: 
---------------------------------------------------
vVVrRRpPP, where v represents the major version (release), r the revision (minor version), and p the patch level. VV, RR, and PP are two-digit integers (00–99).

*Examples:*

* v01r00p00 – Initial release
* v01r01p00 – First revision
* v01r01p02 – Second patch to Revision 1
* v02r00p00 – Second major release

---------------------------------------------------
JSON File Naming Example:
---------------------------------------------------
Metadata-Crosswalk_NASA-ESDIS_schemadotorg_dataset_v01r00p00-20260710.json

---------------------------------------------------
References
---------------------------------------------------
