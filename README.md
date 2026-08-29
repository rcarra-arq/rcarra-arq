![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Terraform](https://img.shields.io/badge/Terraform-IaC-purple)
![FinOps](https://img.shields.io/badge/FinOps-Cost_Governance-2ea44f)
![Reliability](https://img.shields.io/badge/Reliability-Engineering-1f6feb)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-kind-326CE5)
![Python](https://img.shields.io/badge/Python-boto3-3776AB)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-black)

# Cloud & DevOps: building toward FinOps & Reliability

Sou a **Renata**, arquiteta e urbanista. Trabalhei muitos anos desenvolvendo e
compatibilizando projetos para grandes construtoras, e brincava que minha
função era resolver problemas. Hoje entendo que são as mesmas competências que
sustentam uma boa arquitetura de nuvem: entender sistemas complexos, avaliar
limitações e encontrar a solução mais adequada. Estou em transição para Cloud,
me especializando em AWS pela Escola da Nuvem, e aprendo construindo: quando um
lab quebra, eu pesquiso, testo e entendo a causa em vez de desistir.

I'm **Renata**, an architect and urban planner transitioning into Cloud,
specializing in AWS through Escola da Nuvem. My background was solving complex
problems for large construction companies, the same skill that holds up good
cloud architecture. I learn by building: when a lab breaks, I research, test,
and dig into the root cause instead of giving up.

🇺🇸 [Full version in English ↓](#english)

## Português

**Tecnologias:** Docker · Terraform · Git & GitHub · GitHub Actions · Jenkins ·
Ansible · Kubernetes · Prometheus / Grafana · Python (boto3) · Linux ·
AWS (EC2, S3, IAM, VPC)

## Projetos em destaque

**AWS Highly Available Web Application (Terraform)**: `FinOps` · `Confiabilidade`
Infraestrutura de alta disponibilidade na AWS com Terraform: VPC customizada,
Application Load Balancer, Auto Scaling Group multi-AZ e EC2 com Nginx. Inclui
tagging padronizado para alocação de custo e alertas de orçamento com AWS
Budgets (FinOps), além de um caso de troubleshooting documentado.
https://github.com/rcarra-arq/aws-highly-available-webapp-terraform

**FinOps Tag Auditor (Python + boto3)**: `FinOps`
Ferramenta em Python que audita recursos de nuvem em busca de tags de alocação
de custo faltando (`Project`, `Environment`, `Owner`), o lado da fiscalização
do tagging de FinOps. Lê recursos reais da AWS em modo somente leitura via
boto3, com códigos de saída amigáveis a CI para um pipeline falhar em recursos
sem tag.
*Foi o projeto que eu mais me interessei em pesquisar e construir.*
https://github.com/rcarra-arq/finops-tag-auditor

**Cloud Monitoring DevOps Lab (Docker + Prometheus/Grafana)**: `Confiabilidade` · `Observabilidade`
Aplicação containerizada monitorada de ponta a ponta com stack Prometheus +
Grafana; pipeline de CI que builda, testa e escaneia (Trivy); e documentações
detalhadas de troubleshooting no estilo análise de causa raiz / postmortem.
https://github.com/rcarra-arq/cloud-monitoring-lab

### Outros laboratórios
- **terraform-aws-ec2-lab**: Provisionamento de EC2 na AWS com Terraform (IaC). https://github.com/rcarra-arq/terraform-aws-ec2-lab
- **terraform-docker-lab**: EC2 + Docker + Nginx, validado com GitHub Actions. https://github.com/rcarra-arq/terraform-docker-lab

Foco atual: Certificação AWS Cloud Practitioner · Práticas de FinOps · Automação com CI/CD · Linux e redes

Objetivo: Atuar como Cloud / DevOps / Infraestrutura Júnior

Esses são os projetos que venho desenvolvendo até agora. Fique à vontade para me mandar uma msg se eu puder contribuir com alguma coisa. 🙂

💬 [LinkedIn](https://www.linkedin.com/in/renata-carra/)

---

## English

🇧🇷 [Versão em português ↑](#cloud--devops--building-toward-finops--reliability)

**Technologies:** Docker · Terraform · Git & GitHub · GitHub Actions · Jenkins ·
Ansible · Kubernetes · Prometheus / Grafana · Python (boto3) · Linux ·
AWS (EC2, S3, IAM, VPC)

## Featured projects

**AWS Highly Available Web Application (Terraform)**: `FinOps` · `Reliability`
Highly available AWS infrastructure with Terraform: custom VPC, Application Load
Balancer, multi-AZ Auto Scaling Group, and EC2 running Nginx. Includes
standardized cost-allocation tagging and AWS Budget alerts (FinOps), plus a
documented troubleshooting case.
https://github.com/rcarra-arq/aws-highly-available-webapp-terraform

**FinOps Tag Auditor (Python + boto3)**: `FinOps`
A Python tool that audits cloud resources for missing cost-allocation tags
(`Project`, `Environment`, `Owner`), the enforcement side of FinOps tagging.
Reads real AWS resources read-only via boto3, with CI-friendly exit codes so a
pipeline can fail on untagged resources.
*The project I was most interested in researching and building.*
https://github.com/rcarra-arq/finops-tag-auditor

**Cloud Monitoring DevOps Lab (Docker + Prometheus/Grafana)**: `Reliability` · `Observability`
Containerized app monitored end-to-end with a Prometheus + Grafana stack; a CI
pipeline that builds, smoke-tests and security-scans (Trivy); and detailed
troubleshooting write-ups in a root-cause / postmortem style.
https://github.com/rcarra-arq/cloud-monitoring-lab

### Additional labs
- **terraform-aws-ec2-lab**: Provisioning AWS EC2 with Terraform (Infrastructure as Code). https://github.com/rcarra-arq/terraform-aws-ec2-lab
- **terraform-docker-lab**: EC2 + Docker + Nginx, validated with GitHub Actions. https://github.com/rcarra-arq/terraform-docker-lab

Currently focused on: AWS Cloud Practitioner certification · FinOps practices · CI/CD automation · Linux and networking

Goal: Junior Cloud / DevOps / Infrastructure role

These are the projects I've been building so far. Feel free to send me a message if there's anything I can help with. 🙂

💬 [LinkedIn](https://www.linkedin.com/in/renata-carra/)
