# Github Workflow Files

Github workflow files. For CI procedures.

## Features

- Maven tests
- Maven site deployment

## Usage

Use these files as any reusable workflow:

```
jobs:
  tests:
    name: Tests
    uses: Bernardo-MG/github-workflow/.github/workflows/maven/testing.yml@v1
```

## Collaborate

Any kind of help with the project will be well received, and there are two main ways to give such help:

- Reporting errors and asking for extensions through the issues management
- or forking the repository and extending the project

### Issues management

Issues are managed at the GitHub [project issues tracker][issues], where any Github user may report bugs or ask for new features.

### Getting the code

If you wish to fork or modify the code, visit the [GitHub project page][scm], where the latest versions are always kept. Check the 'master' branch for the latest release, and the 'develop' for the current, and stable, development version.

## License

The project has been released under version 2.0 of the [Apache License][license].

[issues]: https://github.com/Bernardo-MG/dice-notation-java/issues
[license]: http://www.apache.org/licenses/LICENSE-2.0
[scm]: http://github.com/Bernardo-MG/dice-notation-java
