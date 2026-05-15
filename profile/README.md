<div align="center">

# Actyze

**Open-source self-hosted AI analytics on top of Trino**

Natural-language SQL across federated catalogs, ML predictions on existing tables,
scheduled KPIs. Sits on top of your data stack — no migration.

[Docs](https://docs.actyze.io) · [Website](https://actyze.ai) · License: AGPL v3

</div>

---

## Repositories

| Repo | Purpose |
|---|---|
| [`dashboard`](https://github.com/actyze/dashboard) | Main monorepo — frontend, Nexus API, schema service |
| [`helm-charts`](https://github.com/actyze/helm-charts) | Helm charts for Kubernetes |
| [`dashboard-docker`](https://github.com/actyze/dashboard-docker) | Docker Compose / image build configs |

## Built on

Trino · LiteLLM · XGBoost / LightGBM / AutoGluon

## Get started

- Self-host via [Docker Compose](https://github.com/actyze/dashboard-docker)
- Deploy on Kubernetes via [Helm](https://github.com/actyze/helm-charts)
- Read the [docs](https://docs.actyze.io)

## Contributing

Start with [`actyze/dashboard`](https://github.com/actyze/dashboard) and check open issues labeled `good-first-issue`.
