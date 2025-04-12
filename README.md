<!--
SPDX-FileCopyrightText: 2025-present Stuart Ellis <stuart@stuartellis.name>

SPDX-License-Identifier: MIT
-->

# copier-sve-baseline

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit) [![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier) [![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

This [Copier](https://copier.readthedocs.io/en/stable/) template provides files that are useful for any software project.

The files in this template enable these tools:

- [EditorConfig](https://EditorConfig.org)
- [Prettier](https://prettier.io/)
- [REUSE](https://reuse.software/)

The template is used to maintain files in this project itself, as well as other projects.

## Install

You need [Copier](https://copier.readthedocs.io/en/stable/) to use template for a project. Use [uv](https://docs.astral.sh/uv/) or [pipx](https://pipx.pypa.io/) to run Copier. These tools enable you to use Copier without installing it.

You can either create a new project with this template or add the template to an existing project. Use the same _copy_ sub-command of Copier for both cases. Run Copier with the _uvx_ or _pipx run_ commands, which download and cache software packages as needed. For example:

```shell
uvx copier copy git+https://github.com/stuartellis/copier-sve-baseline my-project
```

## Usage

This template provides files that are required by other tools. These tools may be called by text editors, pre-commit hooks and continuous integration. This template does not specify or limit how the tools will be used.

### Updating Projects

To update a project again with a new version of this template, run these commands:

```shell
cd your-project-name
copier update -a .copier-answers-baseline.yaml .
```

## Contributing

This project was built for my personal use. I will consider suggestions and Pull Requests, but I may decline anything that makes it less useful for my needs. You are welcome to fork this project.

## License

MIT © 2025 Stuart Ellis
