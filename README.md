# Fossorial Kubernetes Helm Charts

<div align="center">
  <a href="https://praxis.causq.com/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CausQ-Networks/praxis/main/public/logo/praxis-logo-white.png">
      <img alt="Praxis Logo" src="https://raw.githubusercontent.com/CausQ-Networks/praxis/main/public/logo/praxis-logo.png" width="280">
    </picture>
  </a>
</div>

[![Discord](https://img.shields.io/discord/1572896060949659679?logo=discord&style=flat-square&label=Discord)](https://praxis.causq.com/discord/)

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/fosrl?style=flat-square)](https://artifacthub.io/packages/search?org=fosrl)
[![Newt Chart Version: 1.3.0](https://img.shields.io/badge/Newt%20Chart-1.3.0-informational?style=flat-square)](https://github.com/CausQ-Networks/praxis-helm/releases)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/license/mit)
![Release Charts](https://github.com/CausQ-Networks/praxis-helm/actions/workflows/helm-ci.yml/badge.svg?branch=main)
[![Releases downloads](https://img.shields.io/github/downloads/fosrl/helm-charts/total.svg?style=flat-square)](https://github.com/CausQ-Networks/praxis-helm/releases)

Welcome to the official repository for **Fossorial Kubernetes Helm Charts**, featuring Helm charts for

- [Praxis](https://github.com/CausQ-Networks/praxis-helm/tree/main/charts/praxis)
- [Newt](https://github.com/CausQ-Networks/praxis-helm/tree/main/charts/newt)
- [Praxis CLI](https://github.com/CausQ-Networks/praxis-helm/tree/main/charts/praxis-cli) (site tunnel via `praxis-cli up site`)

## Installation & Usage

To use these charts, you need [Helm](https://helm.sh/).  
For setup and advanced documentation, visit the official [Helm documentation](https://helm.sh/docs/).

### Add Fossorial Helm Chart Repository

```console
helm repo add fossorial https://charts.fossorial.io

helm repo update fossorial
```

### Explore Available Charts

You can then run `helm search repo fossorial` to see the charts.

### Install a Chart

Example to install the Praxis chart:

```console
helm install my-praxis fossorial/praxis
```

Example to install the Praxis CLI chart:

```console
helm install my-site fossorial/praxis-cli
```

Example to install the older Newt chart:

```console
helm install my-newt fossorial/newt
```

### Uninstall a Chart

Uninstalling a chart can be done with:

```console
helm uninstall my-praxis
```

For more details, please refer to the individual chart READMEs in the `charts/` directory.

## Contributions

Looking for something to contribute? Take a look at issues marked with [help wanted](https://github.com/CausQ-Networks/praxis-helm/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22).

Please see [CONTRIBUTING](./CONTRIBUTING.md) in the repository for guidelines and best practices.

Please post bug reports and other functional issues in the [Issues](https://github.com/CausQ-Networks/praxis-helm/issues) section of the repository.

## Licensing

The charts in this repository are licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
