# Fork of mozilla/kitsune, being re-writen for PubFeat

![Status Sustain](https://img.shields.io/badge/Status-Sustain-green)

PubFeat is an effort to create a portal that serves as a community driven issue epic/ backlog for organizations at large.

Rationale: Issues affecting hundereds or thousands or even millions of consumers are not accounted for publicly, rather dealt in silos of one-to-one support tickets, which puts consumers (includes children and elderly) and regulatory authorities at a disadvantage. This is not to say that orgs are doing anything wrong, however, a gap is evident. Org features are mostly driven by business need and regulatory afflictions, however, true urgency of meaningful features gets watered down when filtered and sourced from support systems and run teams, driven by their own kpis. 

Solution: A safe space for posting, assessing, voting on issues/ stories/ features as a collective, creating actionable backlog for Organizations at large to feed from. 

## Usage

It is a [Django](http://www.djangoproject.com/) application. There is [documentation](https://mozilla.github.io/kitsune/) on Kitsune by Mozilla, online.

## Releasing a new version

-   Create a [signed tag](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work) for the new version.

    We are using [semantic versioning](https://semver.org/).

    Given a version number MAJOR.MINOR.PATCH, increment the:

        MAJOR version when you make incompatible API changes
        MINOR version when you add functionality in a backward compatible manner
        PATCH version when you make backward compatible bug fixes

    Example:

    `git tag -s 1.0.1 -m "Bump version: 1.0.0 to 1.0.1`

-   Draft a new release in GitHub for the new tag. Document the **highlights** of the release and also use the option to automatically document the release through the commit history.

-   Trigger the release for the specified tag in the deploy repository.

> [!TIP]
> You can access the staging site at **TBD**

## Code of Conduct

By participating in this project, you're agreeing to uphold the [Mozilla Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/). If you need to report a problem, please see our [Code of Conduct](./CODE_OF_CONDUCT.md) guide.

## Contribute

See our [contribution guide](https://mozilla.github.io/kitsune/contributors), or dive into [setting up your development environment](https://mozilla.github.io/kitsune/hacking_howto/).

## Issues

We use [Bugzilla](https://bugzilla.mozilla.org/enter_bug.cgi?product=support.mozilla.org) for submitting and prioritizing issues.

## Thanks to all of our contributors ❤️

<a href = "https://github.com/mozilla/kitsune/contributors">
  <img src = "https://contrib.rocks/image?repo=mozilla/kitsune"/>
</a>
