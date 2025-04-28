# my-react-app

Welcome to the TechDocs for my-react-app!

## Overview

Basic React App

## Features
- Basic React App
### Integrates With:
- Github 
- Github CI/CD
- Techdocs
- Kubernetes
- Datadog
- Dependency charts (via catalog-info.yaml)

## Dan's Dev Notes

### Kubernetes
- Can read from different namespaces as long as it is specified in the catalog-info.yaml
- Also can detects multiple pods

### Datadog
- To import a dashboard, ensure that the sharing settings allow the dashboard to be shared
  - Need to state the specific URL-> full path i.e. http://localhost:3000/catalog/default/component/my-react-app/datadog
  - Share the embed url, not the actual datadog webpage url
  
