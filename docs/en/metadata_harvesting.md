# Metadata harvesting

<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="10-scope-purpose">1.0 Scope & Purpose</h2>

        <div class="mb-3">
            This policy governs the metadata harvesting protocols and activities associated with the search and discovery of third-party data repositories for the Federated Research Data Repository (FRDR) website (the Site), <a href="https://www.frdr-dfdr.ca/">https://www.frdr-dfdr.ca/</a>, and the services available on or at the Site (taken together, the Service). This policy should be consulted in accordance with the <a href="/policies/en/terms_of_use/">Terms of Use</a>, <a href="/policies/en/privacy/">Privacy Policy</a>, the <a href="/policies/en/glossary/">Glossary of Terms</a>, and any other relevant policies.
        </div>
    </div>
</div>



<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="20-background">2.0 Background</h2>

        <div class="mb-3">
            In addition to providing repository services, the Service is designed to index other research data repositories in Canada. These generally fall into three categories: data repositories hosted at Canadian universities which serve as a deposit point for researchers working at those institutions, government data portals, and domain-specific repositories hosted at larger or independent research centres which are known to researchers working in a given domain or subject area.
        </div>
    </div>
</div>

<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="30-repository-metadata-harvesting">3.0 Repository Metadata Harvesting</h2>

        <div class="mb-3">
            The Service will harvest publicly available metadata distributed across multiple Canadian platforms and repositories. Only Canadian data repositories, that is, repositories owned and operated by a Canadian institution or organization, will be selected for harvesting. Exceptions may be made for data repositories that facilitate querying data by country of origin.
        </div>
        <div class="mb-3">
            The Service will not transfer or ingest any research data from harvested repositories. If the data are openly available, Users will be able to access them from the source repository. If no license is explicitly given, Users are encouraged to contact the repository to confirm license or terms of use. The Service will endeavour to work with harvested repositories to ensure that dataset licensing terms are clearly indicated.
        </div>
    </div>
</div>

<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="40-criteria-for-harvesting">4.0 Criteria for Harvesting</h2>

        <div class="mb-3">
            The Service will endeavour to index new repositories for search and discovery as they are identified. Repositories will be prioritized for indexing based on the following criteria:
        </div>

        <ul>
             <li>Support for one of the metadata API formats implemented in the FRDR harvester. Currently, this is OAI-PMH , CKAN, CSW,  MarkLogic, OpenDataSoft, Socrata, and certain repositories with Google Sitemaps. Support for additional formats may be added in the future.</li>
             <li>If a repository holds more than just research data -- for example, some university institutional repositories also hold theses and pre-print articles -- it should have a means of querying for only research data.</li>
             <li>A plausible workflow for plaintext/keyword search and retrieval of datasets from the repository.</li>
             <li>The existence of a reliable point of contact at the host institution for resolving technical and/or metadata issues.</li>
        </ul>
    </div>
</div>

<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="50-use-of-harvested-metadata">5.0 Use of Harvested Metadata</h2>

        <div class="mb-3">
            Metadata from the Service will be available through the FRDR Discovery Service search platform (<a href="https://www.frdr-dfdr.ca/repo/">https://www.frdr-dfdr.ca/repo/</a>), the map-based, Geodisy search platform (<a href="https://geo.frdr-dfdr.ca/">https://geo.frdr-dfdr.ca/</a>), and exposed via an API (such as an OAI-PMH endpoint). Metadata from the Service may be under the CC0 license, which allows for free reuse. Users are responsible for confirming the licensing terms of the Metadata in the source repository prior to reusing the Metadata.
        </div>
        <div class="mb-3">
            Should a User identify content erroneously indexed by the Service, the User should notify the Service by contacting <a href="mailto:support@frdr-dfdr.ca">support@frdr-dfdr.ca</a>.
        </div>
    </div>
</div>

<div class="card-shadow mb-3">
    <div class="card-body">
        <h2 id="60-implementation-and-revision">6.0 Implementation and Revision</h2>

        <div class="mb-3">
            Policy enters into force on the date of its adoption. It will be reviewed every two years or at any time, as required.
        </div>
    </div>
</div>

Last Revised: 2023-11-28
