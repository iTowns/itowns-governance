# Contribution and Review Process

## Introduction
Before making any contributions, it is important for contributors and the
community at large to open discussions (proposals) about addition or improvement
of features.
Those proposals are centralized on issues tagged "proposals" in the
`iTowns/itowns` repository.
This allows contributors to demonstrate the existence of real use cases and gain
a concrete understanding of user needs.

The diagram below outlines this proposal process.

## Type of Contribution
Contributions can be of three types:
- **Bug fixes** linked to an open bug issue on the `itowns/itowns` repository.
- **Documentation.**
- **Improvement of an existing feature or component**
- **Addition of a new feature.**

*Note: Proposals are only required for improvements or additions of features.
Bug reports are sufficient for proposing a fix.*

## Documentation
Documentation changes can be proposed directly through pull requests. In case of
questions or issues with documentation, an issue should be opened, following the
same proposal process as other contribution types.

## Bug Discovery and Correction Process
The entire bug discovery and correction process takes place on the itowns/itowns
repository.
1. A user or contributor submits a bug report through an issue (following the
   defined template).
2. A contributor submits a fix by opening a pull request linked to the
   corresponding issue in the description.

## Proposal Process
Improvements or new features occur through the opening of a dedicated proposal
on the itowns/itowns repository.

This can be initiated in two ways:
- As a community member through an informal discussion. The final feature takes
  shape through discussions and users feedback.
- As a contributor through an issue following the defined template:
   - Concise details of the feature, including use cases and supported by user
     needs.
   - Technical explanation of the suggested implementation.

*Note: Contributors can still directly open a pull request on the itowns/itowns
repository. However, it will be less prioritized (TODO: veto) than if it had
gone through the proposal process.*

The Product Committee then validates the proposal through a vote (functional
consensus).
- If validated, the feature or improvement is added to the project's roadmap.
- If on hold (lack of maturity, interesting but longer-term), the issue remains
  open, and discussions can continue.
- Otherwise, the issue is closed.

*Note: After CP validation of a proposal from a discussion, one or more
contributors can take on its development. The contributor(s) opens an issue
following the defined template without detailing the feature (a link to the
discussion is sufficient) and without CP validation of this issue.*

In this issue, technical consensus must be reached by a double majority of
reviewers (within a specified time, no response equals a yes). They evaluate:
- The technical quality of the chosen solution.
- The impact on the rest of the codebase.

After functional and technical consensus, the contributor can:
- Implement the feature following the chosen solution.
- Open a draft pull request on the main itowns/itowns repository (linking to the
  issue in itowns/itowns-proposals).
After implementation (when the pull request is ready), a two-step review phase
is conducted by two reviewers:
1. Functional review: The reviewer ensures that the implementation only adds the
   proposed functionality.
2. Technical review: The reviewer ensures that the implementation meets
   technical consensus.

This review phase is simplified as previous discussions help understand the
author's intentions and choices.

*Note: The reviewer is responsible for the implementation they validate and for
any bugs resulting from this validation.*
