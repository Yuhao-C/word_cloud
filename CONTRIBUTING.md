# Contributing

To contribute to wordcloud, you'll need to follow the instructions in [Creating a pull request from a fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

In addition to the general procedure for creating a pull request, please follow the following steps:

## Before starting development

### Use a correct version of Python

Python 3.8.x should be fine for development.

```
python --version
> Python 3.8.6
```

### Install all dependencies

```
pip install -U -r requirements.txt -r requirements-dev.txt
pre-commit install
```

### Ensure that tests pass and files are correctly formatted

```
pre-commit run --all-files
```

## Before creating a pull request

### Commit changes

Again make sure that you have installed dependencies properly following the previous section.

When committing, tests and code style checks will run automatically.
You can successfully commit only if your changes pass the tests and style checks.
Otherwise, you will have to fix them before committing.

When writing the commit message, follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) specifications.
Commit messages that do not conform to the specifications will be rejected.

## After submitting the pull requset

After you have submitted the pull requset, CI tasks will fire automatically to check the sytles, lint your code, and run tests on your code (this is to ensure that you do not skip the client side pre-commit tests). In case of any errors, you will be block from merging your PR until the test passes.

After you have passed all CI tests and your PR is proved, you can safely merge your PR. Another CI task will fire automatically to update the changelog, bump the version based on information inferred from your commit message. Then it will release it to the PyPI registry.
