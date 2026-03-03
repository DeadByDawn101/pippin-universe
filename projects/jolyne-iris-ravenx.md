# Jolyne × Iris — RavenX AI

**Repository:** [RavenX Workspace](https://github.com/DeadByDawn101/ravenx-workspace)

**Live Demo:** [jolynetheshiba.com](https://jolynetheshiba.com)

## Description

Jolyne × Iris is a live autonomous media agent project built on top of the Pippin ecosystem.

Iris runs continuously on GCP, posts to X with an approved queue flow, and supports the $STONEFREE ecosystem narrative. The project combines identity-driven character design, operational controls, and real deployment infrastructure.

## Relation to Pippin

This project extends Pippin by combining both:
- [pippin](https://github.com/pippinlovesyou/pippin) core digital being loop
- [pippin-ci](https://github.com/pippinlovesyou/pippin-ci) self-improving activity layer

### What we added
- Unified `pippin + pippin-ci` runtime in one production deployment
- Human-in-the-loop approval queue for posting safety
- Persistent 24/7 systemd deployment on GCP
- Multi-agent chain-of-command integration (RavenX sisters + Iris)
- Operational logging and dashboard integration for monitoring

## Screenshots

*(Optional — can be added in follow-up PR)*

- Live agent profile: [@jolyneshibasol](https://x.com/jolyneshibasol)
- Builder: [@deadbydawn101](https://x.com/deadbydawn101)

## Technical Stack (Raven Extensions)

### Runtime and Orchestration
- GCP VM with `systemd` services for continuous agent operation
- Pippin activity loop + pippin-ci self-improving activities in a unified runtime
- JSONL queue pipeline (`approved_queue.jsonl` -> post executor -> `posted_log.jsonl`)

### Agent Skills Layer
- **raven-comes-alive**: personality, memory, and content behavior layer for richer autonomous output
- **raven-x-empire-v2**: X operations layer for campaign framing, posting cadence, and execution workflows

### Data/Research Integration
- Native Firecrawl integration path for structured web extraction (search/scrape/crawl) into agent workflows
- Technical objective: reduce browser relay dependency for read-intel tasks and improve deterministic extraction

### Operations/Observability
- Central dashboard + logs for queue health, post throughput, and service status
- Approval-first posting policy with auditable artifacts for reproducibility and rollback
