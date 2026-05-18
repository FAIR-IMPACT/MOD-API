# MOD-API

Metadata for Ontology Description and Publication Ontology Application Program Interface

Semantic artefacts (SA) (a broader term to include ontologies, terminologies, taxonomies, thesauri, vocabularies, metadata schemas and semantic standards) are key for the description of data and for making data FAIR. Plus, describing SAs is fundamental to make them FAIR themselves. The Metadata for Ontology Description and Publication (MOD) was developed since 2017 within an RDA working group and adopted by FAIR-IMPACT to provide the vocabulary required to semantically describe Semantic Artefacts [https://github.com/FAIR-IMPACT/MOD](https://github.com/FAIR-IMPACT/MOD). It was designed as an extension of the Data Catalogue Vocabulary (DCAT), the W3C Recommendation to describe datasets and resources that can be catalogued.

This Application Programming Interface (API) has been developed to promote interoperability of Semantic Artefact Catalogues in the European Open Science Cloud (EOSC) ecosystem and beyond. This API is formalised by means of a [Swagger template](mod_api/static/mod_api/openapi.yaml) that shall guide for the implementation of Web REST API. The objects returned by an implementation of the API shall all be standard semantic objects either from a W3C Recommendation (RDFS, OWL and SKOS) or MOD.  We are expecting the MOD-API for Semantic Artefact Catalogues will enable interoperability and unified access to their content, enabling seamless querying and use by stakeholders independent of domain.


For full details of the API please refer to the [FAIR-IMPACT D4.3 Deliverable](https://zenodo.org/records/12579779).

The Swagger specification is available here: https://fair-impact.github.io/MOD-API .

Validators for MOD-API implementation:
- https://github.com/syphax-bouazzouni/mod-api-validator
- https://github.com/MaastrichtU-IDS/mod-api-conformance
