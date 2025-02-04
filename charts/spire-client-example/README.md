# spire-client-example

<!-- This README.md is generated. -->

> **:exclamation: This Helm Chart is deprecated!**

![Version: 0.2.1](https://img.shields.io/badge/Version-0.2.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.12.2](https://img.shields.io/badge/AppVersion-0.12.2-informational?style=flat-square)

A Helm chart for deploying a spire workload as example.

**Homepage:** <https://github.com/philips-labs/helm-charts/charts/spire-client-example>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| marcofranssen | marco.franssen@philips.com | https://marcofranssen.nl |

## Source Code

* <https://github.com/philips-labs/helm-charts/charts/spire-client-example>

## Requirements

Kubernetes: `>=1.19.0-0`

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| autoscaling.enabled | bool | `false` |  |
| autoscaling.maxReplicas | int | `100` |  |
| autoscaling.minReplicas | int | `1` |  |
| autoscaling.targetCPUUtilizationPercentage | int | `80` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"gcr.io/spiffe-io/spire-agent"` |  |
| image.tag | string | `""` |  |
| imagePullSecrets | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podAnnotations | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| securityContext | object | `{}` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| spire.namespace | string | `"spire"` |  |
| spire.releaseName | string | `"spire-server"` |  |
| tolerations | list | `[]` |  |
