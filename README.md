<div align="center">

<!--- FIXME: Pick an emoji and name your project! --->
# `😊 template-opensource-contributor-guide`

<!--- FIXME: Write short catchy description/tagline of project --->
**Template for creating new source repositories that follow the source guidelines**

<!--- FIXME: Update crate, repo and CI workflow names here! Remove any that are not relevant --->

[![dependency-review](https://github.com/bridgewwater/template-opensource-contributor-guide/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/bridgewwater/template-opensource-contributor-guide/actions/workflows/dependency-review.yml)
[![license](https://img.shields.io/github/license/bridgewwater/template-opensource-contributor-guide)](https://github.com/bridgewwater/template-opensource-contributor-guide)
[![GitHub contributors](https://img.shields.io/github/contributors/bridgewwater/template-opensource-contributor-guide)](https://github.com/bridgewwater/template-opensource-contributor-guide)
[![github release](https://img.shields.io/github/v/release/bridgewwater/template-opensource-contributor-guide?style=social)](https://github.com/bridgewwater/template-opensource-contributor-guide/releases)

</div>

<!--- FIXME: check this finish then remove --->

<!--- FIXME: check this finish then remove --->
## TEMPLATE INSTRUCTIONS

1. Create a new repository using this template.
   - [ ] replace `github.com` if change git server.
   - [ ] replace `bridgewwater` to new group.
   - [ ] replace `template-opensource-contributor-guide` to new registry.
2. **Title:** Change the first line of this README to the name of your project, and replace the sunflower with an emoji that represents your project. 🚨 Your emoji selection is critical.
3. **Badges:** In the badges section above, change the repo name in each URL. If you are creating something other than a Rust crate, remove the crates.io and docs badges (and feel free to add more appropriate ones for your language).
4. **CI:** In `.drone.yml`. And go over it and adapt it to work for your project
    - If you aren't using or customized the CI workflow, also see the TODO in `.mergify.yml`
    - If you want to use the automatic rustdoc publishing to github pages for git main, add by yourself.
5. **Issue & PR Templates**: Review the files in `.github/ISSUE_TEMPLATE` and `.github/pull_request_template`. Adapt them
to suit your needs, removing or re-wording any sections that don't make sense for your use case.
1. **CHANGELOG.md:** Change the `$REPO_NAME` in the links at the bottom to the name of the repository, and replace the example template lines with the actual notes for the repository/crate.
2. **Cleanup:** Remove this section of the README and any unused files (such as configs for other languages) from the repo.

<!--- FIXME: read this then remove --->

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/contributor%20covenant-v1.4-ff69b4.svg)](.github/CODE_OF_CONDUCT.md)

We welcome community contributions to this project.

Please read [Contributor Guide](.github/CONTRIBUTING_DOC/CONTRIBUTING.md) for more information on how to get started.

## Feature

- [...]

## usage

- [...]