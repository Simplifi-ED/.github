# Omnivya Engineering

**Cloud, platform and software engineering for systems that need to be reliable, observable, secure and operable.**

This GitHub organization hosts public engineering work maintained by the team behind [Omnivya](https://www.omnivya.fr/).

Our open-source work focuses on practical infrastructure and platform problems: understanding dependencies, operating Kubernetes and cloud environments, improving CI/CD security, making infrastructure costs explicit, and building tooling that removes operational friction.

## Engineering focus

- **Cloud & infrastructure** — Azure, hybrid architectures, infrastructure automation and cost visibility.
- **Kubernetes & platform engineering** — operators, workload lifecycle, GitOps and platform automation.
- **SRE & observability** — Prometheus, OpenTelemetry, dependency signals, diagnostics and reliability engineering.
- **Security & software supply chain** — SBOM, secret detection, CI/CD security and policy enforcement.
- **Developer & operations tooling** — focused tools designed to be understandable, testable and useful in real environments.

## Selected projects

### [External Metrics Exporter](https://github.com/Simplifi-ED/external-metrics-exporter)
Discovers external dependencies used by Kubernetes workloads, builds blast-radius context and exports provider-neutral SRE signals across cloud and SaaS systems.

### [cloudcost](https://github.com/Simplifi-ED/cloudcost)
Queries Azure retail pricing to make infrastructure cost assumptions explicit, comparable and reproducible.

### [Azure DevOps Kubernetes Operator](https://github.com/Simplifi-ED/azdo-kube-operator)
Runs self-hosted Azure DevOps agents on Kubernetes and adjusts capacity according to pipeline demand.

### [Azure DevOps Supply-Chain Scanner](https://github.com/Simplifi-ED/ShaiHulud-AzureDevops-Scanner)
Generates SBOMs, scans repositories for exposed secrets and evaluates software supply-chain policies with Dependency-Track.

### [container compose](https://github.com/Simplifi-ED/compose)
Provides Compose-style orchestration for Apple's container runtime on macOS, including dependency-aware startup, health checks and operational commands.

### [setup-step-cli](https://github.com/Simplifi-ED/setup-step-cli)
Installs Smallstep CLI reproducibly in GitHub Actions with CI, CodeQL and release automation.

## Engineering principles

We prefer explicit architecture, observable behaviour and documented limitations over opaque automation.

Public repositories should make it possible to understand:

- why the project exists;
- what problem it solves;
- how the main components interact;
- what security and operational assumptions it makes;
- what is stable, experimental or intentionally unsupported.

## Links

[Omnivya](https://www.omnivya.fr/) · [LinkedIn](https://www.linkedin.com/company/simplifi-ed/)
