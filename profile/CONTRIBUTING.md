# Contributing to this GitHub organization

- [Who can add repositories to this organization?](#who-can-add-repositories-to-this-organization)
- [How to contribute a new repository?](#how-to-contribute-a-new-repository)
- [What kind of repositories can be added to this organization?](#what-kind-of-repositories-can-be-added-to-this-organization)
- [Contributing an example project](#contributing-an-example-project)
  - [README structure](#readme-structure)
  - [Pin major versions in `package.json`](#pin-major-versions-in-packagejson)
- [Contributing a template](#contributing-a-template)
  - [README structure](#readme-structure-1)
  - [Pin major versions in `package.json`](#pin-major-versions-in-packagejson-1)
- [Contributing tooling](#contributing-tooling)
## Who can add repositories to this organization?

Everyone is welcome to add new repositories to this organization as long as the repository adheres to the contribution guidelines (read more below).

## How to contribute a new repository?

If you want to contribute a new repository to this organization, you can reach out to us at [devrel@prisma.io](mailto:devrel@prisma.io) with your suggestion. Please already create the repository beforehand in your own GitHub account and share the link to it as well in the email.

## What kind of repositories can be added to this organization?

We accept all kinds of repositories that are _directly_ related to Prisma, including (but not limited to):

- Example projects
- [Templates](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository) (i.e. starter kits)
- Tooling (such as [middleware](https://www.prisma.io/docs/concepts/components/prisma-client/middleware) packages, [generators](https://www.prisma.io/docs/concepts/components/prisma-schema/generators#community-generators), and utitilies from the Prisma ecosystem)

If your repository doesn't fit into any of these predefined categories, you can still suggest to for it to be added by [reaching out to us](mailto:devrel@prisma.io).

## Contributing an example project

This section explains the best pactices for contributing example projects. 

### README structure

The README of an example project should contain the following sections (as `h2` headings, i.e. `##` in Markdown):

- **Overview**: Describe what the example project is about. If your example project is related to a tutorial, workshop or another kind of educational resource, crosslink that tutorial in this section).
- **Technologies**: List the technologies/frameworks/libraries that are used in the project and describe what their purpose is.
- **Setup**: Provide clear _step-by-step_ instructions for the reader to run the example project. It is very important that the example project should _just work_ when following the instructions precisely. Provide deployment instructions if applicable. 
- **Usage**:
  - If your example project is a **server-side app**, provide instructions for how to use the API (e.g. sample API calls to a REST API route or a GraphQL query) that's easy to replicate for the reader.
  - If your example is a **fullstack app**, include a screenshot of the UI and (optionally) describe some of the user flows of the app.
- **Author**: Include a section where you briefly introduce yourself and let readers know how they can reach you.

These sections are required. Feel free to include any additional sections that are specific to your repository as you see fit.

### Pin major versions in `package.json`

Example projects often get out of date and break when they depend on libraries that see major version updates with breaking changes.

We believe it's more important for an example project to be functional than to be always up-to-date. To avoid the examples breaking, we ask you to pin the major versions of your npm packages in the project.

## Contributing a template

This section explains the best practices for contributing [templates](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository). Templates allow developers to generate new repositories with the same directory structure, branches, and files.
### README structure

The README of a template should contain the following sections (as `h2` headings, i.e. `##` in Markdown):

- **Overview**: Describe what the template is about.
- **Technologies**: List the technologies/frameworks/libraries that are used in the template and describe what their purpose is.
- **Setup**: Provide clear _step-by-step_ instructions for the reader to get started with the template.
- **Usage**:
  - If your Template is a **server-side app**, provide instructions for how to use the API (e.g. sample API calls to a REST API route or a GraphQL query) that's easy to replicate for the reader.
  - If your example is a **fullstack app**, include a screenshot of the UI and (optionally) describe some of the user flows of the app.
- **Author**: Include a section where you briefly introduce yourself and let readers know how they can reach you.

### Pin major versions in `package.json`

Templates often get out of date and break when they depend on libraries that see major version updates with breaking changes.

We believe it's more important for a template to be functional than to be always up-to-date. To avoid the examples breaking, we ask you to pin the major versions of your npm packages in the project.

## Contributing tooling

This section explains the best practices for adding tooling, such as [middleware](https://www.prisma.io/docs/concepts/components/prisma-client/middleware) packages, [generators](https://www.prisma.io/docs/concepts/components/prisma-schema/generators#community-generators), and utitilies from the Prisma ecosystem).

### README structure

The README of a tool should contain the following sections (as `h2` headings, i.e. `##` in Markdown):

- **Overview**: Describe what the tool is about.
- **Features**: List the features this tool has.
- **Installation**: Explain how to install the tool. This section should include any other relevant information (e.g. specific configurations) that is required to use the tool.
- **Documentation**: Document the tool. 
  - If the tool is a **library**, describe how the library can be used, include an API reference and provide usage examples.  
  - If the tool is a **CLI**, document all CLI commands, their options and provide usage examples.
- **Author**: Include a section where you briefly introduce yourself and let readers know how they can reach you.
