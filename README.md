## Installation

Install cookiecutter using pip package manager:

```bash
# pipx is strongly recommended.
pipx install cookiecutter
```

### Quick Start

**Use a GitHub template**

```bash
# You'll be prompted to enter values.
# Then it'll create your Python package in the current working directory,
# based on those values.
# For the sake of brevity, repos on GitHub can just use the 'gh' prefix
$ pipx run cookiecutter gh:audreyfeldroy/cookiecutter-pypackage
```

**Use a local template**

```bash
$ pipx run cookiecutter cookiecutter-pypackage/
```
