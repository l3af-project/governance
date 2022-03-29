# Defining L3AF project maintainers

## Finding all the L3AF projects

You can see all of the repositories associated with L3AF by navigating to the top-level [L3AF organization on GitHub](https://github.com/l3af-project).

Typically a L3AF sub-project is represented by a single repository (repo). For instance, the Specs and Architecture project is represented in the [l3af-arch](https://github.com/l3af-project/l3af-arch) repo. In the future it's possible that a single project may require multiple repos. The contents of this document still hold true in that case (and if you find that's wrong, please [open and issue](https://github.com/l3af-project/governance/issues/new/choose) and we'll fix it).

## Who are the current maintainers?

The maintainers for each L3AF sub-project are contained in the `CODEOWNERS` file in the respective repositor(y|ies).

## Removing a maintainer from a project

There are many reasons why a maintainer may need to leave a project. In the case that one does, please follow these steps:

1. Open an issue in the appropriate repo(s) describing the necessary change
1. Create a pull request (PR) in each relevant repo, making the necessary change to the `CODEOWNERS` file
1. Add an item about the maintainer change to [the agenda for the next L3AF TSC meeting](https://wiki.lfnetworking.org/display/L3AF/Meeting+Minutes?src=contextnavpagetreemode)
1. Discuss the change in the meeting
1. If the TSC approves (by majority vote of all present [TSC members or their proxies](https://wiki.lfnetworking.org/pages/viewpage.action?pageId=62491327)), merge the PR. If they do not approve, close the PR without merging or continue the discussion with the TSC as necessary.

**NO MAINTAINER CHANGES ARE VALID WITHOUT TSC APPROVAL**

## Adding a maintainer for a project

All projects should ideally have multiple maintainers (as listed in the relevant `CODEOWNER` file(s)). There currently are no upper limits set on the number of maintainers for a L3AF project. A project will have as many maintainers as it sees are useful for the functioning of the project and its community. To add a maintainer to a L3AF project, please follow these steps:

1. Open an issue in the appropriate repo(s) describing the necessary change
1. Create a pull request (PR) in each relevant repo, making the necessary change to the `CODEOWNERS` file
1. Add an item about the maintainer change to [the agenda for the next L3AF TSC meeting](https://wiki.lfnetworking.org/display/L3AF/Meeting+Minutes?src=contextnavpagetreemode)
1. Discuss the change in the meeting
1. If the TSC approves (by majority vote of all present [TSC members or their proxies](https://wiki.lfnetworking.org/pages/viewpage.action?pageId=62491327)), merge the PR. If they do not approve, close the PR without merging or continue the discussion with the TSC as necessary.

**NO MAINTAINER CHANGES ARE VALID WITHOUT TSC APPROVAL**

(yes, this currently is exactly the same as removing a maintainer; we're documenting it separately to disambiguate the process for each and also to prepare for the eventuality that the processes will need to diverge)
