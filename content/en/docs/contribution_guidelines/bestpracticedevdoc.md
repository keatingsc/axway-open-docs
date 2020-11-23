---
title: "Best practices for developer documentation"
linkTitle: "Best practices"
weight: 70
date: 2020-03-16
description: >
    Follow these best practices when developing Axway product documentation.
---

## Structure your documentation

It is important to structure your content in an easy-to-navigate manner to retain the interest of your audience. A good structure also improves searchability and discoverability.  

### Navigation structure

To develop a clear visual hierarchy on your website:
* Organise menus by topic.
* Group similar types of content under the same menu.
* Use a maximum of two levels of submenu.

{{% alert title="Note" %}}
Users can land on a page from a search result. In this case, the menu hierarchy can provide context.
{{% /alert %}}

Example:

* [Kubernetes Troubleshooting](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/troubleshooting-kubeadm/)
* [Kong Enterprise Documentation](https://docs.konghq.com/enterprise/)

### Make the documentation discoverable

Documentation should be searchable and easy to find. It is important to ensure documentation visibility on search engines.

Some recommendations for using search engine optimization (SEO) include:
* Create short, unique, and accurate page titles.
* Link the order of menus to the importance of the content.
* Follow the recommendations on [Use meaningful link text](#use-meaningful-link-text) to create link text for URLs.

## Writing documentation

Organise your content in a logical order, including the following sections as a guide.

### Getting started

Introduce your product and describe the first steps users need to complete.

Example:

* [Getting Started with Amazon API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
* [Getting Started with Docker](https://docs.docker.com/get-started/)

### Tutorials

Tutorials lead a reader through a series of steps to complete a defined task.

Example:

* [Create a Tyk On Premise API](https://tyk.io/docs/get-started/with-tyk-on-premise/tutorials/tyk-on-premises-pro/create-api/)
* [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)

### How-to guides

How-to guides help intermediate or experienced users to solve a real-world task using the software.

Example:

* [Tyk Planning for Production](https://tyk.io/docs/deploy-tyk-premise-production/)
* [Assign-memory-resource in Kubernetes](https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/)

### Videos

Videos and screencasts can quickly demonstrate how to complete a task.

## Code samples and scripts

Code samples and downloadable scripts help users get up and running quickly.

### Add code samples

Small snippets of code help users understand a previously explained concept. Snippets can also be used to demonstrate the syntax of attributes or parameters.

Example:

* [Apache Configuration](https://httpd.apache.org/docs/2.4/sections.html)
* [Oracle Create and Deploy Replication Nodes](https://docs.oracle.com/en/database/other-databases/nosql-database/19.5/admin/create-and-deploy-replication-nodes.html)

### Add downloadable scripts

The sample could also be downloadable, which is less error-prone than copying and pasting.

Example:

* [A Sample: Array of JSON Documents](https://docs.oracle.com/en/database/other-databases/nosql-database/19.5/full-text-search/appa-json-array.html).
* [You can find a few example schema files in Autopilot Templates repo on GitHub](https://www.twilio.com/docs/autopilot/twilio-autopilot-cli#schema-files).

### Reference material

Include references to the software’s code, functions, APIs, CLI, and parameters.

Example:

* [Flow variables reference](https://docs.apigee.com/api-platform/reference/variables-reference)
* [Amazon API Gateway Documentation](https://docs.aws.amazon.com/apigateway/index.html)
* [Docker reference documentation](https://docs.docker.com/reference/)
* [Kubernetes reference](https://kubernetes.io/docs/reference/)
* [Oracle Administrator’s Guide](https://docs.oracle.com/en/database/other-databases/nosql-database/19.5/admin/admin-cli-reference.html)

### Glossary

A glossary defines all the terms specific to your company or product.

Example:

* [AWS Glossary](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html)
* [Docker Glossary](https://docs.docker.com/glossary/)

## Writing style

Follow these guidelines to write clear and concise documentation.

### Topic-based writing

Write modular sections of content that cover a specific subject with a singular purpose, for example, a conceptual topic that provides an overview, or a procedural topic that explains how to accomplish a task.

* Write topic-based content that describes how to complete a singular task.
* Group related topics.
* Use the right-side menu to navigate the topics.

### Be minimalist

Find a balance between no documentation and excessive documentation.

* Action-oriented headings (strong, clear verbs)
* Use bullet lists
* Use code snippets
* Use screenshots sparingly
* Use animated gifs

### Use meaningful link text

Write effective link text to help users understand where each link leads.

* Do not paste the URL in the page - this can cause accessibility issues especially for screen readers.
* Do not use **Click here**, as this does not describe the target and negatively impacts SEO.
* Use meaningful words or phrases in the link text for URLs.

### Do not overuse tables

Use tables as quick references. Overly complex tables may be difficult to interpret, so strive for simplicity.

## Review your work

Aim to continuously improve your documentation; include doc reviews in each iteration.

### Version control

Ensure the documentation accurately reflects the functionality of the current release.

### Do not duplicate information

Duplicated content can introduce inconsistencies and increase maintenance overhead. To avoid duplicating content, consider reusing content and referencing.  

## Reference articles

* [Core Practices for Agile/Lean Documentation](http://www.agilemodeling.com/essays/agileDocumentationBestPractices.htm)
* [Chromium Documentation Best Practices](https://chromium.googlesource.com/chromium/src/+/master/docs/documentation_best_practices.md)
* [A Guide to Writing Your First Software Documentation](https://www.sitepoint.com/writing-software-documentation/)
* [Why agile teams should care about documentation](https://techbeacon.com/app-dev-testing/why-agile-teams-should-care-about-documentation)
* [Search Engine Optimization (SEO) Starter Guide](https://support.google.com/webmasters/answer/7451184?hl=en)
* [I'd Rather Be Writing, API glossary](https://idratherbewriting.com/learnapidoc/docapis_glossary_section.html)
* [Developers Google, Link text](https://developers.google.com/style/link-text)
* [Writing effective link text](https://www.webcredible.com/blog/writing-effective-link-text/)
* [DITA Reference topics](https://docs.oasis-open.org/dita/v1.2/os/spec/archSpec/dita_reference_topic.html)
* [Data vs. Layout Tables](https://accessibility.umn.edu/tutorials/data-vs-layout-tables)
