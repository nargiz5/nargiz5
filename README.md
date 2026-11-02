<h1 align="center">Nargiz Bakhshaliyeva</h1>

<p align="center"><i>I break pipelines politely, so attackers don't have to.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Security-Engineer-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DevSecOps-pipelines-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AppSec-SAST%20%7C%20secrets-black?style=for-the-badge" />
</p>

```console
nargiz@lab:~$ whoami
ai-security-engineer && devsecops

nargiz@lab:~$ cat focus.txt
  [x] shift security left: scan on every push, not once a year
  [x] gate the pipeline: High finding in = alert out
  [x] keep secrets out of git (and clean up fast when they slip in)
  [x] secure the AI systems that everyone is rushing to ship

nargiz@lab:~$ ./run_pipeline.sh
  push -> semgrep -> defectdojo -> gate -> telegram 🚨
```

## 🧪 Lab notebook
| Repo | The one-line story |
|---|---|
| [devsecops-pipeline](https://github.com/nargiz5/devsecops-pipeline) | A whole security factory in Docker: GitLab CI, Semgrep, DefectDojo, Vault, Grafana, Telegram alerts |
| [devsecops-ansible](https://github.com/nargiz5/devsecops-ansible) | The same factory, built by Ansible while I drink tea |
| [n8n-gitlab-sync](https://github.com/nargiz5/n8n-gitlab-sync) | `git log` for n8n workflows, with AI-written changelogs |

## 🧰 Toolbox
`GitLab CI` `Semgrep` `Trivy` `DefectDojo` `HashiCorp Vault` `Ansible` `Docker` `Grafana` `PostgreSQL` `n8n` `Bash` `Linux`

## 📜 Lesson learned the hard way
> A secret deleted from a file is still in git history. Revoke first, rewrite history second, delete old tags third.

📧 nargiz.bakhshaliyevaa@gmail.com · [LinkedIn](https://www.linkedin.com/in/nargizbakhshaliyeva)
