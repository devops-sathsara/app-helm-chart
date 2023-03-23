# CI/CD Best Practices for Helm Charts

*This repository contains a GitHub Actions pipeline that incorporates some best practices for managing Helm charts.*

## Features

* Lint and validate chart with [Chart Testing CLI](https://github.com/helm/chart-testing)
* Install and test a chart on a [Kind](https://kind.sigs.k8s.io/) cluster
* Package and release chart through GitHub pages


