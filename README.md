<h1 align="center">BRiX - A better Boilerplate</h1>

<p align="center">
  A straight-forward starting point for building a great website on the HubSpot CMS.
</p>

<p align="center">
  <a href="https://support.inboundlabs.co/en/the-brix-framework">Documentation</a> | 
  <a href="https://www.gobrix.io/">BRiX dashboard</a> | 
  <a href="https://boilerplate.gobrix.io/">Demo website</a>
</p>

## Purpose

The [BRiX - A better Boilerplate](https://support.inboundlabs.co/en/the-brix-framework) is designed to offer developers a head start in the website building process. While the boilerplate represents HubSpot's opinionated best practices, we intend to learn from similar projects and feedback. We hope it offers inspiration and utility for all website projects!

Follow and star the repository to stay up-to-date with product releases and evolving best practices for building websites on the HubSpot CMS.

## Getting started

The BRiX - A better Boilerplate is designed to work with both [local development](https://designers.hubspot.com/docs/tools/local-development) and the HubSpot Design Tools. Before getting started, you will need to have [Node.js](https://nodejs.org) installed and we strongly suggest that you set up a [HubSpot CMS Developer Sandbox](https://offers.hubspot.com/free-cms-developer-sandbox).

### To download the BRiX - A better Boilerplate using the HubSpot CMS CLI:

1. Navigate to the directory that you want to use for your project
2. Run `hs create website-theme <directory>` to create a project from the BRiX - A better Boilerplate
3. Create a `hubspot.config.yml` file and [configure](https://designers.hubspot.com/tutorials/getting-started-with-local-development#2-set-up-your-configuration-file) the CLI so that you can upload files to the HubSpot portals that you want to use
4. Run `hs upload --portal=<portal> <src> <dest>` to upload all of the files in the boilerplate.
5. Run `hs watch --portal=<portal> src <directory>` to [watch for changes](https://designers.hubspot.com/docs/tools/local-development-reference#watch) to files in the `src` directory, and upload any that have saved changes.

Please reference _[Quick start guide to developing on the HubSpot CMS](https://designers.hubspot.com/tutorials/getting-started#1-install-the-hubspot-cms-cli)_ and _[Getting started with local development](https://designers.hubspot.com/tutorials/getting-started-with-local-development)_ articles for more information.

### To use version control in your project using GitHub and GitHub Actions:

1. [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) the BRiX - A better Boilerplate repository and [clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) your forked repository to your computer
2. [Set up GitHub secrets in your forked repository to encrypt sensitive information from showing publically](https://help.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets) for `HUBSPOT_PORTAL_ID` and `HUBSPOT_PERSONAL_ACCESS_KEY`
3. Update the name of the directory that you'll be deploying to in your Design Manager in the `.github/workflows/deploy.yml` file (the current default `dest_dir` is `cms-theme-boilerplate`)
4. Deploy changes to your Design Manager by pushing to the `master` branch of your forked repository

Please reference [_HubSpot CMS deploy GitHub action page_](https://github.com/marketplace/actions/hubspot-cms-deploy) and _[Setting up continuous integration with a GitHub repository using GitHub Actions article](https://designers.hubspot.com/tutorials/github-integration)_ for more information.

## Style guide

For details about the BRiX - A better Boilerplate's recommended best practices and code formatting, please reference [style guide](https://github.com/HubSpot/cms-theme-boilerplate/blob/master/STYLEGUIDE.md).

## Community

You can stay up to date with BRiX - A better Boilerplate updates and discussions in the [BRiX Framework Slack](https://support.inboundlabs.co/en/your-support-options-for-brix-framework).
