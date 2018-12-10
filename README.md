# WP3-Standards
 Standards and interoperability issues

## Partners

Inline-style: 
![alt text](https://github.com/GeoEra-GIP/WP3-Standards/blob/master/WP3_Partners.PNG "Logo Title Text 1")


## Objectives
The main objectives of this work package will be to explore in detail the requirements and needs stemming from the other GSPs (mapped by WP2) in order to identify shortcomings in the data models. This will lead to the development of a set of data models taking into account existing standards and specific needs for extensions. In order to help the data and service producing GSPs, the task will identify the rules to evaluate whether a given dataset is conformant with the relevant data model (a “conformance class”) and develop a data and service validation system to embed in the Information Platform in the Prototyping and Development phases. The technical requirements and documents produced by this package are essential for WP 5/6/7 to develop a system able to manage different types of data and formats.

### Description of work

Task 3.1 Standardisation and interoperability analysis. (NERC, GEUS, BGR, TNO, SGU, GeoZS, CGS, BRGM, ISPRA, NGU, Geoinform, GBA, SGSS, MBFSZ, LNEG, PGI, HGI-CGS, ISOR)

The task will analyse in the Start-up phase the existing standards and Technical Guidelines (TGs) based on the common international standards: INSPIRE, ISO, IUGS CGI, OGC (GeoSciML, GWML, O&M, etc.), RDF, W3C (DCAT, semantic web best practices).
It will be based on the data requirements of each of the GSPs and will produce an overview of existing standards and provide some guidelines how to use these UMLs. A number of such data types have been identified through the “pre-defined” use cases mentioned in other GSPs (i.e. geological models).
Driven by these use cases, the task will produce a set of rules that will be transformed in WP8 as a toolkit, enabling the data providers to transform their datasets according to the appropriate standards. The main set of tools will be for the remodelling of the dataset elements from the source to the standardised target schemas.
Building on the identified international interoperability standards, this will produce the reference data structures to be used within the Information Platform (D3.1).

Task 3.2 Data model gap analysis and technical requirements. (BRGM, GEUS, BGR, TNO, SGU, GeoZS, CGS, NERC, ISPRA, NGU, GBA, SGSS, MBFSZ, LNEG, HGI-CGS, ISOR)

Based on the analysis of existing standards and models (UML) of task 3.1, this task will evaluate possible gaps and produce a roadmap for the extension of the data models and standard (D3.2.1). When a completely new view and data models and standard will be developed, the task should target technical interoperability. It will identify and describe the minimum technical requirements (functional as well as non-functional) for the development of components needed to data integration and access, serving as core functionalities for the infrastructure. Technical requirements will be calibrated in the Prototyping phase on the needs identified by the analysis of existing and missing standards, producing also a set of recommendations for other the GSPs (D3.2.2). All the requirements and recommendations will be treated in parallel by the validation (task 3.3) and WP 6 and 7, to produce validation procedures and services and to develop the technical components of Information Platform.

Task 3.3: Standards validation procedures. (ISPRA, GEUS, SGU, BRGM, NERC, SGSS) 

Based on the UML models defined in task 3.1 and on the vocabularies and ontologies identified and archived in WP4, this task will develop the Abstract Test Suites (ATS - a set of technical rules to implement in a real case the data model) that must take the sematic content into consideration.
Based on the ATS, the task will produce the schematron and the Executable Test Suite (ETS) needed to realise a Validation service for each data type provision. The documents in the Prototyping phase will provide to WP7 that should be implemented the schematron documents and the ETS transforming in a specific web services based on these information, requirements and recommendations for each.
The task will also provide in the Prototyping and Full Development phases the “Validation service specification and requirements” document some example how to perform the validation against the requirements identified in ATS.
The task will be marked by two important internal milestones, moreover all the implementation procedure description and the list schematron documents will be described in a deliverable (D.3.3).

### Deliverables

D 3.1 – Data models standards guidelines and toolkits [M9]. The document contains the analysis on the existing reference standard that can be used in the different project and that can be implemented in the Information Platform, at the same time it will provide Tool, guidelines and examples for datasets and metadata harmonisation.

D 3.2.1 – Gap analysis and path extension [M12]. The document list the gaps between the existing standards and the needs as mapped by WP2 as well as some general workflows describing how to extend the existing model to improve the knowledge.

D 3.2.2 – Technical requirements [M15]. The document contains all the technical requirements to integrate these reference data model and how to target the technical interoperability.

D 3.3 - Validation service specification and requirements [M18]. The documents contains some examples on how to perform the validation against the ATS requirements, the ATS identified for each data model that could be managed in the Information platform as identified in the previous deliverables and the basic schematron that will be implemented as service in the Information Platform.
