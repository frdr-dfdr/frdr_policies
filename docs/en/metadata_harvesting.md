
## 1.0	Scope & Purpose

This policy governs the metadata harvesting protocols and activities associated with the search and discovery of third-party data repositories for the Federated Research Data Repository (FRDR) website (the Site), <a href="https://www.frdr-dfdr.ca/">https://www.frdr-dfdr.ca/</a>, and the services available on or at the Site (taken together, the Service). This policy should be consulted in accordance with the [Terms of Use](/policies/en/terms_of_use/), [Privacy Policy](/policies/en/privacy/), the [Glossary of Terms](/policies/en/glossary/), and any other relevant policies.

## 2.0	Background

In addition to providing repository services, the Service is designed to index other research data repositories in Canada. These generally fall into three categories: data repositories hosted at Canadian universities which serve as a deposit point for researchers working at those institutions, government data portals, and domain-specific repositories hosted at larger or independent research centres which are known to researchers working in a given domain or subject area.

## 3.0	Repository Metadata Harvesting

The Service will harvest publicly available metadata distributed across multiple Canadian platforms and repositories. Only Canadian data repositories, that is, repositories owned and operated by a Canadian institution or organization, will be selected for harvesting. Exceptions may be made for data repositories that facilitate querying data by country of origin.

The Service will not transfer or ingest any research data from harvested repositories. If the data are openly available, Users will be able to access them from the source repository. If no license is explicitly given, Users are encouraged to contact the repository to confirm license or terms of use. The Service will endeavour to work with harvested repositories to ensure that dataset licensing terms are clearly indicated.

## 4.0	Criteria for Harvesting

The Service will endeavour to index new repositories for search and discovery as they are identified. Repositories will be prioritized for indexing based on the following criteria:

 * Support for one of the metadata API formats implemented in the FRDR harvester. Currently, this is OAI-PMH , CKAN, CSW,  MarkLogic, OpenDataSoft, Socrata, and certain repositories with Google Sitemaps. Support for additional formats may be added in the future.
 * If a repository holds more than just research data -- for example, some university institutional repositories also hold theses and pre-print articles -- it should have a means of querying for only research data.
 * A plausible workflow for plaintext/keyword search and retrieval of datasets from the repository.
 * The existence of a reliable point of contact at the host institution for resolving technical and/or metadata issues.

## 5.0 Use of Harvested Metadata

Metadata from the Service will be available through the FRDR Discovery Service search platform (<a href="https://www.frdr-dfdr.ca/repo/">https://www.frdr-dfdr.ca/repo/</a>), the map-based, Geodisy search platform (<a href="https://geo.frdr-dfdr.ca/">https://geo.frdr-dfdr.ca/</a>), and exposed via an API (such as an OAI-PMH endpoint). Metadata from the Service may be under the CC0 license, which allows for free reuse. Users are responsible for confirming the licensing terms of the Metadata in the source repository prior to reusing the Metadata.

Should a User identify content erroneously indexed by the Service, the User should notify the Service by contacting [support@frdr-dfdr.ca](mailto:support@frdr-dfdr.ca). 

## 6.0 Implementation and Revision

Policy enters into force on the date of its adoption. It will be reviewed every two years or at any time, as required.

Last Revised: 2023-11-28
