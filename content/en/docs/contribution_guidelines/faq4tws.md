---
title: "FAQ for Technical Writers"
linkTitle: "FAQ for Technical Writers"
weight: 70
date: 2020-11-23
description: >
    Find answers to commonly asked questions about using the docs-as-code workflow.
---

## What is a docs-as-code workflow?

A docs-as-code workflow means applying software development processes and tools to technical documentation. As a Technical Writer (TW), you write content in plain text format using a code editor, rather than a markup language like XML and a content management system. You publish docs using a static site generator rather than a complex publishing system. TWs work with docs as developers work with code, relying on a source control system to track changes in the documentation suite. Adhering to Agile principles, as TWs manage documentation, they write, review, test, merge, build, deploy and iterate.

## What tools support the docs-as-code workflow?

The four main categories of tooling in the workflow are:
* [Source Code Editor](#source-code-editor)
* [Static Site Generator](#static-site-generator)
* [Source Control System](#source-control-system)
* [Collaboration Tool](#collaboration-tool)

### Source Code Editor

Using a source code editor, such as Atom or VS Code, documentation content is written in Markdown, see [Writing Markdown](/docs/contribution_guidelines/writing_markdown/). The editor is designed for managing multiple-document projects, you can easily work with all the relevant files for related images, content, or scripts, without interrupting the workflow. A color-coding feature  ensures both structures and syntax errors are visually distinct, and also integrates the source control system showing the version status of files.

### Static Site Generator

Static site generators (SSG) is similar to a build script which takes in data, content and templates, processes them, and outputs a folder full of all the resultant pages and assets.

### Source Control System

A source control system tracks changes in a set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows. For example, **Git**, a command-line tool, is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

### Collaboration Tool

Teams of developers and TWs generally contribute to **Git** projects. **GitHub** provides hosting for project repositories, access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.  

## Why use the docs-as-code approach?

According to [Write the Docs](https://www.writethedocs.org/), a docs-as-code approach gives you the following benefits:

* Writers integrate better with development teams
* Developers will often write a first draft of documentation
* You can block merging of new features if they do not include documentation, which incentivizes developers to write about features while they are fresh

Read about an sample implementation of the docs-as-code approach in this UK GOV [article](https://technology.blog.gov.uk/2017/08/25/why-we-use-a-docs-as-code-approach-for-technical-documentation/#:~:text=Docs%20as%20code%20means%20applying,and%20a%20content%20management%20system.).

{{% alert title="Note" %}}
[Write the Docs](https://www.writethedocs.org/) is a global community of people who care about documentation. This community publishes many useful resources for TWs using or thinking of adopting the docs-as-code workflow. For example, this podcast provides some useful background on the docs-as-code approach. (https://podcast.writethedocs.org/2017/03/05/episode-4-continuous-integration-and-docs-like-code/)
{{% /alert %}}

References:

* Atom Source Code Editor, https://atom.io/
* Hugo Static Site Generator, https://gohugo.io/
* Git Source Control System, https://git-scm.com/
* GitHub Collaboration Tool, https://en.wikipedia.org/wiki/GitHub
