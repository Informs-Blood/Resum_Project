# Профиль / Портфолио

Системный администратор, DevOps. Опыт администрирования серверной инфраструктуры, мониторинга, автоматизации и информационной безопасности.

---

## Навыки

| Область | Инструменты / Технологии |
|---------|--------------------------|
| **Системное администрирование** | Linux (Ubuntu, RedOS, Debian), Windows Server (2008 R2–2019), VMware ESXi, Hyper-V, VirtualBox, systemd (journald, unit override), sysctl, cgroups |
| **Контейнеры / оркестрация** | Docker, containerd, Kubernetes (multi-DC, kubelet, kube-reserved, NodeSwap), Helm, Kustomize, OCI-образы, Harbor |
| **CI/CD** | GitLab CI/CD, Jenkins, Concourse CI (fly, set_pipeline, resources, tasks), GitHub Actions, Tekton, Semver (S3) |
| **GitOps** | Flux, Argo CD, Git (конфиг и пайплайны как код) |
| **Мониторинг и наблюдаемость** | Prometheus (retention, relabel, recording rules), Grafana, Alertmanager, Pushgateway, Zabbix, Telegram API, интеграция с системами инцидентов |
| **SIEM / логи** | Wazuh, Graylog |
| **Автоматизация** | Ansible (playbooks, роли, inventory, group_vars), Git |
| **Сети** | TCP/IP, VLAN, DHCP, DNS, VPN (IPsec, OpenVPN), MikroTik, Cisco, D-Link, HP, Cilium (eBPF), HAProxy (L7), firewalld |
| **Безопасность** | iptables, ufw, Windows Firewall, fail2ban, RBAC, ACL, SSL/TLS, Kaspersky Security Center |
| **DevSecOps / безопасность кода** | Gitleaks, TruffleHog, Hadolint, Checkov (IaC), Semgrep, Bandit, SonarQube, Trivy (образы, fs), OWASP ZAP (DAST), Snyk/Dependabot (SCA), Conftest/OPA, Kyverno, Cosign (Sigstore), Syft (SBOM) |
| **СУБД** | MySQL, PostgreSQL (репликация, HA, primary/standby) |
| **Очереди и бэкенды** | RabbitMQ, S3-совместимое хранилище |
| **Резервное копирование** | Veeam Backup & Replication, FreeNAS |
| **Почта / приложения** | Postfix, Dovecot, Nextcloud, 1С |
| **Телефония / видеонаблюдение** | UIS, 3CX, MTT, СКУД (SecureOS) |
| **Vault** | HashiCorp |
| **Мягкие навыки** | Лидерство, коммуникация, аналитическое мышление, работа в условиях сжатых сроков |

---

## Выполненные кейсы

| Кейс | Краткое описание |
|------|------------------|
| [Prometheus + Grafana + Alertmanager](cases/monitoring-prometheus-grafana.md) | Внедрение мониторинга, оповещения в Telegram и систему управления инцидентами |
| [SIEM: Wazuh + Graylog](cases/siem-wazuh-graylog.md) | Развёртывание SIEM, централизованный сбор логов и анализ угроз |
| [Автоматизация с Ansible](cases/ansible-automation.md) | Playbooks и роли, интеграция с CI/CD, развёртывание серверов |
| [План аварийного восстановления (DRP)](cases/disaster-recovery.md) | DRP, Veeam, тестовый стенд, интеграция с мониторингом |
| [Миграция БД MySQL → PostgreSQL HA](cases/postgresql-migration-ha.md) | Миграция с минимальным простоем, репликация, высокая доступность |
| [Миграция почты на VPS](cases/mail-migration-vps.md) | Переезд с облачной почты на собственные VPS (Postfix, Dovecot) |
| [Zabbix + Grafana](cases/monitoring-zabbix-grafana.md) | Мониторинг сети и серверов, дашборды |
| [Видеонаблюдение и СКУД](cases/video-access-control.md) | Проектирование и внедрение системы видеонаблюдения и контроля доступа |
| [L7-балансировщик HAProxy](cases/haproxy-l7-balancer.md) | whitelist по FQDN, forbidden-сервис, конфиг в Git |
| [CI/CD и версионирование БД для розничной учётной системы](cases/ci-cd-retail-postgres-docker.md) | PostgreSQL в Git, пайплайн, тесты и нагрузка, Docker + фискальный модуль для маркировки |
| [Комплексная оптимизация инфраструктуры (Senior DevOps)](cases/senior-devops-infra-optimization.md) | journald, kube-reserved, containerd/Docker, sysctl, Prometheus, логи, swap/OOM, профили по ролям, демоны, очистка диска и образов |
| [DevSecOps-пайплайн на GitLab CI](cases/devsecops-gitlab-pipeline.md) | Gitleaks, Hadolint, Checkov, Semgrep, Bandit, SonarQube, Trivy, OWASP ZAP, SCA, Helm, Argo CD — полный CI/CD с security-gates |
| [GitOps CI/CD с security-стеком и SBOM](cases/gitops-cicd-security-sbom.md) | GitHub Actions/Jenkins, Syft, Cosign, Trivy, Snyk, Argo CD, Conftest/OPA, Kyverno — подпись образов, SBOM, policy as code |
| [Concourse + Flux + Ansible: полный пайплайн и замена kube-proxy](cases/concourse-flux-ansible-pipeline.md) | Всё на Kubernetes, несколько ЦОДов, Master/Slave; Concourse (fly, set_pipeline), Ansible, Helm, Harbor, Flux, Cilium |

---

## Контакты

<!-- Добавь по желанию: Telegram, LinkedIn, email -->
