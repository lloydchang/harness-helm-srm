## Harness CET Chart

A Helm chart for CET

![Version: 0.7.0](https://img.shields.io/badge/Version-0.7.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

## Usage

Use the following dependency to add this chart repository to your Helm installation:

```
dependencies:
    - name: cet
      repository: https://harness.github.io/helm-srm
      version: 0.7.0
```

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| enable-receivers | bool | `false` |  |
| et-collector.autoscaling.enabled | bool | `false` |  |
| et-collector.image.tag | string | `"5.14.0"` |  |
| et-receiver-agent.image.tag | string | `"5.14.2"` |  |
| et-receiver-decompile.image.tag | string | `"5.14.2"` |  |
| et-receiver-hit.image.tag | string | `"5.14.2"` |  |
| et-receiver-sql.image.tag | string | `"5.14.2"` |  |
| et-service.autoscaling.enabled | bool | `false` |  |
| et-service.image.tag | string | `"5.14.2"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)