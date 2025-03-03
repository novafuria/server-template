# template-base <!-- omit in toc -->

***A template with the minimal features to start any repository in Novafuria***

<div align="center">

&nbsp;

[![License: NIL](https://img.shields.io/badge/License-Private-yellow.svg)](./LICENSE)
[![Contributor covenant: 2.1](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./CODE_OF_CONDUCT.md)
[![Semantic Versioning: 2.0.0](https://img.shields.io/badge/Semantic--Versioning-2.0.0-a05f79?logo=semantic-release&logoColor=f97ff0)](https://semver.org/)

[![Labeling](https://github.com/novafuria/template-base/actions/workflows/labeling.yml/badge.svg)](https://github.com/novafuria/template-base/actions/workflows/labeling.yml)
[![Liberation](https://github.com/novafuria/template-base/actions/workflows/liberation.yml/badge.svg)](https://github.com/novafuria/template-base/actions/workflows/liberation.yml)
[![Project Automation](https://github.com/novafuria/template-base/actions/workflows/project-automation.yml/badge.svg)](https://github.com/novafuria/template-base/actions/workflows/project-automation.yml)

[Bug Report](./issues/new?assignees=&labels=bug%2Clifecycle%2Fneeds-triage&projects=novafuria%2F7&template=1-bug-report.yml&title=...+is+broken)
⭕
[Feature Request](./issues/new?assignees=&labels=enhancement%2Clifecycle%2Fneeds-triage&projects=novafuria%2F7&template=2-feature-request.yml&title=As+a+%5Btype+of+user%5D%2C+I+want+%5Ba+goal%5D+so+that+%5Bbenefit%5D)
⭕
[Help Wanted](./issues/new?assignees=&labels=help+wanted%2Clifecycle%2Fneeds-triage&projects=novafuria%2F7&template=3-help-wanted.yml&title=I+need+help+with...)

&nbsp;

</div>

## Table of Contents <!-- omit in toc -->

- [👋 Introduction](#-introduction)
- [🚀 Usage](#-usage)
- [🔥 Upcoming soon](#-upcoming-soon)
- [🤝 Contributing](#-contributing)
- [🔖 Versioning](#-versioning)
- [⚖️ License](#️-license)
- [📜 Code of conduct](#-code-of-conduct)

## 👋 Introduction

> [!NOTE]
> Replace this text with an engaging introduction for your project.

This is a template with the minimal features to start any repository in Novafuria.

> [!IMPORTANT]
> If you want start a coding project, documentation repository, or any other kind of project, please check the other templates available in Novafuria before using this one.

Is recommended to use in:

- **Scripts**: For scripts that automate tasks with bash or powershell.
- **Isolated projects**: For projects that don't need a specific template.
- **Anything that requires versioning**: For projects that need to be versioned.

## 🚀 Usage

> [!NOTE]
> Here you should explain how to use your project. You can include examples, screenshots, and any other information that can help users to understand how to use your project.

Some files are included in this template to help you to start your project:

- `.github/workflows`: Contains the workflows to automate the project.
- `.github/ISSUE_TEMPLATE`: Contains the templates to create issues.
- `CODE_OF_CONDUCT.md`: Contains the code of conduct for the project.
- `CONTRIBUTING.md`: Contains the guidelines for contributing to the project.
- `LICENSE`: Contains the license used on Novafuria for privates projects.
- `README.md`: Contains the information about the project.

To perform the initial setup of the project, you can follow these steps:

- [ ] **RENAME** the title and all mentions of `base-template` with the name of your project.
- [ ] **CHANGE** the value of key `type: devops|gamedev|agro` in ISSUE_TEMPLATE files to the correct project type.
- [ ] **REVIEW** if is needed update:
  - [ ] `CODE_OF_CONDUCT.md`
  - [ ] `CONTRIBUTING.md`
  - [ ] `LICENSE`
  - [ ] `.github/CODEOWNERS`
  - [ ] `.github/release.yml`
  - [ ] `.github/pull_request_template.md`
  - [ ] `.github/ISSUE_TEMPLATE/*.md`
  - [ ] `.github/workflows/*.yml`
- [ ] **UPDATE** the correct sections of the README.

## 🔥 Upcoming soon

> [!NOTE]
> Here you can announce some features you plan to work on.

## 🤝 Contributing

Any kind of positive contribution is welcome! Please help us to grow by contributing to the project.

If you wish to contribute, you can work on any issue or create one on your own. After adding your code, please send us a Pull Request.

Please read [CONTRIBUTING](CONTRIBUTING.md) file for details on our `CODE OF CONDUCT`, and the process for submitting pull requests to us.

## 🔖 Versioning

This project uses [SemVer](https://semver.org/) for versioning. For the versions available, see the tags on this repository.

The repository also contains a versioning workflow that will automatically generate a new release when a pull request is merged into the main branch.

You can find the versioning workflow in `.github/workflows/versioning.yml`.

Remember update the workflow with spteps needed to generate a new release.

## ⚖️ License

This project is licensed under the `NIL License version 1`, a private license. See the [LICENSE](LICENSE) file for details.

## 📜 Code of conduct

This project is governed by the Contributor Covenant version 2.1. See the [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) file for details.
