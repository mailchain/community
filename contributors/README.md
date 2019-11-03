# Guide

Welcome to Mailchain. This document is a guide for how to contribute to the code base. Please read and observe our [Code of Conduct](/code-of-conduct.md).
Browse the [open issues](https://github.com/mailchain/community/issues) and file new ones, all feedback welcome!

## Before you get started

Follow the getting [started guide](https://docs.mailchain.xyz/getting-started) to install, setup, and send your first message.

## Community Expectations and Roles

Mailchain is a community project.

It depends on its community to provide a productive, friendly and collaborative environment.

Please read and review the [Community Expectations](expectations.md) for an understanding of code and review expectations.

## Your First Contribution

Have you ever wanted to contribute to the coolest blockchain messaging technology?

We will help you understand the organization of the Mailchain project and direct you to the best places to get started.

You'll be able to pick up issues, write code to fix them, and get your work reviewed and merged.

If you have questions about the development process, jump into our [Slack Channel](https://mailchain.slack.com/).  The Mailchain team scans Slack regularly and will usually answer quickly.

### Find Something to Work On

Help is always welcome! For example, [documentation](https://docs.mailchain.xyz) can always use improvement.

There are always clarifications to code, or renaming of functions/variables.

There's always a need for more test coverage.

You get the idea - if you ever see something you fix or improve, own it. The community appreciates it.

If you do not know what to start on, look at the [open issues](https://github.com/mailchain/mailchain/issues) or ask in our [Slack Channel](http://mailchain.slack.com/) to see who is looking for help or what's being worked on.

Those interested in contributing without writing code may also find ideas in the [Non-Code Contributions Guide](non-code-contributions.md).

### Find a Good First Topic

There are [multiple repositories](https://github.com/mailchain/) in the Mailchain organization.

Taking [mailchain/mailchain](https://github.com/mailchain/mailchain) as an example, you can head to the [help wanted](https://github.com/mailchain/mailchain/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) and [good first issue](https://github.com/mailchain/mailchain/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) labels for issues that should not need in-depth knowledge of the system.

The `good first issue` label shows that members have committed to providing extra help for new contributors.

Please note that while several of the repositories in the Mailchain community have `good first issue` labels already, they are still being applied throughout the community.

Another good approach is to find a documentation improvement, such as a missing/broken link, which will give you exposure to the code submission/review process without the added complication of technical depth.

Please see [Contributing](#contributing) below for the workflow. When you take on an issue, you can assign it to yourself.

### It's Easy to File an Issue

Not ready to contribute code, but see something that needs work?

The community encourages everyone to contribute code, but we also appreciate when someone reports an issue (AKA a problem).

Raise issues under the appropriate Mailchain sub-repository. For example: open a documentation issue in [mailchain/docs.mailchain.xyz](https://github.com/mailchain/docs.mailchain.xyz/issues).

Adhere to the prompted guidelines while opening an issue and fill out as much as you can. This will help the community fix it.

## Contributing

Mailchain is an open source project, but many of the people working on it do so as their day job. To avoid forcing people to be "at work" effectively 24/7, we want to establish some semi-formal protocols around development. Hopefully, these guidelines make things go more smoothly. If you find that this is not the case, please complain loudly.

As a potential contributor, your changes and ideas are welcome at any hour of the day or night, weekdays, weekends, and holidays. Please never hesitate to ask a question or send a pull request.

Beginners can find focused information below in [Open a Pull Request](#open-a-pull-request) and [Code Review](#code-review).

## GitHub workflow

To check out the code to work on, please refer to [the GitHub Workflow Guide](./github-workflow.md).

## Open a Pull Request

Pull requests (PR) follow the standard [github pull request](https://help.github.com/articles/about-pull-requests/) process. We need to build our integration tests there as several components that need building first.

## Code Review

For a brief description of the importance of code review, please read [On Code Review](/contributors/expectations.md#code-review).  

There are two aspects of code review: giving and receiving.
To make it easier for your PR to receive reviews, consider the reviewers will need you to:

- follow the project [coding conventions](./guide/coding-conventions.md)
- write [good commit messages](https://chris.beams.io/posts/git-commit/)
- break large changes into a logical series of smaller patches which individually make easily understandable changes, and in aggregate solve a broader issue

Reviewers are highly encouraged the people giving the review to revisit the [Code of Conduct](/code-of-conduct.md) and [community expectations](./expectations.md#expectations-of-reviewers-review-latency) and must go above and beyond to promote a collaborative, respectful community.

When reviewing a pull request from others [The Gentle Art of Patch Review](http://sage.thesharps.us/2014/09/01/the-gentle-art-of-patch-review/) suggests an iterative series of focuses which leads new contributors to positive collaboration without inundating them initially with nuances:

- Is the idea behind the contribution sound?
- Is the contribution architected correctly?
- Is the contribution polished?

Note: if your pull request isn't getting enough attention, you can use the [#pr-reviews](https://mailchain.slack.com/messages/pr-reviews) channel on Slack to get help to find reviewers.

## Testing

Testing is the responsibility of all contributors, run unit tests before opening a pull request, and an perform an end to end test run before requesting us to merge a pull request.

## Documentation

If you pull request requires and changes to the documentation open a [pull request for the docs](https://github.com/mailchain/docs.mailchain.xyz/).

## Community

If you haven't noticed by now, we are building a lively, and friendly open-source community.

We depend on new people becoming members and regular code contributors, so we would like you to come join us!

## Mentorship

Please learn about our [mentored contributor program](/mentoring/mentored-contributor.md)
