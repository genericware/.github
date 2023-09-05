<p style="color: white; border-width: 3px; border-radius: 30px; padding: 15px;">
🌹 <i>generic-infrastructure</i>
</p>

*free and open source templates*

## source

| project            | quality        | status         |
|--------------------|----------------|----------------|
| [devops]           | ❗ experimental | ⚠️ in progress |
| [minikube-cluster] | ❗ experimental | ⚠️ in progress |
| [doks-cluster]     | ❗ experimental | ⚠️ in progress |
| [eks-cluster]      | ❗ experimental | ⚠️ in progress |
| [gke-cluster]      | ❗ experimental | ⚠️ in progress |
| [aks-cluster]      | ❗ experimental | ⚠️ in progress |
| [helm-aoa]         | ❗ experimental | ⚠️ in progress |
| [helm-internal]    | ❗ experimental | ⚠️ in progress |
| [fastapi-app]      | ❗ experimental | ⚠️ in progress |

## stack

| level                                           | project                                                                                            |
|-------------------------------------------------|----------------------------------------------------------------------------------------------------|
| ci/cd                                           | [terragrunt], [terraform], [helm], [kustomize], [argo-cd]                                          |
| engines                                         | [minikube], [doks], [eks], [gke], [aks]                                                            |
| issuers                                         | [cert-manager] ([selfsigned], [acme])                                                              |
| networks                                        | [istio], [kiali], [knative]                                                                        |
| events                                          | [strimzi] ([zookeeper], [kafka])                                                                   |
| storage                                         | [postgres], [redis], [minio]                                                                       |
| graphs, metrics, alerts <br/> logs <br/> traces | [kube-prometheus] ([grafana], [prometheus], [alertmanager]) <br/> [loki], [promtail] <br/> [tempo] |
| apps                                            | [fastapi-app]                                                                                      |

[devops]: https://github.com/generic-infrastructure/devops
[minikube-cluster]: https://github.com/generic-infrastructure/minikube-cluster
[doks-cluster]: https://github.com/generic-infrastructure/doks-cluster
[eks-cluster]: https://github.com/generic-infrastructure/eks-cluster
[gke-cluster]: https://github.com/generic-infrastructure/gke-cluster
[aks-cluster]: https://github.com/generic-infrastructure/aks-cluster
[helm-aoa]: https://github.com/generic-infrastructure/helm-aoa
[helm-internal]: https://github.com/generic-infrastructure/helm-internal
[fastapi-app]: https://github.com/generic-infrastructure/fastapi-app

[terragrunt]: https://terragrunt.gruntwork.io/
[terraform]: https://www.terraform.io/
[helm]: https://helm.sh/
[kustomize]: https://kustomize.io/
[argo-cd]: https://argoproj.github.io/cd/

[minikube]: https://minikube.sigs.k8s.io/docs/
[aks]: https://learn.microsoft.com/en-us/azure/aks/
[doks]: https://docs.digitalocean.com/products/kubernetes/
[eks]: https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html
[gke]: https://cloud.google.com/kubernetes-engine/

[cert-manager]: https://cert-manager.io/
[selfsigned]: https://cert-manager.io/docs/configuration/selfsigned/
[acme]: https://cert-manager.io/docs/configuration/acme/

[istio]: https://istio.io/
[kiali]: https://kiali.io/
[knative]: https://knative.dev/docs/

[strimzi]: https://strimzi.io/
[zookeeper]: https://zookeeper.apache.org/
[kafka]: https://kafka.apache.org/

[postgres]: https://www.postgresql.org/
[redis]: https://redis.io/
[minio]: https://min.io/

[kube-prometheus]: https://prometheus-operator.dev/
[grafana]: https://grafana.com/
[prometheus]: https://prometheus.io/
[alertmanager]: https://prometheus.io/docs/alerting/latest/alertmanager/
[loki]: https://grafana.com/oss/loki/
[promtail]: https://grafana.com/docs/loki/latest/clients/promtail/
[tempo]: https://grafana.com/docs/tempo/latest/

[fastapi]: https://fastapi.tiangolo.com/