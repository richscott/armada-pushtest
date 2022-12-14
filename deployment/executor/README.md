# armada-executor

![Version: LATEST](https://img.shields.io/badge/Version-LATEST-informational?style=flat-square) ![AppVersion: LATEST](https://img.shields.io/badge/AppVersion-LATEST-informational?style=flat-square)

A helm chart for armada-executor component

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| additionalLabels | object | `{}` |  |
| applicationConfig.apiConnection.armadaUrl | string | `""` |  |
| customServiceAccount | string | `nil` |  |
| image.repository | string | `"gresearchdev/armada-executor"` |  |
| image.tag | string | `"LATEST"` |  |
| nodeSelector | object | `{}` |  |
| prometheus.enabled | bool | `false` |  |
| prometheus.labels | object | `{}` |  |
| prometheus.scrapeInterval | string | `"10s"` |  |
| resources.limits.cpu | string | `"300m"` |  |
| resources.limits.memory | string | `"1Gi"` |  |
| resources.requests.cpu | string | `"200m"` |  |
| resources.requests.memory | string | `"512Mi"` |  |
| serviceAccount | string | `nil` |  |
| terminationGracePeriodSeconds | int | `5` |  |
| tolerations | list | `[]` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
