# Helm Charts

Curated applications for Kubernetes.

Charts are curated application definitions for Helm. For more information about installing and using Helm, see its
[README.md](https://github.com/helm/helm/tree/master/README.md). To get a quick introduction to Charts see this [chart document](https://github.com/helm/helm/blob/master/docs/charts.md).

## How to enable this repository?

```sh
helm repo add khezen https://khezen.github.com/charts
"khezen" has been added to your repositories
```

## How do I install these charts?

```sh
helm install khezen/<chart>
```
For more information on using Helm, refer to the [Helm's documentation](https://github.com/kubernetes/helm#docs).

## Repository Structure

This GitHub repository contains the source for the packaged and versioned charts released at [`https://khezen.github.com/charts`](https://github.com/khezen/charts/tree/master/docs) (the Chart Repository).

The Charts in the master branch of this repository match the latest packaged Chart in the Chart Repository, though there may be previous versions of a Chart available in that Chart Repository.
