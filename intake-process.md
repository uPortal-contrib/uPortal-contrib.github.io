[TOC]

This is an intake process for sub-projects that are intended to be part of the greater uPortal Ecosystem. 
By virtue of being a sub-project, certain stipulations are accepted that allow this process to be easier and more
expedient yet still conform with the greater
[Apereo Incubation Process](https://www.apereo.org/content/apereo-incubation-process).
This makes it easier for organizations and individuals to contribute new projects to Apereo and the greater uPortal
Community. 

Goals:

*   Low barrier to entry; this is where and how you get started
*   More small projects out in the public
*   Fast track for things uPortal-related
*   Clear where new work should go
*   Centralized place for work
*   Clear what you should consider
    *   Licensing
*   Has certain stipulations, assumptions
*   Comes out meeting incubation exit criteria
*   Look at lessons learned from uPortal Home incubation
*   Clarify what is code that has been contributed vs code that is officially released

Stipulations:

*   Intend as part of the uPortal Ecosystem (community)
*   Intend to be licensed under Apache 2
    *   Otherwise compliant with Apereo licensing policy might be okay.
*   Identified sub-project contact	
*   Intended to execute conditions below upon acceptance
*   For consideration
    *   Encouraged to use other uPortal-related infrastructure

## Simplified Intake Process

### Narrative Version

This is an intake process for sub-projects that are intended to be part of the greater uPortal Ecosystem. By virtue of
being a sub-project, certain stipulations are accepted that allow this process to be easier and more expedient yet still
conform with the greater [Apereo Incubation Process](https://www.apereo.org/content/apereo-incubation-process). This
makes it easier for organizations and individuals to collaborate on more new projects in the context of Apereo and the
greater uPortal Community. Potential adopters and contributors should be able to easily see what projects are ready for
adoption, what projects are in development and being actively collaborated on, and what projects are no longer active.

A project may be suitable for intake if its participants intend it  \to be part of the uPortal Ecosystem, intend that it
be licensed under Apache 2 or other compatible license, and hope that others will engage with the project. Note that
while it is desirable that the code be licensed under Apache 2 upon intake, it is not required until exiting.

Submit a project for intake by posting on [uPortal-dev](mailto:uportal-dev@apereo.org) with 

*   A proposed name for the project, together with a brief explanation of why the project wishes to be part of the
    uPortal Ecosystem
*   A project readme
*   A proposed Project Lead with contact information 
*   A list of the initial committers for the Project; these committers MUST be Apereo
    [ICLA signatories](https://www.apereo.org/licensing/agreements/icla)
*   A pointer to any existing resources that may be of interest to and accessible by reviewers

Any uPortal Committer can accept the contribution. A Committer taking this action must 1) state their intention to
accept it as a sub-project on [uPortal-dev](mailto:uportal-dev@apereo.org), 2) wait 72 hours to allow other review and
potential voicing of concerns, 3) execute the repo bootstrapping in
[https://github.com/uPortal-contrib](https://github.com/uPortal-contrib). The uPortal Committer bootstrapping the repo
will ensure that the new repo has a COMMITTERS.md file clearly documenting the
[ICLA signatory committers](http://licensing.apereo.org/completed-clas) for the project.

Any uPortal Committer can -1 VETO a contrib proposal and that veto must be justified. A Committer might veto e.g. to
delay intake of a contribution with red flags as to provenance.

Upon intake, the committers and others interested in the sub-project are encouraged to use
[uPortal-dev](mailto:uportal-dev@apereo.org) and [uPortal-user](mailto:uportal-user@apereo.org) to further discuss and
develop the project. he project should not make any official releases until the code is properly licensed. Any new
committers must be be Apereo ICLA signatories. The project lead will report to uPSC minimally on an annual basis
regarding the status of the project.

A project can become an official uPortal sub-project by a vote of the uPortal Steering Committee. Candidate projects
must meet all
[Apereo incubation exit criteria](https://www.apereo.org/content/apereo-incubation-process#S4%20Exit%20Criteria).
Official sub-projects move to [https://github.com/uportal-project](https://github.com/uportal-project). On the other
hand, sub-projects that cease to show activity may move from contrib to the attic and can re-enter the intake process
at a later point if interest and activity returns.

### In Bullet Format

1.  Stipulations
    1.  Intention to be part of the uPortal Ecosystem
    1.  Intention to be licensed under Apache 2 or other compatible license
    1.  Hope for community engagement
1.  Submission
    1.  Submit via post to uportal-dev
    1.  A proposed name for the project, together with a brief explanation of why the project wishes to be part of the
        uPortal Ecosystem
    1.  A project readme
    1.  A proposed Project Lead with contact information 
    1.  A list of the initial committers for the Project; these committers MUST be Apereo ICLA signatories
    1.  A pointer to any existing resources that may be of interest to and accessible by reviewers
1.  Review
    1.  Any uPortal Committer can accept the contribution, creating a suitable repo in uPortal-contrib and configuring
        it to accept the contribution. A Committer taking this action must
        1) state intention to accept on uPortal-dev@
        2) wait 72 hours to allow other review and potential voicing of concerns
        3) execute the uPortal-contrib repo bootstrapping to make the acceptance so..
            - The uPortal Committer bootstrapping the repo will ensure that the new repo has a COMMITTERS.md file
              clearly documenting the committers for the project.
    1.  Any uPortal Committer can -1 VETO a contrib proposal. As all vetoes, a veto must be justified. A Committer might
        veto e.g. to delay intake of a contribution with red flags as to provenance.
1.  Expectations
    1.  New committers must be be Apereo ICLA signatories
    1.  The project lead will report to uPSC minimally on an annual basis
1.  Exit to uPortal Project
    1.  Project can become official uPortal sub-project upon vote by the uPSC
    1.  Meets all [Apereo incubation exit criteria](https://www.apereo.org/content/apereo-incubation-process#S4%20Exit%20Criteria)
    1.  Code moves to [https://github.com/uportal-project](https://github.com/uportal-project) 
1.  Exit to Attic
    1.  Sub-projects that cease to show activity may be moved from contrib to the attic. They can re-enter the intake
    process at a later point if interest and activity returns. Formally, the uPortal Steering Committee is the authority
    for deciding to move a sub-project to the Attic. The remaining active documented committers on a sub-project can
    vote to request that the Steering Committee take this action.

## Detailed Intake Process vs. Apereo Incubation Process

The uPortal Intake Process varies from the Apereo Incubation Process in the following ways:

### S2 Intake Process Overview

2.1 Submissions are sent to the uPortal Steering Committee rather than IWG. Further references to IWG can be replaced
    with uPSC (uPortal Steering Committee).

2.3 Rather than quarterly updates, uPSC would like at least bi-monthly updates.

### S3 Core Intake Process

3.1. **Purpose**: This process describes how an uPortal Intake Candidate or other Intake Proposal would progress from
     submission to full acceptance as a uPortal Sub-Project.

3.2 **Proposal Submission**:

*   Unsponsored Contribution related to uPortal will be accepted
*   Community of Interest are likely not to be accepted as the uPortal Community is our focus
*   An outline of reasons for choosing the submission outcome will be drafted; however, they will not be sent to the Apereo Board.

3.3 **Proposal Content**:

*   Proposal is made to uPSC via uportal-steering-committee@apereo.org
*   3.3.b Acceptance of uPortal-dev and uPortal-user as mailing list or reasons why an alternative will be used.
*   3.3.d two or more recommendations from active uPSC members
*   3.3.i An overview of how the sub-project relates to uPortal

3.4 **Submission Review**:

*   Acceptance of an sub-project is solely determined by uPSC

3.5 **Acceptance as an Intaking uPortal Sub-Project**:

*   Code forks into uPortal-Contrib Organization on GitHub
*   Other services have been superseded by GitHub

3.6 **Post Acceptance -- uPSC Next Steps**:

*   3.6.a "Intaking uPortal Sub-Project"
*   3.6.b uPSC nominates a mentor for the sub-project
*   3.6.e TO-REVIEW: in lieu of adding project to [www.apereo.org](www.apereo.org), do we add them in our web presence?

3.7 **Post Acceptance -- Sub-Project Next Steps**:

*   Indicate that the sub-project is in intake as a uPortal sub-project
*   ??Display uPortal logo??

3.8 **Periodic Review**:

*   3.8.a The sub-project will be adopted as a fully endorsed uPortal Sub-Project

3.9 **Promotion to Full-Fledged uPortal Sub-Project**:

*   uPSC plays both the IWG and board role in this section
*   Code moves to [https://github.com/uportal-project](https://github.com/uportal-project) Organization
*   Contact starts reporting quarterly to uPSC forever more

3.10 **Termination of Sub-Project Endorsement**:

*   uPSC plays IWG, board and governance structure in this section

3.11 **Conflict Resolution**:

*   This section stands as a sub-project or uPSC may engage IWG and/or board to help with conflict resolution.

### S4 Exit Criteria

4.1 **Legal**:

*   4.1.1 Apache2 license strongly encouraged (GPL and other licenses MAY be considered)
*   4.1.2 Follow uP standard NOTICE and LICENSE

4.2 **Community**

*   This area differs from Apereo Incubation the most. The sub-project will be integrating into the uPortal Community.
    Evaluation is on how well the sub-project integrates.
*   In addition, COMMITTERS.md needs to exist

4.3 **Governance**

*   Governance for the sub-project is uPSC. If not, then the "project" should not use this process.
*   Specifically, [uPortal code of conduct](https://github.com/Jasig/uPortal/blob/master/CODE_OF_CONDUCT.md) must be
    recognized as applying to sub-project

4.8. **Alignment & Synergy**

*   This is assumed by integration into the uPortal Ecosystem.

4.9 **Infrastructure**

*   Sub-project shall be hosted with the other uPortal sub-projects, currently at GitHub.
*   GitHub docs are used in lieu of a project website.

