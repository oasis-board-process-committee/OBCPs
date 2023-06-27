![OASIS](../OASIS-Logo.png)
---

# OASIS Best Current Practices Document

## Using Git

### Version: 2023.01

### Abstract:

This document defines guidelines for using git to collaborate on documents in an OASIS Technical Committee or Open Project.

### Key words:

The key words "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**", "**SHOULD**", "**SHOULD NOT**", "**RECOMMENDED**", "**NOT RECOMMENDED**", "**MAY**", and "**OPTIONAL**" in this document are to be interpreted as described in BCP 14 [RFC2119] [RFC8174] when, and only when, they appear in all capitals, as shown here.

### Notices:

Copyright © OASIS Open 2023. All Rights Reserved. This document is published under the Creative Commons Attribution 4.0 International Public License (CC BY 4.0).

---

# 1 Introduction

This OASIS Best Current Practices documents (OBCP) document provides guidelines for when to use the git protocol and repositories (e.g. GitHub) to collaobrate on documents in an OASIS Technical Committee (TC) or Open Project (OP) board or committee, how to create a repository, how to contribute to a repository, and how to administer a repository.


# 2 When to use git

The git protocol and repositories (e.g. GitHub) are designed for distributed versioning of source code but they are also useful for the publication and version control of other documents.  Regardless, the git protocol and repositories may not enforce features critical to open specifications, including persistence and compliance with the [OASIS] [IPR Guidelines] and specific license requirements of the [Committee]. Therefore, according to the [Open Repository] policy, while an [OASIS] [Committee] **MAY** choose to create one or more repositoroes to suport document collaboation, a [Work Product] published on these repositories **MUST NOT** be considered the authoritative version of the [Work Product].

[OASIS]: https://oasis-open.org

[IPR Guidelines]: https://www.oasis-open.org/policies-guidelines/ipr/
Can this be used as the official publication process or can it contain an authoritative version?

[Committee]: https://www.oasis-open.org/policies-guidelines/oasis-committee-operations-process/#committees

[Work Product]: https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2018-05-22/#dWorkProduct

[Open Repository]: https://www.oasis-open.org/policies-guidelines/open-repositories/#independentResources

# 3 Create a git repository

Each [Repository] is created by a specific [Committee]. 

When creating a [Repository], it is important to consider creating an organization, defining a purpose, choosing a license and choosing maintainers.

# 3.1 Consider joining an Organization

Some [Repository] hosts (e.g. [GitHub]) support shared accounts enabling [Organizations] to collaborate across multiple related [Repositories]. Personal accounts can be invited to either join [Organizations] as a member or owner.  [Organizations] enable consolidated management of permissions and features across multiple [Repositories].  Some hosts also allow [Repositories] and [Organizations] to provide a website. (e.g., [Pages])

# 3.2 Defining a purpose

Each [Repository] **SHOULD** have a [Purpose Statement] defining the intended scope and contents of the [Repository] approved by the [Committee] that created the [Repository].  

# 3.3 Choosing a license

Each [Repository] **MUST** have a one or more [Licenses] approved the [Committe] that created the [Repository].

# 3.4 Choosing maintainers

Each [Repository] **MUST** have one or more [Maintainers] desginated by the [Committee] to have administrative-level privileges and organize the content of the [Repository].

The list of [Maintainers] **SHOULD** include the [Chairs] and any Secretaries of the [Committee] that created the [Repository], if they exist, as well as at least two staff members of [OASIS].

Document Editors **MUST** and other [Contributors] **MAY** have privileges to edit specific documents stored in a [Repository] without necessarily needing to be [Maintainers].

[Maintainers]: https://www.oasis-open.org/maintainers-guide/

[Repository]: https://www.oasis-open.org/open-repositories/#repositoryDefinition

[GitHub]: https://github.com/

[Organizations]: https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations

[Pages]: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages

[Licenses]: https://www.oasis-open.org/licenses/

[Contributors]: https://www.oasis-open.org/policies-guidelines/ipr/#def-contributor

[Chairs]: https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2018-05-22/#dChair

# 4 Contributing to a git repository

Before contributing a repository, it is important to first complete Contributor License Agreements (CLAs) and be familiar with submitting pull requests and reporting/tracking issues.

## 4.1 Contributor License Agreements (CLAs)
Per the [RepoGuidelines], all [Contributors] to a [Repository] **MUST** complete and sign a Contributor License Agreement ([CLA]) before submitting a contribution.

To ensure compliance, [OASIS] provides various [License Tools] to the [Committees].

## 4.2 Submitting Pull Requests
Each contribution to a [Repository] **SHOULD BE** submitted as a [Github] [Pull Request].

Each [Pull Request] **SHOULD** include a succint comment describing the scope of the contributed changes.

Each [Pull Request] **SHOULD** be accepted into the [Repository] by one of the [Maintainers] other than the [Contributors].

## 4.3 Reporting/Tracking issues
[GitHub] provides an [Issues] feature which is useful for reporting and tracking features and bugs.

[Maintainers] **MAY** define [Labels] that [Contributors] **MAY** use to categorize issues.

## 4.4 Participating in Discussions
[GitHub] also provides a [Discussions] feature which is useful for threaded conversations including questions and answers.

[CLA]: https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2018-05-22/#dCLA

[License Tools]: https://www.oasis-open.org/policies-guidelines/open-repositories/#licenseTools

[Pull Request]: https://docs.github.com/en/pull-requests

[Issues]: https://github.com/features/issues

[Labels]: https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels

[Discussions]: https://docs.github.com/en/discussions

# 5 Collaborating on documents
When using a [Repository] to collaborate on documents, it is important to consider document formats, document automation, and synchronization with other repositories.

## 5.1 Document formats
https://datatracker.ietf.org/doc/html/rfc8874#name-document-formats
Should we recommend Markdown or AsciiDocs?
Github-Flavored Markdown

## 5.2 Document automation
How could this fit into an automated publication process?

## 5.3 Synchronizing with other repositories
What about phases of use?
- Like doing your work outside in say Google Docs and then copying it in every so often
- Doing your work natively or day-2-day
- or something in between


# 6 Administering a git repository

Administering a repository includes organizing content and enforcing with document retention requirements.

## 6.1 Organizing content
How to use we tagging and branching?
Should you use Branching or Directories?

## 6.2 Enforcing Document retention
When can content or repos be deleted or archived? What are the rules around that?

---

# Appendix A. References

This appendix contains the normative and informative references that are used in this document. Normative references are specific (identified by date of publication and/or edition number or version number) and Informative references are either specific or non-specific. For specific references, only the cited version applies. For non-specific references, the latest version of the reference document (including any amendments) applies. While any hyperlinks included in this appendix were valid at the time of publication, OASIS cannot guarantee their long term validity.

## A.1 Normative References

The following documents are referenced in such a way that some or all of their content constitutes requirements of this document.

**[RFC2119]**

Key Words for Use in RFCs to Indicate Requirement Levels, BCP 14, RFC 2119, March 1997. [Online]. Available: https://www.rfc-editor.org/info/rfc2119

**[RFC8174]**

Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words, BCP 14, RFC 8174, May 2017. [Online]. Available: https://www.rfc-editor.org/info/rfc8174

**[DefinedTerms]**

OASIS Defined Terms, 22 July 2020, [Online]. Available: https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2018-05-22/

**[CommitteeProcess]**

OASIS Committee Operations Process, 14 June 2022, [Online]. Available: https://www.oasis-open.org/policies-guidelines/oasis-committee-operations-process/

**[TCProcess]**

OASIS Technical Committee (TC) Process, 22 July 2020. [Online]. Available: https://www.oasis-open.org/policies-guidelines/tc-process-2017-05-26/

**[RepoGuidelines]**

Open Repository Guidelines and Procedures, July 2022. [Online]. Available: https://www.oasis-open.org/policies-guidelines/open-repositories/

## A.2 Informative References

The following referenced documents are not required for the application of this document but may assist the reader with regard to a particular subject area.

**[RFC8874]**

Working Group GitHub Usage Guidelines, August 2020. [Online]. Available: https://datatracker.ietf.org/doc/html/rfc8874

---

# Appendix B. Revision History

| Revision | Date       | Changes Made     |
|----------|------------|------------------|
| 01       | 2023-06-24 | Outline          |

---
