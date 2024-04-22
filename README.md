# Java Workflows

Workflows para o seu código Java.

## Como utilizar?

```yaml
name: Java Workflow
on: [push]

jobs:
  maven:
    uses: gh-actions-workflows/java-workflows/.github/workflows/maven.yaml@master
    with:
      java-version: 17

```

Para mais detalhes sobre o funcionamento consulte o arquivo: [maven.yaml](https://github.com/gh-actions-workflows/java-workflows/blob/master/.github/workflows/maven.yaml).
