# okapi-folio-helm - Helm charts modules repository

## Introduction

Okapi and Setae-API FOLIO Helm charts modules repository.

Contains Helm sources and Helm packages repository.
Repository URL https://sul-dlss.github.io/okapi-folio-helm/

gh-pages branch is configured as GitHub pages.

## Creating Helm package from source

Build packages with:
```
  helm package okapi -d ./charts
```
and
```
  helm package setae-api -d ./charts
```

Update repository index
```
  helm repo index . --url https://sul-dlss.github.io/okapi-folio-helm/
```

Commit and push changes to GitHub
