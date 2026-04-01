# Data Governance

*Last update: March 2026*

> *This is part of the [ZAPP Governance Documents](GOVERNANCE.md).*

This document describes the policies governing data available in the ZAPP Atlas, including images and their associated annotations. Data are submitted by contributors via the Submission Platform (see [Contribution Guidelines](CONTRIBUTING.md) for how to contribute data).

## 1. Commitment to FAIR Principles

ZAPP is committed to ensuring that all data in the Atlas are **Findable, Accessible, Interoperable, and Reusable (FAIR)**.

To meet these principles, all data must:

- Follow the agreed-upon data model and applicable standards
- Include clear and traceable provenance information
- Be openly available under the specified license (CC BY 4.0 — see [Licensing](#7-licensing) below and [IP & Licensing](IP_AND_LICENSING.md))
- Be structured to support interoperability and reuse

## 2. Data Acceptance

Data are accepted into the Atlas provided they:

- Conform to required standards and data models
- Pass all quality control (QC) checks

The Submission Platform is designed to facilitate compliance with these requirements. Data are made publicly available only after passing QC and being explicitly published by the data submitter.

## 3. Data Publication Control

Data submitters retain control over publication status. Submitters may:

- **Publish data to the Atlas:** Data becomes publicly available.
- **Delay publication:** Data remains private and accessible only to the submitter (e.g., pending annotation completion or manuscript publication). Data may be edited during this period.
- **Edit published data:** Edited data are temporarily removed from public view until re-published.
- **Retract data:** Data are removed from public view.

The Principal Investigator (PI) or designated laboratory manager associated with the submitted data may assume publication control when appropriate. In such cases, a request must be submitted to ZAPP maintainers via GitHub (process to be finalized).

## 4. Data Review

Community review provides feedback on the accuracy and appropriateness of the association between a phenotype and its visual representation.

**Purpose of review:**

- Assess whether the image appropriately represents the annotated phenotype(s)
- Provide constructive scientific feedback

**Process**

The review workflow is under development. It is expected to include:

- A structured approval/disapproval mechanism (e.g., thumbs up/down)
- Optional comment fields

**Use of review feedback**

Data submitters determine whether and how to respond to review feedback.

**Attribution**

Review activity will be attributed to contributors. Reviewers may choose to remain anonymous publicly.

## 5. Data Provenance

All submitted data include explicit provenance information visible on each Phenotype Atlas record.

Provenance includes:

- **Data submitter**, identified via ORCID
- **Laboratory of origin**, identified via ZFIN Lab identifier (ZDB-LAB-####-#)
- **Associated publication reference**, when available (PMID, DOI, or internal link)

Each laboratory is responsible for maintaining its registration in ZFIN. Individual laboratories determine whether the listed submitter is the original data creator or a designated representative.

## 6. Data Access and API Policies

ZAPP data are openly accessible through:

- The Atlas web interface (search, browse, and visualization)
- Bulk data downloads
- Public APIs

Access mechanisms are documented on the ZAPP website. API usage policies, rate limits, and technical specifications are provided in the API documentation.

## 7. Versioning Policy

ZAPP is developed incrementally and released under numbered versions.

Each release includes:

- Newly published submissions
- Approved edits
- Reviewed and validated updates

Release notes describe changes included in each version.

Users are encouraged to use the most recent release. Previous releases remain accessible when feasible, with reasonable backward compatibility.

## 8. Licensing

All data in the Atlas are distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

This license permits sharing and reuse of data provided appropriate attribution is given to the original creators and ZAPP.

For the full licensing policy covering all ZAPP resources (data, code, ontologies), see [IP & Licensing](IP_AND_LICENSING.md).

## 9. Citation Policy

**Citing the ZAPP Atlas as a Resource**

When referencing ZAPP as a database, infrastructure, or data resource (e.g., in Methods sections, as a search resource, or for bulk data download), cite:

> [Insert official ZAPP citation here]

**Citing a Specific Atlas Entry**

When referencing a specific image or record, cite:

- The individual entry (via provided citation tool)
- The data submitter and laboratory (as indicated on the record)
- The associated publication, if applicable

The Atlas provides a "Cite this entry" tool to generate the correct citation format.

For the full citation and publication policy, see [IP & Licensing](IP_AND_LICENSING.md).
