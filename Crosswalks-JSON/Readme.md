Crosswalks in JSON
======================

This folder contains JSON crosswalks from individual organizational metadata profiles, collected and documented by the ESIP Data Stewardship Committee, to a common reference metadata schema based on Schema.org. The crosswalks cover only the essential dataset metadata for discovery and citation, consisting of the elements defined in Fenner et al. (2019) together with several additional fields identified by Peng et al. (2026).

---------------------------------------------------
File Naming Convention:
---------------------------------------------------
crosswalkType_sourceSystem_destinationSystem_resourceType_version_creationDate.json

where,

crosswalkType = Metadata-Crosswalk

sourceSystem = Individual organizational metdata profile IDs (see Table 3.2 in Peng et al., 2026; also listed below)

destinationSystem = schemadotorg

resourceType = dataset

creationDate = Creation date of the JSON crosswalk file (YYYYMMDD)

---------------------------------------------------
**Versioning Convention:** 

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

Fenner, M., M. Crosas, M., J.S. Grethe, D. Kennedy, H. Hermjakob, and others. (2019) 'A data citation roadmap for scholarly data repositories.’ Sci. Data 6. https://doi.org/10.1038/s41597-019-0031-8 

Peng, G., M. Wu, R.A. Ringuette, J. Blythe, A. Shepherd, E. Söding, L. Wyborn, E. Wood-Charlson, N.A. Ritchey, M.B. Jones, N. Atkins, M. Abarca, D. Kottmeier, U. Schindler, S.H. Lubkin, and ESIP Data Stewardship Committee. (2026) ‘Advancing Cross-Organizational Interoperability Through Data Stewardship — Machine-Interpretable Crosswalks From Earth Science Organizational Metadata Profiles to Schema.org.’ ESIP Data Stewardship Committee Report. Document ID: ESIP-DSC-002-2026. Version: v01r00-20260724. License: CC-BY 4.0 International. ESIP Zenodo. https://doi.org/10.5281/10.5281/zenodo.18981936

---------------------------------------------------
Earth science organizational metadata profiles 
---------------------------------------------------

| Organizational Metadata Profile ID | Description |
| :---:| :--- |
| AODN-IMOS | Metadata records for data from the Integrated Marine Observing System (IMOS) within the Australian Ocean Data Network (AODN) catalog are ISO 19115 compliant metadata ((https://imos.org.au/data/access-ocean-data/metadata-catalogues). It is currently based on ISO 19115-3.|
| DataOne | The DataONE federation is a federated network that connects many Earth and environmental data repositories into a single discovery and access system  (https://www.dataone.org/). It currently operates the 10 DataONE hosted repositories with additional 65 DataONE member repositories. It supports variety of community and discipline-specific metadata standards. | 
| DOE-KBase | The U.S. Department of Energy’s (DOE) Systems Biology Knowledgebase (KBase, www.kbase.us) is an open, collaborative platform that enables researchers, educators, and students to integrate, analyze, and publish biological data across scales – from molecules to ecosystems. KBase Credit Metadata Schema (https://doi.org/10.25982/1984203) was designed to be interoperable with DataCite schema  |
