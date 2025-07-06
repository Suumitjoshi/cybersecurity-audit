Checklist for VMs, containers, network, CI/CD pipelines

| Component   | ✅ Check Item                                |
| ----------- | ------------------------------------------- |
| OS          | ✅ Latest security patches installed         |
| SSH         | ✅ Key-based SSH only, root disabled         |
| Containers  | ✅ Non-root container users                  |
| Dockerfiles | ✅ No secrets in Dockerfiles or images       |
| Firewalls   | ✅ Ports restricted by rule-based firewall   |
| CI/CD       | ✅ Secrets stored in vault, not in scripts   |
| Pipeline    | ✅ Code scanning in pipeline (CodeQL/Bandit) |
| Monitoring  | ✅ Prometheus/Grafana or Azure Monitor used  |
| Access      | ✅ No shared admin accounts                  |
| Audit Logs  | ✅ Central logging with retention policy     |

