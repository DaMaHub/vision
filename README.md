## Vision 

Momentum is growing among research funding agencies, data preservation advocates, and individual researchers to increase the extent to which the scientific process and record is fully reproducible and transparent. In the context of data, this is most commonly referred to as making research data (and code, models, etc). findable, accessible, interoperable and re-usable/reproducible (FAIR).

Distributed web technologies are well suited to meeting some of the challenges of creating a network infrastructure which natively facilitates FAIR data. Unlike existing approaches, where data is “published” long after the research has been carried out, technologies like InterPlanetary File System (IPFS)[1] and DAT [2] fit into the researcher's daily workflow throughout the research lifecycle, much as git fits into a software developer's daily flow throughout a given project lifecycle. However, for example, while IPFS natively simplifies the “A” (accessible) aspect of FAIR, there are gaps in terms of how it currently addresses the findability and interoperability of data.

## Project Outline


In general, we subscribe to adopting a modular approach, breaking the problem of FAIR data management down into discrete issues and solutions. This simplifies matters from a technological point of view, but also from the point of view of getting adoption within the existing research landscape.

Our group is actively working on use-cases that bridge the gap between IPFS (and other distributed technologies, e.g. ledgers and smart contracts) and existing scholarly communication infrastructures, from data repositories and linked data to DOIs [12] and ORCIDs [13].


Broadly speaking, our group will work on progressing matters on three fronts:


* Firstly we will develop use-cases and prototypes [4,5,11] which combine emerging technologies (IPFS, blockchain, DAT, distributed identity) with existing research infrastructure, working towards making research data more FAIR and making research infrastructures simpler, more efficient, and more inherently transparent and trustless.


* A parallel strand of development will address the operationalisation of how these technologies might be funded, incentivised, and governed at scale. Again, this strand will combine new concepts and technologies around consensus based incentivisation, mapping token-based technologies to the reputational economy which drive research. However, it will also consider how traditional approaches to funding public good infrastructures can be brought to bear in the short-to-medium term. We believe there is considerable potential in re-allocated the existing, centralised public-good funding that goes into research data management infrastructures, more efficiently leveraging the inherent characteristics of IPFS and related systems.   


* A final strand will consider the issue of gaining adoption of distributed web technologies and concepts within the scholarly communications ecosystem, building upon and modifying that ecosystem by seeking to complement it rather than trying to replace it in one fell swoop. Our group is already actively engaged in relevant stakeholder groups such as the Research Data Alliance (RDA), engaging with relevant projects such as ResearchObjects and DataCite, and are working towards participation in the European Open Science Cloud initiative [7].


## Some core components to be explored further are:


* Elaborating and documenting the implications of immutable content addressed references and collaborative storage for the preservation the global scholarly record (the “A”, accessiblility, of FAIR). Through a collaborative network of trusted nodes (libraries, research centres, infrastructure providers), we will investigate open and permanent access to fundamental primary research data and analysis. This needs to take into account the relationship between IPFS hashes and earlier technologies like DOI, as well as developing use-cases around robust collaborative pinning of IPFS hashes.

* Elaborating and documenting the data model and related technologies needed to add semantic interoperability to content stored on IPFS (the “I”, interoperability, of FAIR data).  We are working with existing portable, self-describing data packaging initiatives to agree a set of supported wrapper formats which address different levels of semantic interoperability, e.g. “discoverability metadata” for the package as a whole roughly equivalent to DataCite Schema (e.g. DataPackages/DataCate/ResearchObjects) ; detailed file-level annotations (e.g. DataPackages/DataCrate/ResearchObjects); data-element level annotations/metadata (e.g. ResearchObjects/TabularDataPackages) [6]. This will involve taking into account where IPLD fits with these existing packing formats and also with earlier work on network-level semantic interoperability, i.e. the W3C Linked Data and RDF approach.

* Elaborating and documenting use cases of how the semantics encoded in content-addressed data packages can be indexed and exposed for querying and discovery (the “F”, findability of FAIR)

* The role of distributed ledgers to record an independent, immutable log of interactions with the IPFS cluster [10] described above. This allows contributions to be attributable and to trace the impact of individual contributions directly to the hub without the need for a third party trusted intermediary [4].

* The potential and challenges associated with using smart contracts between scientists to introduce a simplified way of governance of the research cycle. Smart contracts have the potential to lay out the terms of such collaboration, to incentivize contributions to projects and may become a new means of funding research through a tokenized science economy. The protocol would allow any collaborative research cycle application to be implemented on top of e.g. SciDapp [5] etc.

## Next

* [April 21st–22nd, 2018  The British Library] -- [**Decentralised Data Infrastructure for Science**](https://ti.to/damahub/decentralised-data-infrastructure-for-science) - two days of talks, discussions and workshops. [12]

## Contact

Email: damahub@pm.me

--------

[1] https://ipfs.io

[2] https://datproject.org

[3] https://github.com/scholarc/infrastructure

[4] https://github.com/DaMaHub/v0.01

[5] https://github.com/SciDappSDG/futurehack/wiki/

[6] https://futurehack.io

[7] https://rd-alliance.org/approaches-research-data-packaging-rda-11th-plenary-bof-meeting

[8] Data Packaging Formats https://docs.google.com/document/d/155lA2BcixTl-zwJHGfLkxsmg7WmQbBK00QWyP8QggkE/edit

[10] https://github.com/DaMaHub/ipfs-cluster-demo

[11] ChemChain [slides] https://docs.google.com/presentation/d/1TW_nmoVxNd4T8ZybNFS-jloMNCFXOmAB4TMV66vzj9Y/edit?usp=sharing

[12] https://www.doi.org

[13] https://orcid.org

[14] https://ti.to/damahub/decentralised-data-infrastructure-for-science
