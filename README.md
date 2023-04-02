# puertaDigital dotnet solution template

Default templates and guidelines for puertaDigital.com repositories on GitHub.

## Folder Structure

- **src**: The source code folder! However, in languages that use headers (or if you have a framework for your application) don’t put those files in here.
- **test**: Unit tests, integration tests… go here.
- **.config**: It should local configuration related to setup on local machine.
- **build**: This folder should contain all scripts related to build process (PowerShell, Docker compose…).
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

- **README.md** file: Is a file that answer the What, Why and How of the project. GitHub will recognize and automatically surface the README to repository visitors. Here is an awesome list for more professional readme files.
- **LICENSE** file: Is a file that explains the legal licensing, such as any rights, any restrictions, any regulations, etc.
- **CHANGELOG.md** file: Is a file that describes what's happening in the repo. Version number increases, software updates, bug fixes… are examples of the file’s content.
- **CONTRIBUTORS.md** file: Is a file that lists people who have contributed to the repo.
- **AUTHORS.md** file: Is a file that lists people who are significant authors of the project, such as the people who are legally related to the work.
- **SUPPORT.md** file: Is a file that explains how a reader can get help with the repository. GitHub links this file on the page "New Issue".
- **SECURITY.md** file: Describes your project's security policies, including a list of versions that are currently being maintained with security updates. It also gives instructions on how your users can submit a report of a vulnerability. Fore more details, check the following link.
- **CODE_OF_CONDUCT.md** file: Is a file that explains how to engage in a community and how to address any problems among members of your project's community. Here is some examples.
- **CONTRIBUTING.md** file: Is a file that explains how people should contribute, and that can help verify people are submitting well-formed pull requests and opening useful issues. GitHub links this file on page "New Issue" and the page "New Pull Request". This helps people understand how to contribute.
- **ACKNOWLEDGMENTS.md** file: Is a file that describes related work, such as other projects that are dependencies, or libraries, or modules, or have their own copyrights or licenses that you want to include in your project.
- **.github/CODEOWNERS** file: Is a file that defines individuals or teams that are responsible for code in a repository. Code owners are automatically requested for review when someone opens a pull request that modifies code that they own. When someone with admin or owner permissions has enabled required reviews, they also can optionally require approval from a code owner before the author can merge a pull request in the repository.
- **.github/FUNDING.yml** file: Is a file to raise funding for or support your project.
- **.github/ISSUE_TEMPLATE** directory: When you add an issue template to your repository, project contributors will automatically see the template’s contents in the issue body. Templates customize and standardize the information you’d like included when contributors open issues. To add multiple issue templates to a repository create an ISSUE_TEMPLATE/ directory in your project root. Within that ISSUE_TEMPLATE/ directory you can create as many issue templates as you need, for example ISSUE_TEMPLATE/bugs.md. This list contains multiple templates for issues and pull requests.
- **.github/workflows** directory: GitHub Actions are event-driven, meaning that you can run a series of commands after a specified event has occurred. For example, you can run a set of commands after a pull request is opened, after code is pushed to a branch, or after a release is published. You can also run scheduled commands. For more information, see "Events that trigger workflows."
- **.github/ISSUE_TEMPLATE/bug_report.md** file: Is a file that helps you create a bug report.
- **.github/ISSUE_TEMPLATE/feature_request.md** file: Is a file that helps you create a feature request.
- **.github/PULL_REQUEST_TEMPLATE.md** file: Is a file that helps you create a pull request.

## Reference
### GitHub Repository Structure Best Practices
<https://medium.com/code-factory-berlin/github-repository-structure-best-practices-248e6effc405>
