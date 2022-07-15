# Contributing to this GitHub organization

## Who can add repositories to this organization?

Everyone is welcome to add new repositories to this organization as long as the repository adheres to the contribution guidelines (read more below).

## How to contribute a new repository?

If you want to contribute a new repository to this organization, you can reach out to us at [devrel@prisma.io](mailto:devrel@prisma.io) with your suggestion. Please already create the repository beforehand in your own GitHub account and share the link to it as well in the email.

## What kind of repositories can be added to this organization?

We accept all kinds of repositories that are _directly_ related to Prisma, including (but not limited to):

- Example projects
- [Templates](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository) / Starter kits
- Tooling (such as [middleware]() packages, [generators](), and utitilies from the Prisma ecosystem)

If your repository doesn't fit into any of these predefined categories, you can still suggest to for it to be added by [reaching out to us](mailto:devrel@prisma.io).

## Contributing an example project

This section explains the best pactices for contributing example projects.

### README structure

The README of an example project should contain the following sections (as `h2` headings, i.e. `##` in Markdown):

- **Overview**: Describe what the example project is about. If your example project is related to a tutorial, workshop or another kind of educational resource, crosslink that tutorial in this section).
- **Technologies**: List the technologies/frameworks/libraries that are used in the project and what their purpose is.
- **Setup**: Provide clear _step-by-step_ instructions for the reader to run the example project.
- **Usage**:
  - If your example project is a **server-side app**, provide instructions for how to use the API (e.g. sample API calls to a REST API route or a GraphQL query) that's easy to replicate for the reader.
  - If your example is a **fullstack app**, include a screenshot of the UI and (optionally) describe some of the user flows of the app.
- **Author**: Include a section where you briefly introduce yourself and let readers know how they can reach you.

### Pin major versions in `package.json`

Example projects often get out of date and break when they depend on libraries that see major version updates with breaking changes.

We believe it's more important for an example project to be functional than to be always up-to-date. To avoid the examples breaking, we ask you to pin the major versions of your npm packages in the project. 



