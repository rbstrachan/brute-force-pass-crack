# Contributing to Camden MacLeod's BFPC

:+1::tada: &nbsp;&nbsp; First off, thanks for taking the time to contribute! &nbsp;&nbsp; :tada::+1:

The following is a set of guidelines for contributing to BFPC and its packages, which are hosted on the [repl.it website](https://repl.it/@CyanCoding). These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Table Of Contents

- [Code of Conduct](#code-of-conduct)
- [I don't want to read this whole thing, I just have a question!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)
- [How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)
- [Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [Documentation Styleguide](#documentation-styleguide)

## Code of Conduct

This project and everyone participating in it is governed by the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [this repositories owner](mailto:rossbstrachan@gmail.com).

## I don't want to read this whole thing I just have a question!

For questions concerning Camden's BFPC - including descriptions and explanations of the code - you can [contact Camden MacLeod](http://cyancoding.net16.net/contact) directly.

For questions and information regarding this repository, you can ask your question by [opening an issue](https://github.com/rbstrachan/brute-force-pass-crack/issues).

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for BFPC. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](ISSUE_TEMPLATE.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3Arbstrachan)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues). After you've determined what your bug is related to, create an issue on it and provide the following information by filling in [the template](ISSUE_TEMPLATE.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or a command, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with a Keybinding Resolver**. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of BFPC) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of BFPC?** What's the most recent version in which the problem doesn't happen? You can download older versions of BFPC from [repl.it](repl.it/@cyancoding).
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **What's the name and version of the OS you're using**?
* **Are you using BFPC with multiple monitors?** If so, can you reproduce the problem when you use a single monitor?
* **Which keyboard layout are you using?** Are you using a US layout or some other layout?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for BFPC, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](ISSUE_TEMPLATE.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3Arbstrachan)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined what your enhancement suggestion is related to, create an issue on it and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of BFPC which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most BFPC users.
* **Specify the name and version of the OS you're using.**

### Your First Code Contribution

Unsure where to begin contributing to BFPC? You can start by looking through the `beginner` and `help-wanted` issues:

* [Beginner issues](https://github.com/rbstrachan/brute-force-pass-crack/issues?q=is%3Aopen+is%3Aissue+label%3A"good+first+issue") - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues](https://github.com/rbstrachan/brute-force-pass-crack/issues?q=is%3Aopen+is%3Aissue+label%3A"help+wanted") - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

* Fill in [the required template](PULL_REQUEST_TEMPLATE.md)
* Do not include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible.
* Document new code based on the [Documentation Styleguide](#documentation-styleguide)
* End all files with a newline

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown).
