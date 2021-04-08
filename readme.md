# Atlantis with Terragrunt

This is a custom docker image based off of the Atlantis container:
<https://hub.docker.com/r/runatlantis/atlantis>

## Supported Atlantis tags/versions

Currently only support the version of the Atlantis container that is used in their helm chart:
<https://github.com/runatlantis/helm-charts/blob/main/charts/atlantis/values.yaml>

```yaml
## -------------------------- ##
# Default values for atlantis (override as needed).
## -------------------------- ##

image:
  repository: runatlantis/atlantis
  tag: v0.16.1
  pullPolicy: IfNotPresent
```

## Contributors

All contributors welcome!
