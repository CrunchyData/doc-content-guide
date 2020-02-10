---
title: "Writing READMEs"
draft: false
weight: 8
---

A README is a single file (typically .txt, or .md) that introduces the reader to the project repository and source code.

Like user guides, a README informs the reader what a project is for and how to use it. That said, the target audience for READMEs is more specific: developers (both on your project's team as well as outside), and potentially other end users who are comfortable with code. READMEs can also contain additional information that doesn't necessarily belong in a user guide, such as acknowledgements, licensing, etc.

## Guidelines

### Help the reader identify the project

- At the top of the README, make sure the project's name is the first heading.
- Add a URL for the project (e.g. a product landing page).
- Identify the owner/s or author/s of the project.

### Help the reader evaluate the project

Provide a description that focuses on the *why*:

- What is this project?
- How does it work?
- Who will find it useful, and why? 
    - What differentiates your project from alternatives?
    - What is this project *not* good for?

With that said, you might also include (after addressing the above!):

- languages and tools used
- the project's status and progress (e.g. beta, deprecated)

When relevant, indicate under what terms the project may be used. Name and link to the license or other appropriate document.

### Help the reader use the project

- What are the requirements? (e.g. hardware, OS, tooling, other dependencies)
- List the specific steps to install and use the project for the first time.
    - Extended instructions for day-to-day usage should go in a user guide and other dedicated docs.
- Include examples and expected output. Assuming that the README will not be the only available documentation for the project, it is more helpful to include the "smallest" examples of usage, then provide links to docs containing longer and more detailed examples. This also applies to troubleshooting.

### Help the reader engage with the project

- Tell the reader where to go for additional documentation. This can include help commands, tutorials, and top-level README companion files such as `LICENSE`, `CONTRIBUTING`, `CHANGELOG`, etc.
    - Include a brief description of each, in addition to the link.
- Tell the reader where to go for help. This includes issue trackers, forums, our Support team (available for paying customers), etc.
- Tell the reader how they can help. This includes linking to and summarizing a contributor's guide, GitHub pull requests, channels for reporting issues and bugs, etc.

It might also be a good idea to include a quick roadmap or list ideas for future enhancements or releases.

## Examples

Here are some examples that you could check out for reference:

- Make a README [template](https://www.makeareadme.com/#template-1)
- Extensive list on the Awesome README [repo](https://github.com/matiassingers/awesome-readme)

## Final Notes

- Developers are the target audience here, but remember that they can still be unfamiliar with most aspects of this project. 
- If your README is long and contains several large sections, consider adding a table of contents at the beginning.

## Acknowledgement

These guidelines are adapted from Daniel D. Beck's [README Checklist](https://github.com/ddbeck/readme-checklist/blob/master/checklist.md).
