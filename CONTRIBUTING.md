<!--@@joggrdoc@@-->
<!-- @joggr:version(v1):end -->
<!-- @joggr:warning:start -->
<!-- 
  _   _   _    __        __     _      ____    _   _   ___   _   _    ____     _   _   _ 
 | | | | | |   \ \      / /    / \    |  _ \  | \ | | |_ _| | \ | |  / ___|   | | | | | |
 | | | | | |    \ \ /\ / /    / _ \   | |_) | |  \| |  | |  |  \| | | |  _    | | | | | |
 |_| |_| |_|     \ V  V /    / ___ \  |  _ <  | |\  |  | |  | |\  | | |_| |   |_| |_| |_|
 (_) (_) (_)      \_/\_/    /_/   \_\ |_| \_\ |_| \_| |___| |_| \_|  \____|   (_) (_) (_)
                                                              
This document is managed by Joggr. Editing this document could break Joggr's core features, i.e. our 
ability to auto-maintain this document. Please use the Joggr editor to edit this document 
(link at bottom of the page).
-->
<!-- @joggr:warning:end -->
# Contributing to this projects

A big welcome and thank you for considering contributing to this! 

Reading and following these guidelines will help us make the contribution process easy and effective for everyone involved. It also communicates that you agree to respect the time of the developers managing and developing these open source projects. In return, we will reciprocate that respect by addressing your issue, assessing changes, and helping you finalize your pull requests.

## Quicklinks

* [Code of Conduct](#code-of-conduct)
* [Getting Started](#getting-started)
    * [Issues](#issues)
    * [Pull Requests](#pull-requests)

## Code of Conduct

We take our open source community seriously and hold ourselves and other contributors to high standards of communication. By participating and contributing to this project, you agree to uphold our [Code of Conduct](/CODE-OF-CONDUCT.md).

## Getting Started

Contributions are made to this repo via Issues and Pull Requests (PRs). A few general guidelines that cover both:

- To report security vulnerabilities, please email [security@bluenova.io](mailto:security@bluenova.io).
- Search for existing Issues and PRs before creating your own.
- We work hard to makes sure issues are handled in a timely manner but, depending on the impact, it could take a while to investigate the root cause. A friendly ping in the comment thread to the submitter or a contributor can help draw attention if your issue is blocking.

### Issues

Issues should be used to report problems with the library, request a new feature, or to discuss potential changes before a PR is created. When you create a new Issue, a template will be loaded that will guide you through collecting and providing the information we need to investigate.

If you find an Issue that addresses the problem you're having, please add your own reproduction information to the existing issue rather than creating a new one. Adding a [reaction](https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/) can also help be indicating to our maintainers that a particular problem is affecting more than just the reporter.

### Pull Requests

PRs to our libraries are always welcome and can be a quick way to get your fix or improvement slated for the next release. In general, PRs should:

- Only fix/add the functionality in question **OR** address wide-spread whitespace/style issues, not both.
- Add unit or integration tests for fixed or changed functionality (if a test suite already exists).
- Address a single concern in the least number of changed lines as possible.
- Include documentation in the repo or on our [docs site](https://docs.bluenova.io).
- Be accompanied by a complete Pull Request template (loaded automatically when a PR is created).

For changes that address core functionality or would require breaking changes (e.g. a major release), it's best to open an Issue to discuss your proposal first. This is not required but can save time creating and reviewing changes.

In general, we follow the ["fork-and-pull" Git workflow](https://github.com/susam/gitpr)

1. Fork the repository to your own Github account
2. Clone the project to your machine
3. Create a branch locally with a succinct but descriptive name
4. Commit changes to the branch
5. Following any formatting and testing guidelines specific to this repo
6. Push changes to your fork
7. Open a PR in our repository and follow the PR template so that we can efficiently review the changes.

<!-- @joggr:editLink(b3f7b3d8-5bec-435a-b56c-e7c6669d67a9):start -->
---
<a href="https://app.joggr.io/app/documents/b3f7b3d8-5bec-435a-b56c-e7c6669d67a9/edit" alt="Edit on Joggr">
  <img src="https://img.shields.io/static/v1?label=&message=Edit%20doc%20on%20Joggr&style=for-the-badge&color=349ACA&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAQOSURBVHgBtVdNTBNBFH67UBQK0vIPwUhBDngAjB4EE4GInssd4lHwIgl6Bs7EBC7CEQNn4Y5G8SAXE4EDHlCpP+GnAi0pYKQWfN90p0zbbbst+CVNd2ffzvfmve+9mdXIItbW1hwFBQVuTdPa+Nd8cnJSw8MO47Gfxzw8tsi/+UAgMOtyufxW5tVSGWxsbNTYbLZ+JnigEFrB5NHR0XBlZaWHMnEAK2YMHh8f99PZMKrr+rDT6fRbdgCrzsnJecOXNXQ+8HA0OsyiEeeA1+ttzsrKmkmH/Iv/Dw0vbNHWYZDuXSmgvqYSstv0OCdCoVBXWVnZojoYZYWVp0sOSHJg7luAXq7umZmJucFh6gBynknY94PHEXIJb8y96gQ4fD6fI84BCI4yyHk+h7qxNDdqLPY+1gkW9qC8ERowRLdGFjDzeY/erx8Ikp4GpxjbOvxLszy+eRCk1iq70IFqj+ewVXXBonRBlNm44TofskK+wMQTS9vievnXb/rK4ntys4zK87LpYWNxnP30Jx9NreyK64rcbHLXF0aeobfwX7+GfHBIfKnIsYq+Vz/ogHOuAuQjd6qo3G6LGsfKpbPA87vVVOe4oJr4uT+4dC4NN1kgfzq/HiG/zyEuz7OdPnu3LkpRQo0U0MfRiSEHHMFg0I2ktFMSgBTkUunI8QCHfaStKsqJR69/Ch3geuSDN/J+N+feXW/ewbks27Td3d2PvIE0J3JgYnmHZlbDXRThHu+8HBETSvAZk0GUEngmI9V1tZB6uSklwaJu7GqmwMQqOXKtKhklONhSEakGQJI3cZWkIAdqUAUJd7h8g8xuEEmhTbG6QdRVd0mMdV8rErbjHC3p7MCNUrIAh7azs3OSzAI5xeRy5WppxVYAbFGe0InJXmAKOIAStLTPq+QScA69oIVJM4Bfx0nGiiVKSyWvLQyXFYQ4tLAp0pIBPDo3oaVUVmalNd5ZzSo/Ddw0Oyc1kAYWkai3lIJcbUIorR4WHdDbVBxVAbNcMVMr1iOB86POzWCWrxMeIBF22YTQzWJLCxUgGxKgpTxlngLcOs5q7MmLREaIAADFD94qN7XZD4YiNoiQRUyCW/jLGxL26KjtGL197vs+tVbmCScaSy7GbThIC8quliMz5wnwNpwfZ5MI2IjYgfB2jIvt7e0xrojH0gAtGJMfHIVE7zcD1A+b7oYi1oWTrIIjPgZO4Ygc5HwM8Z9H3t/mlSPnrUnqGzZAhT2b0oDH4BKIkoyRivM8jseRc+g75OqBqH6JBzg6kxKJcybvUskB06L5D5GIW7mE6Y4BQ37hOsRCZwTmwFxm5EDKtoFocFqGjI9TqxC9hcU2mojYsgOKIw7j/NjOzjRROD2Rz3MK60Z8nqPDJfoYjcU/YCD1KmTczqkAAAAASUVORK5CYII=" />
</a>
<!-- @joggr:editLink(b3f7b3d8-5bec-435a-b56c-e7c6669d67a9):end -->