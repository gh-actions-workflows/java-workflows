# Java Workflows

Workflows for your Java code.

## How to use?

```yaml
name: Java Workflow
on: [push]

jobs:
  maven:
    uses: gh-actions-workflows/java-workflows/.github/workflows/maven.yaml@master
    with:
      java-version: 17

```

For more details on how it works, see the file: [maven.yaml](https://github.com/gh-actions-workflows/java-workflows/blob/master/.github/workflows/maven.yaml).
