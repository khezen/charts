# Cheatsheet

## create chart

```bash
helm create mychart
helm package mychart
mv mychart-0.1.0.tgz docs
helm repo index docs --url https://bulklog.github.com/charts
git add -i
git commit -av
git push origin master
```