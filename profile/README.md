<p style="color: white; border-width: 3px; border-radius: 30px; padding: 15px;">
🌹 generic-infrastructure
</p>

*foss templates*

## source

| project            | type       | quality         | status          |
|--------------------|------------|-----------------|-----------------|
| [devops]           | terragrunt | ❗ experimental  | ⚠️ in progress  |
| [minikube-cluster] | terraform  | ❗ experimental  | ⚠️ in progress  |
| [doks-cluster]     | terraform  | ❗ experimental  | ⚠️ in progress  |
| [eks-cluster]      | terraform  | ❗ experimental  | ⚠️ in progress  |
| [gke-cluster]      | terraform  | ❗ experimental  | ⚠️ in progress  |
| [aks-cluster]      | terraform  | ❗ experimental  | ⚠️ in progress  |
| [helm-aoa]         | helm       | ❗ experimental  | ⚠️ in progress  |
| [helm-internal]    | helm       | ❗ experimental  | ⚠️ in progress  |
| [fastapi-app]      | python     | ❗ experimental  | ⚠️ in progress  |

## stack

| level     | project                                                                                  |
|-----------|------------------------------------------------------------------------------------------|
| ci/cd     | [terragrunt], [terraform], [helm], [kustomize], [argo-cd]                                |
| engines   | [minikube], [doks], [eks], [gke], [aks]                                                  |
| issuers   | [cert-manager] ([selfsigned], [acme])                                                    |
| networks  | [istio], [kiali], [knative]                                                              |
| events    | [strimzi] ([zookeeper], [kafka])                                                         |
| databases | [postgres], [redis], [minio]                                                             |
| etc       | [kube-prometheus] ([grafana], [prometheus], [alertmanager]), [loki], [promtail], [tempo] |
| python    | [fastapi]                                                                                |

[//]: # (generic-infrastructure)
[devops]: https://github.com/generic-infrastructure/devops
[minikube-cluster]: https://github.com/generic-infrastructure/minikube-cluster
[doks-cluster]: https://github.com/generic-infrastructure/doks-cluster
[eks-cluster]: https://github.com/generic-infrastructure/eks-cluster
[gke-cluster]: https://github.com/generic-infrastructure/gke-cluster
[aks-cluster]: https://github.com/generic-infrastructure/aks-cluster
[helm-aoa]: https://github.com/generic-infrastructure/helm-aoa
[helm-internal]: https://github.com/generic-infrastructure/helm-internal
[fastapi-app]: https://github.com/generic-infrastructure/fastapi-app
[whitepaper]: https://github.com/generic-infrastructure/whitepaper

[//]: # (ci/cd)
[terragrunt]: https://terragrunt.gruntwork.io/
[terraform]: https://www.terraform.io/
[helm]: https://helm.sh/
[kustomize]: https://kustomize.io/
[argo-cd]: https://argoproj.github.io/cd/

[//]: # (engines)
[minikube]: https://minikube.sigs.k8s.io/docs/
[aks]: https://learn.microsoft.com/en-us/azure/aks/
[doks]: https://docs.digitalocean.com/products/kubernetes/
[eks]: https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html
[gke]: https://cloud.google.com/kubernetes-engine/

[//]: # (issuers)
[cert-manager]: https://cert-manager.io/
[selfsigned]: https://cert-manager.io/docs/configuration/selfsigned/
[acme]: https://cert-manager.io/docs/configuration/acme/

[//]: # (networks)
[istio]: https://istio.io/
[kiali]: https://kiali.io/
[knative]: https://knative.dev/docs/

[//]: # (events)
[strimzi]: https://strimzi.io/
[zookeeper]: https://zookeeper.apache.org/
[kafka]: https://kafka.apache.org/

[//]: # (databases)
[postgres]: https://www.postgresql.org/
[redis]: https://redis.io/
[minio]: https://min.io/

[//]: # (etc)
[kube-prometheus]: https://prometheus-operator.dev/
[grafana]: https://grafana.com/
[prometheus]: https://prometheus.io/
[alertmanager]: https://prometheus.io/docs/alerting/latest/alertmanager/
[loki]: https://grafana.com/oss/loki/
[promtail]: https://grafana.com/docs/loki/latest/clients/promtail/
[tempo]: https://grafana.com/docs/tempo/latest/

[//]: # (apps)
[fastapi]: https://fastapi.tiangolo.com/