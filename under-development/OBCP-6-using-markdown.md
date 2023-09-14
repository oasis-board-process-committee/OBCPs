![OASIS](../OASIS-Logo.png)

---

# OASIS Best Current Practices Document

## Using Markdown at OASIS

### Version: 2023.07

### Abstract:

This document contains information about the Markdown markup language and how it
can be used for work products at OASIS.

### Notices:

Copyright © OASIS Open 2023. All Rights Reserved. This document is published
under the Creative Commons Attribution 4.0 International Public License (CC BY
4.0).

---

# 1 Introduction

This document contains information about the Markdown markup language and how it
can be used for work products at OASIS.

## 1.2 What is Markdown?

Markdown is a lightweight plaintext markup language that has a very simple and
easy to understand syntax. Documents written in Markdown format can easily be
read with or without a tool that can render it. This is often not possible with
other markup languages like HTML.

## 1.3 Markdown Formatting Limitations

While the formatting options in Markdown are limited, the core set supports the
basic formatting needs for organizing and rapidly developing documents. Some
concepts like the coloring of text or advanced table options are not supported
by Markdown.

## 1.4 Flavors of Markdown

There are currently several versions or flavors of the Markdown syntax, some of
these versions support additional markup features that enable additional
formatting options. However, these versions are not supported and rendered by
all tools. It is therefore recommended that groups at OASIS adopt the Markdown
syntax supported by Github as it is the most widely used and supported
version.

## 1.5 Why Markdown?

Markdown enables rapid development and formatting in any editor or word
processor (even Word or Google Docs). The output is always stored in plaintext
and can be viewed or rendered in many different tools. This also means that
documents written in Markdown can at any point be checked into a source control
system like Github.

Using Markdown may also limit the need for groups at OASIS to produce multiple
versions for publication. Currently groups will often produce a Word version,
an HTML version, and a PDF version of their documents. If a group uses Markdown
they would be able to produce just the Markdown version and possibly a PDF
version.

# 2 Using Markdown

Groups at OASIS may write their documents in Markdown via any tool or process
that they like. Some may use native Markdown tools or text editors, some may
use Google Docs, and others may choose to use GitHub natively as if the
document was source code. Using an external text editor or Google docs does not
prevent groups from also using GitHub.

For example, a group may write their specification in Markdown format using
Google Docs to simplify the comment and suggestion process. Then at some
defined interval or at the end of the document creation process, the plaintext
markdown can be pushed to Github. If groups do choose to use Markdown with an
external editor, but want to make use of GitHub’s change tracking and
redlining (blame) capabilities it is advised that they routinely copy the
current version into GitHub, this could be done on a weekly or monthly basis
depending on how much the document changes.

## 2.1 Issues With Using Markdown in GitHub

GitHub was designed for source code tracking and not document writing. As such,
just as in comments in source code, simple and tiny changes in a sentence can
reflect that the entire paragraph has changed, so reviewers of Pull Requests
should be mindful of this.

When using GitHub natively to work on documents in Markdown, then groups should
consider tiny commits and pull requests which is often not the norm for source
code. Becuase unlike in Google Docs or other tools, a pull request that
contains changes throughout the document prevents editors from accepting part
but not all of the pull request. 

This also means that during a high level of document change and churn, native
GitHub may not be the best choice. 

# 3 Markdown Syntax

The following resources should help groups understand the Markdown syntax.

- [https://www.markdownguide.org/getting-started/](Getting Started)
- [https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax](Basic Syntax)
- [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](Markdown Cheatsheet)
- [https://github.github.com/gfm/](GitHub Markdown Specification)

# 4 OASIS Template Considerations

 - There should be a single blank line before and after headings and formatting blocks
 - Please see the OASIS Markdown Template for ideas and suggestions
  
# 5 Online Markdown Tools

 - https://stackedit.io/

---

# Appendix A. References

This appendix contains the normative and informative references that are used in
this document. Normative references are specific (identified by date of
publication and/or edition number or version number) and Informative references
are either specific or non-specific. For specific references, only the cited
version applies. For non-specific references, the latest version of the
reference document (including any amendments) applies. While any hyperlinks
included in this appendix were valid at the time of publication, OASIS cannot
guarantee their long term validity.

## A.1 Normative References

The following documents are referenced in such a way that some or all of their
content constitutes requirements of this document.

NONE

## A.2 Informative References

The following referenced documents are not required for the application of this document but may assist the reader with regard to a particular subject area.

NONE

---

# Appendix B. Revision History

| Revision | Date       | Changes Made     |
|---       |---         |---               |
| 01       | 2023-07-04 | Initial Release  |

---