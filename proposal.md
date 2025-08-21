# Proposal, Contribution and Review Process

## Introduction
Before making any contributions, it is important for contributors and the community at large to open discussions ( proposals ) about addition or significant improvement of features.

Those proposals are centralized on issues tagged "proposals" in the iTowns/itowns repository.

This allows contributors to demonstrate the existence of real use cases and gain a concrete understanding of user needs, as well as a more fluid process for contributions, and better visibility for the end users and stakeholders.

## Types of Contribution
Contributions can be different types, including:
- **Documentation**
-	**Bug fixes** linked to an open bug issue on the `itowns/itowns` repository.
- **Documentation**.
- **Improvement** of an existing feature or component
- **Addition** of a new feature.
  
*Note: Proposals are only required for improvements or additions of features. Bug reports are sufficient for proposing a fix.*

### Bug Discovery and Correction (proposal not required)

The entire bug discovery and correction process takes place on the `itowns/itowns` repository.
1. A user or contributor submits a bug report through an issue (using the predefined template).
2. A contributor submits a fix by opening a pull request linked to the corresponding issue in the description


### Significant improvements and new features (proposal required)

Significant improvements or new features occur by opening a dedicated proposal issue on the itowns/itowns repository.
This can be initiated in two ways:
- As a community member through an informal discussion. The final feature takes shape through discussions and user’s feedback.
- As a contributor through an issue using the defined proposal template containing: 
    - Concise details of the feature, including its rationale, and use cases supported by user needs.
    - Technical explanation of the suggested implementation.
  
*Note: Contributors can still directly open a pull request on the itowns/itowns repository. In this case, it is expected for the pull request to include the same informations as for a proposal issue. However, proposals are prioritized by reviewers over PRs submitted without proposal.*

To validate the proposal, a functional and technical consensus must be reached.

**Functional consensus**:
- The PSC validates the proposal through a double majority vote (functional consensus).
- If validated, the PSC can integrate the proposal to its roadmap items, and to the list of items subjects for resource allocations from the Sponsors.
- If on hold (lack of maturity, interesting but longer-term), the issue remains open, and discussions can continue.
- Otherwise, the issue is closed.

Expressions of non-validity of the proposal must be motivated and their rationale explained, with reference to the values, processes and documents of the project.

*Note: After CP validation of a proposal, one or more contributors can take on its development. The contributor(s) opens an issue following the defined template without detailing the feature (a link to the discussion is sufficient) and without PSC validation of this issue.*

**Technical consensus**:

In this issue, technical consensus must be reached by a double majority of core contributors. They evaluate:
- adherence to processes, values and overall project direction,
- technical coherency with existing code base,
- technical quality of the chosen solution,
- impact on the rest of the codebase,
- non-regression.
  
If at least one of the Core Contributors expresses a non-favorable advice to the proposal, the issue can remain open, the proposal can be amended and discussions can continue until the negative advice is removed. Meanwhile, no implementation corresponding to this proposal should be merged.

If a consensus is reached, or no negative advice from Core Contributors or PSC has been expressed 1 month after the last comment on the proposal, it is considered as acceptable.

# Implementation & review
After the proposal phase, contributors can:
- Implement the feature following the chosen solution.
- Open a draft pull request on the main itowns/itowns repository (linking to the proposal issue in itowns/itowns)

After implementation, the PR is marked as "Ready", and the review phase can begin:
1.	Functional review: The reviewer ensures that the implementation adds the proposed functionality corresponding to the initial proposal
2.	Technical review: The reviewer ensures that the implementation respects the project's processes and meets technical consensus

Only core contributors are considered as valid reviewers.

PSC members are also expected to assess the functional aspect of the implementation.

The merge action is achieved by a Core Contributor, who is expected to take responsibility for the code merged, with the collaboration of the initial contributor(s).

This review phase is simplified as previous discussions around the proposal helped understand the author's intentions and choices.








