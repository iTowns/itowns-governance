Governance Draft (as of September 2023)
----

## Preamble
iTowns is an **open-source framework** designed for the **efficient visualization, navigation, and interaction** with **multi-scale 2D and 3D geospatial data** on the **web**.
Built on the [`three.js`](three) general-purpose 3D library, it enables users to easily build their own customized 3D geographic applications.

iTowns is a **geographic commons**, developed collectively by a diverse community of contributors, comprising independent developers, public organizations, research laboratories and private companies.

The commons is guided by **rules** that safeguard its expansion and the immutability of its open and shared nature.
This document formalizes the **core values**, **community structure** and **governance** of the [`iTowns`](itowns) project.


## Definitions
- A "**User**" encompasses individual or organization using the `iTowns` framework.
- A "**Contributor**" refers to any individual or organization actively involved in improvements to the iTowns project, whether through feature, documentation additions or bug fixes.
- A "**Core developer**" is any contributor holding commit rights to the main branch of the project.
- A "**Stakeholder**" refers to organizations providing financial support for the growth, initiatives, and activities of the iTowns project.
  These stakeholders are responsible for all governance, funding, and institutional decisions.
- The "**Community**" serves as an umbrella term, encompassing users, contributors, and stakeholders within the iTowns project.


## Values
- iTowns is a **commons**, developed collectively by a diverse community.
  Its **open and shared nature** is **immutable**.
- Operating as **free software** under the MIT or CeCILL-B license, it permits unrestricted reuse and modifications, with the source code readily accessible at [https://github.com/iTowns/itowns](itowns:github).
- Contributors must adhere to the established rules and agree to the [**code of conduct**](coc).
- **Peer reviewing** is a fundamental aspect of the project.
  Contributors can gain a more significant role by providing high-quality
  contributions within the established guidelines.
- The community holds **sovereignty** and autonomously exercises governance over the project, free from external authority.
- A **public roadmap** displays forthcoming developments.
- The dynamics of the open-source project are maintained to keep it aligned with **state of the art developments** in the field of 3D geospatial data visualization.


## Sustainability
- The project identifies **key stakeholders** who contribute significantly to its sustainability across its life cycle, adhering to the governance rules defined in this document.
  Current **key stakeholders** are given in the [membership](./membership.md) document.


## Governance Organization
Governance is structured into quickly deployable **committees**, each possessing **well-defined responsibilities** and a **transparent decision-making process**.
The objective is to ensure clarity and understanding for the `iTowns` project community.

### Project Steering Committee (PSC)
Comprising stakeholders providing financial support the growth, initiatives and activities of the iTowns project, the **Project Steering Committee** (*PSC*) **oversees the strategic direction** of the project.

#### Role of the PSC
- Shapes the **strategic directions** of the project in collaboration with all stakeholders.
- **Arbitrates** significant technical-functional and scientific roadmap proposals submitted by the product committee.
- Handles **relationships with external entities** such as industrial partners, institutional bodies, scientific organizations and associations.
- Makes **decisions on budget and intellectual property** matters.
- Oversees and approves **project communication** strategies.
- **Establishes and executes a governance framework**, including amendment to the present document, requiring a two-thirds majority approval.
- **Votes membership** requests within the committee.

#### Joining the PSC
Organizations seeking PSC membership must meet the following prerequisites:

- **Contribute** an amount equivalent of a full-time annual commitment for one year to the project.
- **Adhere** to project's governance rules
- **Commit to continue collaboration** under equivalent or higher resource
conditions for a minimum of two years.

**New memberships** are subject to a simple majority vote by current PSC members, taking into account adherence to the values and rules of the present document.

Members requesting or discontinuing collaboration for a one-year period will automatically exit the PSC.

#### PSC meetings
- Convenes **formal meetings every six months**, either in person or via video conference and remains accessible via email as required by the product or technical committees.
- Publishes **meeting summaries** on a dedicated public channel ([iTowns website](itowns) or [GitHub](itowns:github)).
- Collaborates closely with the product committee.
- Has the authority to **invite** other project actors to its meetings, granting them an advisory role without voting rights.


### Product Committee (PC)
The **Product Committee** (*PC*) comprises representatives from project-stakeholders and elected core developers.
The PC **oversees the functional aspects and roadmap** of the project, ensuring alignment with defined goals and needs.

#### Role of the PC
- Ensures **project alignment** with the Community's needs and the strategic directions set by the PSC for the project.
- Organizes the collection of requirements based on information provided by the Strategic Committee, Scientific Committee and the Community.
- Coordinates the collection of user requirements through pull requests, user feedback, and discussions.
- Manages the project roadmap (following potential arbitration by the Strategic Committee).
- Validates developments before their deployment in a pre-production environment.
- Plans the version release schedule.

#### Joining the PC
The annual renewal and structure of the Product Committee are as follows:
- Two-thirds of its members are designated by the PSC.
- One-third is elected by the Core Developers.

#### Meetings
- Convenes **formal meetings every two months** and engages in **continuous discussion** through a [dedicated public channel](itowns:chan).
- Publishes **meeting summaries** on a dedicated public discussion channel ([iTowns website](itowns) or [Github](itowns:github)).
- Has the authority to **invite** other project actors to its meetings, granting them an advisory role without voting rights.


### Core Developers
The "**Core developers**" committee comprises contribution validators holding commit rights to the main branch of the project.
They uphold adherence to the project's architectural coherence, technical viability, and oversee contributions in accordance to the roadmap.

#### Role of the Core Developpers
- **Ensures the project' sustainability** in terms of maintainability and technical debt.
- Makes **decisions on technical architecture** and ensures its coherence.
- **Monitors** ongoing **developments**.
- **Addresses requests** in issues.
- **Validates** the conformity of pull requests with the functional roadmap and
  established technical consensuses.
- Arbitrates requests for Core Developers rights and their removal.

#### Operation of the Core Developpers
- Operates continuously, with responsiveness deadlines, in a dedicated public discussion channel.
- Holds meetings every two months and publishes meeting summaries via a public channel on GitHub. Active contributors who are not committee members may be invited.
- Member opinions are documented for transparency and as an objective metric ofactive participation.
- Tracks proposed and adopted solutions.
- Enforces the principle of cross-validation, prohibiting validators from validating their own contributions or those of their respective organizations.

#### Joining the Core Developpers
Every contributor holding commit rights to the main project is a Core Developer.
Achieving status of Core Developer requires significant contributions to the project, a demonstrated ability to produce high-quality code, and adhere to the guidelines outlined in the code of conduct, CODING.md and CONTRIBUTING.md documents.

Access to the validator role is subject to a double majority vote by the Core Developers.
This role is granted on an individual basis (not as part of an organization).
It may be rescinded for rule violations or if contributions cease for a one-year period.
Revocation requires a double majority vote, excluding the concerned individual.

A Core Committer loses their rights after more than 6 months of inactivity and may also have their membership status challenged by peers for non-compliance with governance and project rules (code of conduct, adherence to contribution rules, etc.).


## Contribution process
See [Proposal process](proposal.md).


## Versions
A new version of iTowns is released every 2 months.  

### Release 
- The PC leads the release process with the Core Developpers and set a release date.
- Tests are launched before the release of the new version:
  + Unit tests
  + Functional tests
  + Client application test on the next branch
  + Regression tests through a complete run of all examples.

### Communication
- The changelog is distributed on Github.
- Distribution on npmjs/github:
  + Description of the version
  + Link to changelog
  + Link to examples.

### Roadmap Update
- The roadmap is public and updated on a two-month cycle.
- the project's progress is public and can be tracked at https://github.com/iTowns/itowns/projects?query=is%3Aopen.
- Anyone can suggest adding a new feature to the roadmap through an proposal.

[coc]: https://www.contributor-covenant.org/fr/version/2/0/code_of_conduct/
[itowns]: http://www.itowns-project.org/
[itowns:github]: https://github.com/iTowns/itowns
[itowns:chan]: todo
[three]: https://threejs.org/
