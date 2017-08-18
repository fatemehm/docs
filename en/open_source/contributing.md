# Contributing

We appreciate you want to help us by contributing to Consul. Here's a guide we made describing how to contribute changes to the project.

## Reporting an issue

If you have seen anything wrong in the platform performance or directly in the code, we encourage you to [open an issue in the Consul Github repository](https://github.com/consul/consul/issues/new).

Before doing it, **please take some time to check the [existing issues](https://github.com/consul/consul/issues) and make sure what you are about to report isn't already reported** by another person. In case someone else reported the same problem before, if you have more details about it you can write a comment in the issue page -a little more help can make a huge difference!

In order to write a new issue, take into account these few tips to make it easy to read and comprehend:
- Try to use a descriptive and to-the-point title.
- It's a good idea to include some sections -in case they're needed- such as: steps to reproduce the bug, expected behaviour/response, actual response or screenshots.
- Also it could be helpful to provide your operating system, browser version and installed plugins.

## Resolving an issue

[Issues in Consul](https://github.com/consul/consul/issues) labeled with `PRs-welcome` are well defined features ready to be implemented by whoever wants to do it. In the other hand, the `not-ready` label marks features or changes not well defined yet or subject to an internal decision, so we recommend not to try to resolve them until the admins come to a resolution.

We suggest to follow these steps to keep a good track of the changes you're about to make:

- First of all, add a comment to the issue to make everyone know you are going to work on it. If the issue has someone assigned it means that person is already solving it.
- Fork the project.
- Create a feature branch based on the `master` branch. To make it easier to identify, you can name it with the issue number followed by a concise and descriptive name (e.g. `123-fix_proposals_link`).
- Work in your branch committing there your changes.
- Make sure all tests are passing. In case you're extending or creating a new feature, consider adding its own specs.
- Once you've finished, send a **pull request** to the [Consul repository](https://github.com/consul/consul/) describing your solution to help us understand it. It's also important to tell what issue you're addressing, so specify it in the pull request description's first line (e.g. `Fixes #123`).
- Our core team will review your PR and suggest changes if necessary. If everything looks good, your changes will be merged :)

> **Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

## Other ways of contributing

We'll appreciate any kind of contribution to Consul. Even if you can't contribute to it coding, you still can create issues to notify the project owners with as much information as you can provide about anything wrong you see, and someone will take care of it as soon as possible.