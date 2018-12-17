# charts
Curated applications for Kubernetes

## How to enable this repository

```
helm repo add khezen https://khezen.github.com/charts
"khezen" has been added to your repositories
```

## create chart

```
helm create mychart
helm package mychart
mv mychart-0.1.0.tgz docs
helm repo index docs --url https://khezen.github.com/charts
git add -i
git commit -av
git push origin master
```