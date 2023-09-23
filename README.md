# 0L Monitoring Infrastructure

kube-prometheus-stack HelmRelease in a cluster with FluxCD.

## Resources
- https://fluxcd.io
- https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack
- https://microk8s.io

## Tutorials
- https://ubuntu.com/tutorials/getting-started-with-microk8s-on-ubuntu-core#1-introduction
- https://fluxcd.io/flux/installation/bootstrap/github/
- https://fluxcd.io/flux/guides/helmreleases/

## Todos
- [ ] update `info@nour.space` in cert-manager resources
- [ ] update `openlibra.space` domain in ingress resources and templates
- [ ] update `ssh://git@github.com/bn-space/0l-infra` in Flux sync's GitRepository
- [ ] once Grafana is set up, manually
  - create dashboards from json files
  - confiture alerting (check `alert.settings.json`)
  - create validator-votes alert (check `validator-votes.alert.json`)
