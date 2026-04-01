# Contribution Guidelines

*Last update: March 2026*

> *This is part of the [ZAPP Governance Documents](governance.md).*

Contributions are welcome throughout the ZAPP project. These contributions can take different forms, including:

- **contributions of data** (images and annotations),
- contributions to the **standards and ontologies**,
- contributions to the **code**,
- feedback, feature requests, and documentation improvement,
- participation in testing and working groups.

The level and type of contribution should reflect each contributor's comfort level and expertise. All contributions will be acknowledged and attributed. ZAPP is committed to transparency in contributions, review processes, and follow-up decisions.

All contributions to ZAPP are made on a voluntary basis; ZAPP does not provide financial compensation for contributions.

All contributors are expected to follow the [Code of Conduct](code-of-conduct.md).

## 1. Contributions to Data

### Submission of Images and Annotations

**Who can submit?**
Anyone may submit phenotypic data (images and associated annotations) to the Atlas on behalf of themselves (if they produced the data) and/or the laboratory where the data was generated.
(see also [Data Governance](data-governance.md))

**Minimum required information:**

1. An image (in any supported format)
2. Information about the fish (at minimum, whether it is wild type)
3. Information about the experiment (at minimum, the exposure)
4. The phenotype(s) represented in the image
5. Submitter identification via ORCID

**How to submit**

Data must be submitted through the Submission Platform, which formats submissions according to the ZAPP data model and standards. 
_Bulk submissions via API and spreadsheet upload will be coming soon._

**Expectations**

All submitted data must follow the [data model and standards](link). The Submission Platform is designed to make this process intuitive, including for contributors who are not standards experts.

**Attribution**

- Data submitters are recorded using their ORCID identifier via [ORCID](https://orcid.org/).
- Laboratories are recorded using their ZFIN Lab identifier via [ZFIN](https://zfin.org/).
- References may be recorded using PMID, DOI, or group internal links when available.

Each laboratory is responsible for ensuring that its lab is registered with ZFIN. Each individual submitting data is responsible for obtaining an ORCID for Submission Platform authentication (i.e. login). Individual labs may decide whether a submitter is the "data creator" or a "designated representative" (for example, a lab assistant submitting data on behalf of the group). All options listed above will be made accessible through the Submission Platform.

All attribution information is visible on individual records in the Phenotype Atlas.
(see also [Data Governance](data-governance.md))


### Data Review

All submitted data will be accepted into the Atlas provided they follow the required format and pass quality-control checks (see [Data Governance](data-governance.md) for details). Community review will provide feedback on how well a phenotype is represented visually in an image.

**Who can review?** Anyone in the research community.

**What is reviewed?** Agreement or disagreement with the phenotype represented in the image.

**How review works:** TBD (likely a thumbs-up/down system with optional comments).

**Expectations:** Reviews should be constructive and respectful. All reviewers should follow the ZAPP [Code of Conduct](code-of-conduct.md).

**Attribution:** Reviewer ORCID will be associated with aggregate review activity. Individual votes or comments will remain anonymous unless the reviewer explicitly opts in to attribution.

## 2. Contributions to Standards and Ontologies

**Who can contribute?** Anyone with a GitHub account via [GitHub](https://github.com/).

**Types of contributions:**

- Reporting errors in standards or ontology terms
- Requesting changes to existing terms
- Requesting new terms or standards
- Participating in issue discussions

**How to contribute**

All standards and ontologies are maintained in GitHub repositories to ensure transparency in requests, discussions, and decisions. The ZAPP GitHub organization is https://github.com/zappfish.

Requests should be submitted as issues in the appropriate repository. Links to issue creation are also available in the Submission Platform, Atlas, and project website.

Requests are reviewed by standards and ontology experts. Discussion may occur between requesters, community members, and maintainers directly on the issue tracker. Approved changes become available after the next release of the relevant resource.

**Expectations:**

- Requests should be as specific as possible.
- Contributors should respond to follow-up questions when needed.
- Including an ORCID is optional but encouraged.

**Attribution:** All GitHub activity is attributed to contributor GitHub handles, or ORCID when provided.

**Resources:**

- GitHub repositories:
  - Zebrafish Phenotype Ontology
  - Toxicology data model
  - ECTO
  - EXO
  - ChEBI

## 3. Giving Feedback and Suggestions

Community feedback is essential for improving ZAPP.

**Who can contribute?** Anyone.

**Examples:**

- Suggesting new features
- Reporting bugs
- Requesting documentation improvements
- Requesting tutorials
- Providing feedback on Atlas, Submission Platform, or website functionality

**How to contribute**

Feedback should be submitted as a GitHub issue in the appropriate repository. The "Contact Us" page on the project website (https://zappfish.org/) and Atlas (coming soon) will automatically create a GitHub issue.

**Expectations:** Requests are reviewed and prioritized by ZAPP maintainers. Issues affecting core functionality are prioritized over feature requests. All requests should follow the ZAPP [Code of Conduct](code-of-conduct.md).

**Attribution:** GitHub contributors are credited via their GitHub handles, or ORCID when provided. Contributors may be invited as co-authors on ZAPP community publications when appropriate.

## 4. Contributions to Testing and Working Groups

ZAPP periodically forms testing groups and working groups to address specific needs. For more information about working groups, see Project Structure and Roles in the [main Governance document](governance.md).

**Who can participate?** Anyone interested in testing features or contributing to a working group. The ZAPP team may also invite individuals based on expertise.

**Examples:**

- Testing new Atlas or submission features
- Serving on domain-specific working groups

**How participation works**

Participation methods will be defined for each effort and may include:

- Meetings and discussions
- GitHub feedback
- Structured review tasks

**Expectations:** Participants should follow instructions provided by the ZAPP team and contribute to the best of their ability.

**Attribution:** Participants will be acknowledged on a dedicated webpage and may be invited as co-authors on related publications.

## 5. Contributions to Code and Bug Fixes

**Who can contribute?** Anyone familiar with coding and GitHub workflows.

**What contributions include:**

- Bug fixes
- Feature implementation
- Improvements to ZAPP repositories

Repositories may include:

- Submission platform
- Atlas
- Frogpod
- Other ZAPP infrastructure

**How to contribute**

All code contributions must be submitted as issues and corresponding pull requests in the appropriate GitHub repository. For details on the branching model and pull request process, see [Branching and Pull Request Policy](#6-branching-and-pull-request-policy) below.

**Attribution:** Contributors are credited through GitHub pull requests and may be invited as co-authors on related publications.

## 6. Branching and Pull Request Policy

All ZAPP artifacts are maintained in public repositories hosted on GitHub.

### Branching Model

- The **`main` (or `master`) branch** represents the most current, validated, and release-ready version of the artifact (e.g., schema, Atlas, documentation).
- Direct pushes to the `main` branch are not permitted, except during formal release processes.
- All proposed changes must be developed in a separate branch and submitted via a Pull Request (PR).

### Pull Requests

- Any individual may open or comment on a Pull Request.
- Pull Requests may only be merged by authorized members of the ZAPP maintainer team.

PR authors are expected to:

- Clearly describe the proposed changes
- Document the rationale for changes
- Update relevant documentation as needed
- Identify potential impacts, including breaking changes

### Review and Discussion Process

- Proposed changes (via GitHub issues or PRs) may be discussed during regular ZAPP team meetings.
- For relevant changes, a minimum review period of **one month** will be allowed for stakeholder comments before a decision is made, unless urgent action is required.
- After the review period, the ZAPP maintainers will decide whether to merge, request revisions, or close the PR.
- Meeting discussions related to issues or PRs will be summarized and recorded as comments within the relevant GitHub thread to ensure transparency.

Any community member may:

- Propose changes via issue or PR
- Participate in discussion
- Attend relevant open meetings when appropriate

## 7. Versioning and Dependency Policy

ZAPP follows **semantic versioning** to communicate the nature and impact of changes. It is critical to alert users to any backwards-incompatible or breaking changes.

ZAPP uses a semantic versioning scheme, in which version changes are identified as "major", "minor", and "patch" updates, following the format "Major.Minor.Patch":

- **Patch** updates involve no new features, but only bug fixes.
- **Minor** updates involve new features, but no breaking changes.
- **Major** updates typically involve backwards-incompatible changes.

### Breaking Changes

Any backwards-incompatible or breaking change must:

- Be clearly identified in release notes
- Include documentation describing the impact
- Provide migration guidance when feasible

Users are encouraged to use the most recent stable release. Previous releases will remain accessible when possible to support reproducibility.
