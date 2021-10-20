# Project Governance

This document illustrates the government process for the entire Karavel Project (from now on referred to as "the Project").
Since the Project is composed of many individual projects, some independent and some interdependent, an ideal governance
model would require a more structured approach, with a central committee acting as the coordinating body for the individual
project maintainer committees. However, since the Karavel community is still growing and has not yet reached the momentum
where this kind of organization is needed, we are adopting a simpler model in the time being.

The Project will switch to a more suited governance model as soon as the need arises.

- [Individual Project Governance](#individual-project-governance)
  - [Becoming a Maintainer](#becoming-a-maintainer)
- [Steering Committee](#steering-committee)
- [Meetings](#meetings)
- [Code of Conduct Enforcement](#code-of-conduct)
- [Voting](#voting)
- [Adding New Subprojects](#adding-new-subprojects)
- [Removing projects](#removing-projects)

## Individual Project Governance

All active Maintainers of each subproject are members of that project's Maintainer Committee, which governs that project.
The subproject's Maintainer Committee is responsible for the following project governance activities:

* Ensuring that the subproject creates and publishes regular releases;
* Holding regular, subproject-wide discussions on issues and planning;
* Monthly review of project contributors for advancement on the Contributor Ladder;
* Making final decisions on subproject changes that involve controversial trade-offs;
* Responding to security compromise reports;
* Supporting the Code of Conduct within their subproject and referring violations
  to the Code of Conduct Committee.

Should a member of the Maintainer Committee cease being active in the subproject,
violate the Code Of Conduct, or need to be removed for some other reason, they
may be removed by a 2/3 majority vote of the other Committee members, or a
majority vote of the Steering Committee.

### Becoming a Maintainer

To become a Maintainer you need to demonstrate the following:

* commitment to the project:
  * participate in discussions, contributions, code and documentation reviews
    for 3 months or more,
  * perform reviews for 10 non-trivial pull requests,
  * contribute 10 non-trivial pull requests and have them merged,
* ability to write quality code and/or documentation,
* ability to collaborate with the team,
* understanding of how the team works (policies, processes for testing and code review, etc),
* understanding of the project's code base and coding and documentation style.

A new Maintainer must be proposed by an existing maintainer by sending a message to the
[developer mailing list](https://groups.google.com/g/karavel-dev). A simple majority vote of existing Maintainers
approves the application.

Maintainers who are selected will be granted the necessary GitHub rights,
and invited to the [private maintainer mailing list](https://groups.google.com/u/1/g/karavel-dev-private).

## Steering Committee

The overall Karavel Project is governed by a Steering Committee. Until a sufficient number of Individual Project Maintainers
is reached, all Maintainers are automatically considered members of the Steering Committee.

When the number of Maintainers reaches a sufficient threshold (more than 6), the Steering Committee will transition
to an election model.

## Meetings

Time zones permitting, Maintainers are expected to participate in the public
developer meeting, which occurs monthly on the project [Discord server](https://discord.gg/ZrKBndbmje).

Maintainers will also have closed meetings in order to discuss security reports
or Code of Conduct violations. Such meetings should be scheduled by any
Maintainer on receipt of a security issue or CoC report. All current Maintainers
must be invited to such closed meetings, except for any Maintainer who is
accused of a CoC violation.

## Code of Conduct

[Code of Conduct](./CODE_OF_CONDUCT.md)
violations by community members will be discussed and resolved
on the [private Maintainer mailing list](https://groups.google.com/u/1/g/karavel-developer-private).  If the reported CoC violator
is a Maintainer, the Maintainers will instead designate two Maintainers to work
with CNCF staff in resolving the report.

## Voting

While most business in the Karavel Project is conducted by "lazy consensus", periodically
the Maintainers may need to vote on specific actions or changes.
A vote can be taken on [the developer mailing list](https://groups.google.com/g/karavel-dev) or
[the private Maintainer mailing list](https://groups.google.com/u/1/g/karavel-developer-private) for security or conduct matters.  
Votes may also be taken at [the developer meeting](#meetings).  Any Maintainer may
demand a vote be taken.

Most votes require a simple majority of all Maintainers to succeed. Maintainers
can be removed by a 2/3 majority vote of all Maintainers, and changes to this
Governance require a 2/3 vote of all Maintainers.

## Adding New Subprojects

During the monthly Steering meeting, any project member may recommend projects
to become part of the Karavel Project.  These projects should have the following
characteristics:

* Have a mission in line with the Project core pillars;
* Are appropriately licensed and governed or willing to become so;
* Are under active development;
* Consist of high quality code and designs.

Before submitting an application to the Steering Committee, the applying project
must hold an internal consensus vote of all major contributors to join
the Karavel Project.  The Steering Committee will then review the
application, and decide whether or not to accept it.  If it is accepted, the Committee
will assign one person to assist the subproject in their integration.

In some cases, promising but incomplete projects may be accepted as Experimental
Subprojects.  Such Experimental Subprojects will be considered part of
the Karavel Project, but will be marked as Experimental on the website and in code
repositories, in order to inform users.  Experimental Subproject Members are considered
Members of the Karavel Project, but the subproject is not entitled to a representative on the
Steering Committee.  Steering will review Experimental Subprojects at least twice
per year to determine if they have matured to full subproject status.

## Removing Projects

In some cases, projects will become inactive or unmaintainable, or wish to separate
from the Karavel Project. Any Steering Committee member may propose removal of a project on
these grounds, and Steering can confirm this with a majority vote.

Projects which still have contributors will then be moved to a repository in their
own namespace.  Projects which have ceased all activity are moved to the karavel-archive namespace.
