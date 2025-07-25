# argo-workflows

![Version: 1.0.7](https://img.shields.io/badge/Version-1.0.7-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1](https://img.shields.io/badge/AppVersion-1-informational?style=flat-square)

Argo Workflows is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes.

**Homepage:** <https://argoproj.github.io/argo-workflows/>

## Source Code

* <https://github.com/InseeFrLab/helm-charts-automation/tree/master/charts/argo-workflows>

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://argoproj.github.io/argo-helm | argo-workflows | 0.45.19 |
| https://inseefrlab.github.io/helm-charts-interactive-services | library-chart | 1.7.5 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| argo-workflows.controller.clusterWorkflowTemplates.enabled | bool | `false` |  |
| argo-workflows.controller.replicas | int | `1` |  |
| argo-workflows.controller.resources.limits.cpu | string | `"2000m"` |  |
| argo-workflows.controller.resources.limits.memory | string | `"2000Mi"` |  |
| argo-workflows.controller.resources.requests.cpu | string | `"100m"` |  |
| argo-workflows.controller.resources.requests.memory | string | `"200Mi"` |  |
| argo-workflows.controller.workflowNamespaces | list | `[]` |  |
| argo-workflows.crds.install | bool | `false` |  |
| argo-workflows.createAggregateRoles | bool | `false` |  |
| argo-workflows.server.clusterWorkflowTemplates.enabled | bool | `false` |  |
| argo-workflows.server.enabled | bool | `true` |  |
| argo-workflows.server.extraArgs[0] | string | `"--auth-mode=server"` |  |
| argo-workflows.server.ingress.enabled | bool | `false` |  |
| argo-workflows.server.resources.limits.cpu | string | `"2000m"` |  |
| argo-workflows.server.resources.limits.memory | string | `"2000Mi"` |  |
| argo-workflows.server.resources.requests.cpu | string | `"100m"` |  |
| argo-workflows.server.resources.requests.memory | string | `"200Mi"` |  |
| argo-workflows.singleNamespace | bool | `true` |  |
| argo-workflows.workflow.serviceAccount.annotations | object | `{}` |  |
| argo-workflows.workflow.serviceAccount.create | bool | `true` |  |
| argo-workflows.workflow.serviceAccount.name | string | `"argo-workflows"` |  |
| ingress.annotations | list | `[]` |  |
| ingress.certManagerClusterIssuer | string | `""` |  |
| ingress.enabled | bool | `true` |  |
| ingress.hostname | string | `"chart-example.local"` |  |
| ingress.ingressClassName | string | `""` |  |
| ingress.tls | bool | `true` |  |
| ingress.useCertManager | bool | `false` |  |
| route.annotations | list | `[]` |  |
| route.enabled | bool | `false` |  |
| route.hostname | string | `"chart-example.local"` |  |
| route.tls.termination | string | `"edge"` |  |
| route.wildcardPolicy | string | `"None"` |  |
| security.allowlist.enabled | bool | `true` |  |
| security.allowlist.ip | string | `"0.0.0.0/0"` |  |
| security.networkPolicy.enabled | bool | `true` |  |
| security.networkPolicy.from | list | `[]` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `"workflow"` |  |
| serviceAccount.role | string | `"workflow"` |  |
| serviceAccount.roleBinding | string | `"workflow"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
