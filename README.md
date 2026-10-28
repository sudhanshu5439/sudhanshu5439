## Hi, I'm Sudhanshu 👋

**Platform & DevSecOps engineer, building toward AI infrastructure and AI security.**
I build Kubernetes platforms where releases are boring (only trusted code ships, bad versions
roll themselves back, alerts mean real user pain), and I'm now putting AI to work on operations
*safely*: AIOps assistants that are treated as untrusted components, with guardrails, evidence
and audit trails.

🎓 CKA · AWS Certified Security – Specialty · AWS Certified Advanced Networking – Specialty ·
HashiCorp Terraform Associate

### 🔭 Building now: [Sentinel](https://github.com/sudhanshu5439/sentinel)

AIOps on a secure platform: an LLM incident assistant on top of a self-healing,
supply-chain-secured Kubernetes delivery platform, built from scratch and in public.

[![Sentinel architecture](https://raw.githubusercontent.com/sudhanshu5439/sentinel/main/docs/architecture/sentinel-architecture.png)](https://github.com/sudhanshu5439/sentinel)

| | |
|---|---|
| **AIOps** *(in progress)* | Alert grouping, evidence collection from Prometheus/Loki/Kubernetes/Argo CD, change correlation, LLM diagnosis that must cite its evidence |
| **AI security** | Prompt injection via telemetry in the threat model, query-injection-safe inputs, redaction before the LLM, schema + citation checks, policy-chosen actions, budgets, audit, an injection chaos test |
| **DevSecOps** | Semgrep · Gitleaks · Trivy · Syft SBOM · cosign keyless signing · SLSA provenance · Kyverno admission |
| **Platform** | GitOps with Argo CD · Argo Rollouts canaries judged by Prometheus · SLO burn-rate alerts · Loki · Tempo · Grafana · Terraform |

Code and CI: [sentinel](https://github.com/sudhanshu5439/sentinel) · Cluster state:
[sentinel-gitops](https://github.com/sudhanshu5439/sentinel-gitops) · Progress log:
[PROGRESS.md](https://github.com/sudhanshu5439/sentinel/blob/main/docs/PROGRESS.md)

### 🧰 Tools I work with

Kubernetes · Terraform · AWS · GitHub Actions · Argo CD · Argo Rollouts · Kyverno · Sigstore ·
Prometheus · Grafana · Loki · Tempo · OpenTelemetry · Traefik · Docker · Python (FastAPI) · Go ·
LLM APIs

### 📝 How I work

- Everything in Git: infrastructure, policies, releases, rollbacks.
- AI gets data, not authority: every model output is validated, cited and audited before anything
  acts on it.
- Write down what broke and why. Sentinel's progress log includes the real failures I hit,
  diagnosed and fixed.
- Only publish measured numbers.
