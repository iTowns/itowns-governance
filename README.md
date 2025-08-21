# iTowns Governance 
----

## Preamble

**iTowns** is a **geographic commons**, developed collectively by a diverse community of contributors, comprising independent developers, public organizations, research laboratories, and private companies.

The commons is governed by **rules** that guarantee its expansion and the immutability of its open, shared nature. This document formalizes the **core values**, **community structure**, and **current governance** of the [`iTowns`]([itowns](https://github.com/iTowns/itowns) project.

We welcome contributions from new stakeholders or other project actors wishing to propose changes to the governance structure.  

Any proposed changes can be submitted via a pull request or through a [proposal](https://github.com/iTowns/itowns-governance/blob/master/proposal.md).  

If you wish to propose changes on different topics, please create a separate PR or issue for each topic.
 
Contact us at [iTowns@ign.fr](mailto:iTowns@ign.fr).

---

## Values

- **Community Driven**  
  iTowns is a **commons**, developed collectively by a diverse [community of contributors](https://github.com/iTowns/itowns/blob/master/CONTRIBUTORS.md). Its **open and shared** nature is **immutable**.

- **Licensing**  
  Operates as free software under the MIT or CeCILL-B license.  It permits unrestricted reuse and modifications.
  [Source Code on GitHub](https://github.com/iTowns/itowns)

- **Public Benefit First**  
  The project serves community interest and broader public good, above specific private goals.  
  See the [Sustainability](#Sustainability) section for more details.

- **Inclusion and Diversity**  
  Contributions are welcomed from a diverse range of sources (private and public sector, researchers, individuals, etc.). This is achieved through the meritocratic recognition of contributors.

- **Transparent Collaboration**  
  All decisions are documented and made openly to ensure trust and long-term sustainability.

- **Compliance**  
  Contributors must follow established rules and agree to the code of conduct <TODO link>.

- **Peer Reviewing**  
  Significant contributions are peer-reviewed. Contributors can gain a more significant role by providing high-quality contributions within the established guidelines.

- **Community Sovereignty**  
  Governance is exercised autonomously by the community, free from external authority.

- **Transparent Planning**  
  Future developments are publicized and discussed openly before implementation.

- **Continuous Improvement**  
  The project evolves to stay aligned with state of the art developments developments in 3D geospatial data.
  

## Role definitions
- A **"User"** encompasses an individual or organization using the iTowns framework.
- A **"Contributor"** refers to any individual or organization actively involved in improvements to the iTowns project, whether through feature development, documentation additions, bug fixes, suggesting features, or other forms of value. They do not have direct commit access to the main repository. Their contributions are reviewed and merged by core-contributors
- A **"Core contributor"** is a trusted contributor with additional responsibilities as described below. Core contributors hold commit rights to the main branch of the project. 
- A **"Sponsor"** refers to organizations or individuals providing infrastructure, funding, or employee time for the growth, initiatives, and activities of the iTowns project. 
- The **"Community"** serves as an umbrella term, encompassing users, contributors, sponsors and other players within the iTowns project.


## Core contributors
A "Core contributor" is any contributor holding commit rights to the main branch of the project. These core contributors handle technical governance of the project and guarantee its durability and independence.


### Core contributors’ scope
- Ensure the project's sustainability in terms of maintainability and technical debt
- Directly committing changes to the main branches.
- Monitor ongoing developments.
- Review and merge PRs from others. 
- Enforcing the principle of reviewing and cross-validation, prohibiting validators from validating their own contributions or those of their respective organizations.
- Make consensus-based decisions on technical architecture and ensure its coherence.
- Participate in governance decisions.
- Operate continuously, with responsiveness, in a dedicated public discussion channel
- Address requests in issues
- Arbitrates requests for Core Contributors rights and their removal.
- Maintain onboarding resources and good-first-issue tagging.
- Recognizing contributors via changelogs, showcases, and optionally core contributor seats.


### Becoming a core contributor
Achieving status of Core Contributor requires significant contributions to the project, a demonstrated ability to produce high-quality code or other value to the project, and adherence to the guidelines outlined in the code of conduct, CODING.md TODO link and [CONTRIBUTING.md](https://github.com/iTowns/itowns/blob/master/CONTRIBUTING.md) documents.

New core contributors can be nominated by any existing core contributor. Their selection is then subject to a double majority vote within the Core Contributor group.

This role is granted on an individual basis (not as part of an organization). 

It may be rescinded for rule violations or if contributions cease for a one-year period. Revocation requires a double majority vote, excluding the concerned individual.
Should this person become active again, they will certainly be welcome, but would require a nomination.


## Project Steering Committee (PSC)
The project steering committee is the main governing body for the OpenSource project. It oversees its strategic direction. PSC members represent the interests of users and contributors. They all hold commit rights to the main branch of the project. The PSC operates openly with a consensus-based approach.

### PSC scope 
- Ensure that all project rules are respected, be it [values](#Values), governance or technical processes;
- Arbitrates on significant decisions (e.g., roadmap, release management, governance changes) and resolves disputes.
- Manages functional roadmap.
- Arbitrates on the conformity of pull requests with the functional roadmap.
- Manages releases.
- Oversees the project's sustainability in terms of maintainability and technical debt.
- Arbitrates decisions on technical architecture and ensures its coherence.
- Oversees ongoing developments.
- Arbitrates requests for Core Contributor's rights and their removal.
- Help Core contributors to evaluate and improve proposals.
- Contributes to functional testing of pre-production versions.
- Ensures outreach and project management. 
- At any point in time, the PSC can emit a veto for a proposal or a Pull Request. This veto must be motivated and its rationale explained in detail, with references to the project's values, es and global strategy and purpose.

### Meetings
The PSC holds meetings at the request of any PSC member, and every 2 months minimum. Active contributors who are not committee members may be invited to PSC meetings.
Member’s opinions are documented for transparency and as an objective metric of active participation, and proposed and adopted solutions are specifically reported.

### Joining the PSC
The PSC is made up of individuals based on their merit, and who are intended to represent the various organizations and communities which have a stake in the iTowns project. An odd number is chosen to facilitate the voting process and help prevent ties. However, even with an odd number, the voting system may still allow for a tie in some cases. For this reason the PSC has an appointed Chair, whose sole responsibility is to break ties among the PSC.
Turnover is allowed and expected to accommodate people only able to become active on the project in intervals. A PSC member may step down at any time.
The current members of the PSC are listed in the [membership](https://github.com/iTowns/itowns-governance/blob/master/membership.md) document.  


Membership in the PSC is determined by a formal system of nomination and voting. 
- A new PSC member can be nominated or self-nominate at any time. The nominated member may be an individual or an organization. In the latter case, a representative will be appointed by the organization.
- The candidate must send her/his application to the iTowns Users mailing lists TODO:link, providing a brief statement, after which voting can begin.
- A vote will follow. Only existing PSC committee members may vote on new members. Nominees must receive a majority vote from existing members to be added to the PSC.

Addition and removal of members from the committee should be handled as a proposal to the committee.
The PSC must ensure that its membership is diverse and representative of the different interests of iTowns users and contributors. Its composition must be proportional to the number of active contributors. 
PSC members are also [core contributors](#Core). They are thus subject to the same rules regarding inactivity and may also have their membership status challenged.

PSC Chair is nominated following the same procedure, with an absolute majority of PSC members’ (approval).


## Contribution process
You can either make a [`contribution`](https://github.com/iTowns/itowns/blob/master/CONTRIBUTING.md) or a proposal. Please read the [`Proposal process`](proposal.md) before.

## Versions
A new version of iTowns is released at least every 4 months.

Release
- The PSC leads the release process with the Core Contributors and set a release date.
- Tests are launched before the release of the new version: 
    - Unit tests
    - Functional tests
    - Client application test on the next branch
    - Regression tests through a complete run of all examples.
- The release process is finished only after tests validations.

Communication
- The Changelog is published on Github.
- Distribution on npmjs/github: 
    - Description of the version
    - Link to changelog
    - Link to examples 
TODO communication channels 
 
## Roadmap Update
- The items foreseen for the next releases are published on a public (non-exhaustive) roadmap and updated regularly by the PSC
- The project's progress is public and can be tracked at https://github.com/iTowns/itowns/projects?query=is%3Aopen.  TODO update




