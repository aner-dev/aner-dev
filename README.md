# Leandro Etcheverry — Kubernetes Engineer

Linux enthusiast. My main project is **Athanor**: a single-node Kubernetes
homelab managed with FluxCD GitOps, Cilium (eBPF) as CNI, and ESO + OpenBao
for secrets (SOPS only for bootstrap).
I run my own **CI on self-hosted Forgejo Actions runners**.

## What I do

- **Kubernetes / GitOps** — bare-metal single-node cluster, Flux CD,
  Kustomize overlays, Cilium network policies (default-deny, FQDN-aware egress)
- **Platform** — self-hosted Forgejo + runners (CI on my own infra), container
  registry, observability (Prometheus/VictoriaMetrics, Grafana, Loki)
- **Security** — OpenBao as source of truth, consumed via ESO
  `ExternalSecret`s; rotation runbooks, private CAs. Secrets never land in
  git — SOPS only covers bootstrap leftovers.
- **Agentic engineering** — DevOps + agentic coding is still early, and
  off-the-shelf tooling keeps falling short inside real clusters. So I build
  my own: skills, harnesses and runbooks, validated against Athanor before
  anything else.
- **Background** — came from Data Engineering (ELT pipelines, Spark/Iceberg
  lakehouse), now platform full-time. Past work stays linked below as context,
  not direction.

## Projects & Links

- 🏠 Homelab (live repo, mirrored): https://github.com/aner-dev/athanor
- 🌐 Portfolio — architecture, decisions, incidents, postmortems:
  https://portfolio.athanor.fyi
- 💼 Career: https://www.linkedin.com/in/leandro-etcheverry-data-engineer/

## Stack

<div align="left">
  <img src="https://skillicons.dev/icons?i=kubernetes" height="40" alt="kubernetes" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=terraform" height="40" alt="terraform" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=docker" height="40" alt="docker" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=prometheus" height="40" alt="prometheus" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=grafana" height="40" alt="grafana" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=go" height="40" alt="go" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=py" height="40" alt="python" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=linux" height="40" alt="linux" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=bash" height="40" alt="bash" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="git" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=githubactions" height="40" alt="github actions" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=aws" height="40" alt="aws" />
</div>
