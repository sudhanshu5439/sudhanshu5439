## Hi, I'm Sudhanshu 👋

**Platform / DevOps engineer.** I build Kubernetes platforms where releases are boring: only
trusted code ships, bad versions roll themselves back, and alerts mean real user pain.

🎓 CKA · AWS Certified Security – Specialty · AWS Certified Advanced Networking – Specialty ·
HashiCorp Terraform Associate

### 🔭 Building now: [Sentinel](https://github.com/sudhanshu5439/sentinel)

A self-healing, supply-chain-secured Kubernetes delivery platform with an LLM-powered incident
assistant, built from scratch and in public.

| | |
|---|---|
| **Supply chain** | Semgrep · Gitleaks · Trivy · Syft SBOM · cosign keyless signing · SLSA provenance · Kyverno admission |
| **Delivery** | GitOps with Argo CD (app-of-apps, promotion by digest via PR) · Argo Rollouts canaries judged by Prometheus |
| **Observability** | Prometheus · Loki · Tempo · Grafana · Alloy (OpenTelemetry) · multi-burn-rate SLO alerts |
| **AIOps** *(in progress)* | Alert grouping, evidence collection, change correlation, LLM diagnosis that must cite its evidence |

Code and CI: [sentinel](https://github.com/sudhanshu5439/sentinel) · Cluster state:
[sentinel-gitops](https://github.com/sudhanshu5439/sentinel-gitops) · Progress log:
[PROGRESS.md](https://github.com/sudhanshu5439/sentinel/blob/main/docs/PROGRESS.md)

### 🧰 Tools I work with

Kubernetes · Terraform · AWS · GitHub Actions · Argo CD · Argo Rollouts · Kyverno · Prometheus ·
Grafana · Loki · Tempo · Traefik · Docker · Python · Go · Bash

### 📝 How I work

- Everything in Git: infrastructure, policies, releases, rollbacks.
- Write down what broke and why. Sentinel's progress log includes the real failures I hit,
  diagnosed and fixed.
- Only publish measured numbers.
