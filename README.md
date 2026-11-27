# Nargiz Bakhshaliyeva

**DevSecOps · Application Security · AI Security**

## Focus
- **DevSecOps:** CI/CD pipelines with SAST, SCA, secret scanning, container image scanning and security gates
- **Application security:** static analysis and taint tracking, Semgrep and Trivy scanning, false-positive triage, remediation support for development teams
- **AI security:** attacking and hardening tool-using AI agents (prompt injection, excessive agency, data leakage), mapped to the OWASP Top 10 for LLM Applications
- **Infrastructure as code:** reproducible security tooling with Docker, Ansible and HashiCorp Vault
- **Security automation:** n8n workflows and AI agents that reduce manual security work

## Selected projects
| Project | Description |
|---|---|
| [codesentinel](https://github.com/nargiz5/codesentinel) | Taint analyzer for Python web code that follows untrusted data across functions and modules, with over 300 tests. Found 3 of 5 published CVEs, including the cross-module RCE in pgAdmin 8.4 (CVE-2024-3116) and an SSRF in calibre-web (CVE-2022-0339) that neither CodeQL nor Semgrep reports. On the independent RealVuln benchmark, 87% of its alerts were real (Semgrep, same vulnerability classes: 65%). An optional local LLM recognized 12 of 24 false alarms on real projects with a neutral prompt. |
| [n8n-ai-agent-security-lab](https://github.com/nargiz5/n8n-ai-agent-security-lab) | Vulnerable and hardened versions of a tool-using AI agent, with attack scenarios mapped to the OWASP Top 10 for LLM Applications (2025) |
| [devsecops-pipeline](https://github.com/nargiz5/devsecops-pipeline) | Self-hosted DevSecOps lab: GitLab CI, Semgrep SAST, DefectDojo, HashiCorp Vault and Grafana, with a High-severity security gate and Telegram alerting |
| [devsecops-ansible](https://github.com/nargiz5/devsecops-ansible) | End-to-end provisioning of the same stack with taggable Ansible roles and Ansible Vault |
| [n8n-gitlab-sync](https://github.com/nargiz5/n8n-gitlab-sync) | Git-based version control for n8n workflows, running in production for 23 workflows: a PostgreSQL trigger syncs every change to GitLab, with noise-filtered diffs and AI-generated changelogs ([write-up](https://medium.com/@nargiz.bakhshaliyeva.05/git-based-version-control-to-n8n-workflows-with-gitlab-29cdebad5825)) |

## Technical skills
- **DevSecOps and AppSec:** GitLab CI, Semgrep, Snyk, Gitleaks, Trivy, DefectDojo, taint analysis
- **Infrastructure and automation:** Docker, Ansible, HashiCorp Vault, n8n, Bash, Python, PostgreSQL, Grafana
- **Foundations:** Linux, networking, cryptography, threat modeling

## Contact
nargiz.bakhshaliyeva.05@gmail.com · [LinkedIn](https://www.linkedin.com/in/nargizbakhshaliyeva)
