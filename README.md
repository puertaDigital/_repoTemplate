# .github

Default templates and guidelines for puertaDigital.com repositories on GitHub.

## Basic Folder Structure

- **src** Folder: The source code folder! However, in languages that use headers (or if you have a framework for your application) don’t put those files in here.
- **src/doc** Folder: Documentation of code.
- **test** Folder: Unit tests, integration tests… go here.
- **test/doc** Folder: Documentation of tests.
- **.config** Folder: It should local configuration related to setup on local machine.
- **build** Folder: This folder should contain all scripts related to build process (PowerShell, Docker compose…).
- **dep** Folder: This is the directory where all your dependencies should be stored.
- **doc** Folder: The documentation general of project.
- **res** Folder: For all static resources in your project. For example, images.
- **samples** Folder: Providing “Hello World” & Co code that supports the documentation.
- **tools** Folder: Convenience directory for your use. Should contain scripts to automate tasks in the project, for example, build scripts, rename scripts. Usually contains .sh, .cmd files for example.

## Git Special Files

- **.gitignore**: List of blobs for git to ignore. Affects commands like git add and git clean. You may use gitignore.io to generate a clean and useful gitignore file.
- **.gitattributes**: Let’s you define attributes on files (e.g., to change how files look in a diff).
- **.mailmap**: Lets you tell git that duplicate names or emails in the history are actually the same person.
- **.gitmodules**: Let’s you define submodules (subdirectories of your git repository which are checkouts of other git repositories).

## GitHub Special Files & Folders

- **README.md** File: Is a file that answer the What, Why and How of the project. GitHub will recognize and automatically surface the README to repository visitors. Here is an awesome list for more professional readme files.
- **LICENSE** File: Is a file that explains the legal licensing, such as any rights, any restrictions, any regulations, etc.
- **doc/CHANGELOG.md** File: Is a file that describes what's happening in the repo. Version number increases, software updates, bug fixes… are examples of the file’s content.
- **doc/CONTRIBUTORS.md** File: Is a file that lists people who have contributed to the repo.
- **doc/AUTHORS.md** File: Is a file that lists people who are significant authors of the project, such as the people who are legally related to the work.
- **doc/SUPPORT.md** File: Is a file that explains how a reader can get help with the repository. GitHub links this file on the page "New Issue".
- **doc/SECURITY.md** File: Describes your project's security policies, including a list of versions that are currently being maintained with security updates. It also gives instructions on how your users can submit a report of a vulnerability. Fore more details, check the following link.
- **doc/CODE_OF_CONDUCT.md** File: Is a file that explains how to engage in a community and how to address any problems among members of your project's community. Here is some examples.
- **doc/CONTRIBUTING.md** File: Is a file that explains how people should contribute, and that can help verify people are submitting well-formed pull requests and opening useful issues. GitHub links this file on page "New Issue" and the page "New Pull Request". This helps people understand how to contribute.
- **doc/ACKNOWLEDGMENTS.md** File: Is a file that describes related work, such as other projects that are dependencies, or libraries, or modules, or have their own copyrights or licenses that you want to include in your project.
- **doc/CODEOWNERS** File: Is a file that defines individuals or teams that are responsible for code in a repository. Code owners are automatically requested for review when someone opens a pull request that modifies code that they own. When someone with admin or owner permissions has enabled required reviews, they also can optionally require approval from a code owner before the author can merge a pull request in the repository.
- **doc/FUNDING.yml** File: Is a file to raise funding for or support your project.
- **doc/ISSUE_TEMPLATE** Directory: When you add an issue template to your repository, project contributors will automatically see the template’s contents in the issue body. Templates customize and standardize the information you’d like included when contributors open issues. To add multiple issue templates to a repository create an ISSUE_TEMPLATE/ directory in your project root. Within that ISSUE_TEMPLATE/ directory you can create as many issue templates as you need, for example ISSUE_TEMPLATE/bugs.md. This list contains multiple templates for issues and pull requests.
- **doc/PULL_REQUEST_TEMPLATE.md** File: When you add a PULL_REQUEST_TEMPLATE file to your repository, project contributors will automatically see the template's contents in the pull request body. Templates customize and standardize the information you'd like included when contributors create pull requests. You can create a PULL_REQUEST_TEMPLATE/ subdirectory in any of the supported folders to contain multiple pull request templates.

## Overview

This repository contains defaults for:

- Issue templates
  - [`ISSUE_TEMPLATE/bug_report.md`](doc/ISSUE_TEMPLATE/bug_report.md)
  - [`ISSUE_TEMPLATE/feature_request.md`](doc/ISSUE_TEMPLATE/feature_request.md)
- Pull request template
  - [`PULL_REQUEST_TEMPLATE.md`](doc/PULL_REQUEST_TEMPLATE.md)
- Code of Conduct
  - [`CODE_OF_CONDUCT.md`](doc/CODE_OF_CONDUCT.md)
- Contribution guidelines
  - [`CONTRIBUTING.md`](doc/CONTRIBUTING.md)
- Support guidelines
  - [`SUPPORT.md`](doc/SUPPORT.md)
