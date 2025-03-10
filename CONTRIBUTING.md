# Contributor Guide

This document outlines what is expected of contributors to the Lexicon Community.

## Types of Contributions

This organization is volunteer run and contributions come in many forms. Recognizing this is critical to having a diverse and inclusive organization.

* Lexicon schema file changes, including the introduction and modification of `community.lexicon.*` changes.
* Documentation and guidance on how Lexicon Community lexicons are used and referenced.
* Reference material, including proof-of-concept code and writings, that provide context and examples for others on how to use Lexicon Community lexicons.
* Policy, governance, and process contributions to improve how the Lexicon Community Technical Steering Committee and Collaborators work with the community and accomplish the project’s mission.

There are other ways that people can contribute, and this is not an exclusive list.

## Lexicon Repository

The [lexicon-community/lexicon](https://github.com/lexicon-community/lexicon) repository is the location that contains all of the official and approved lexicon schema files.

The "main" branch contains lexicon schema files and related material that is considered “production”. Access to write to the main branch, including who has authority to merge content into it is moderated.

## Play Books

### How Do I Add A Lexicon?

Lexicon additions and changes start with the formation of a working group at the direction of the technical steering committee.

#### Working Group Formation

Before any lexicon schema development occurs, a working group is formed. A working group is a short-lived group of 1-3 people that do the initial work for the lexicon.

1. In the [lexicon-community/governance](https://github.com/lexicon-community/governance) repository, a discussion is created by a technical steering committee that states the objective of the working group. It should include what the expected deliverable is as well as a general timeline. That technical steering committee member is the directly responsible individual and is charged with ensuring the objective is met.
2. Discussion occurs among technical steering committee members to get to agreement on the objective and goals.
3. In the lexicon-community/governance repository, an issue is created to bootstrap the working group. That issue is used to track all of the tasks needed to enable the working group to be successful.

#### Working Group Day-to-Day

Once the working group is formed, it is up to it’s members to go about the business of the working group to meet the objective. Working groups are meant to be self-organizing, but use official channels.

Depending on the site and scope of the working group, a temporary repository (i.e. "wg-bookmarks-lexicon") will be forked off of [lexicon-community/lexicon](https://github.com/lexicon-community/lexicon). Access will be limited to the technical steering committee and collaborators.

1. The working group produces the lexicon schema definition files, documentation, and reference material needed to fulfill their objective.
2. The working group reports this to the technical steering committee and during that meeting, the next steps are worked out.

Eventually the produced work takes the form of a pull-request in the [lexicon-community/lexicon](https://github.com/lexicon-community/lexicon) repository. These pull requests will have an agreed upon "do not merge before" date to allow for adequate time for discussion.

Alternatively, if the working group concludes with no proposed changes, some form of report or discussion will be reported in the [lexicon-community/lexicon](https://github.com/lexicon-community/lexicon) discussion indicating such.

#### Request For Feedback

After the working group pull requests are created, a call for feedback is made to the broader community of collaborators and Lexicon Community contributors.

This open, iterative process takes place publicly with discourse happening in [lexicon-community/lexicon](https://github.com/lexicon-community/lexicon) discussions.

Once the "do not merge before" date has passed and if the changes have approval by at least 2 technical steering committee members, the changes can be merged and move forward to release.

#### Release

The release process for lexicon additions and changes includes several steps:

1. The changes are merged into the main branch.
2. The lexicon is published for discovery through official lexicon discovery paths, specifically PDS records and DNS records.
3. The lexicon is announced through the Lexicon Community social media channel

### How are Lexicons Updated?

Lexicon modifications can take two forms.

1. Non-structural changes, including documentation and reference material, can be proposed by contributors in the form of pull requests.
2. Structural changes and feedback should take place in the form of a pull request or GitHub discussion

A technical steering committee member or collaborator may make the determination that the change is large enough in scope to warrant additional discussion and scrutiny. In those cases, a working group will be formed to fully explore the change and its impact.

#### Hotfixes

An important caveat to this is the concept of a hotfix. In the event of a critical or breaking change, a technical steering committee member may create a hotfix pull request. A hotfix PR would require approval by at least two other TSC members to be merged and released.

### Lexicon Proposal Best Practices

Lexicon schemas vary in complexity and there is no single design pattern to draw from. Instead, consider how you would answer the following questions when designing and proposing lexicon changes.

What does the proposal accomplish and can it be accomplished with existing lexicons?

Are common conventions used? Compared to adjacent Lexicon Community lexicon schema definition files, are fields and types that accomplish similar things named or presented in a way that makes them easy to understand? Are fields and types vague in naming or purpose?

Do all fields and types have relevant and helpful documentation? Is there supplemental or localized documentation or writings supporting the proposal?

Does the proposal include example records to demonstrate how they are used? Are the examples based on real-world scenarios that readers can use directly?

Are there example applications or reference material in the form of code that demonstrate how records and methods are constructed and invoked?
