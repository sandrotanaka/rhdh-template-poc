# rhdh-template-poc

## 📌 Descrição
Este repositório contém artefatos e templates utilizados em um laboratório com o objetivo de validar o uso do **Red Hat Developer Hub (RHDH)** como plataforma de *Platform Engineering* e automação de provisionamento de recursos.

O laboratório explora a criação de templates reutilizáveis (*Software Templates*) para padronizar e automatizar a criação de recursos em ambientes OpenShift, além da integração com ferramentas externas como GitHub, Azure DevOps e Ansible Automation Platform.

---

## 🎯 Objetivos do laboratório
- Validar o uso do RHDH como portal de autoatendimento (*self-service*)
- Automatizar o provisionamento de infraestrutura (namespaces, quotas, limits)
- Testar integração com ferramentas externas (Git, CI/CD, Ansible)
- Implementar práticas de GitOps
- Avaliar governança e controle de acesso

---

## 📁 Estrutura do Repositório

```bash
.
├── skeleton/                              # Arquivos base utilizados pelos templates
├── README.md                              # Documentação do projeto
├── ansible-job-template-test.yaml         # Exemplo de integração com Ansible
├── create-namespace-quota-limit.yaml      # Template para criação de namespace + quotas
├── org.yaml                               # Definição de organização/catalogo
├── template-create-database-ansible.yaml  # Template com integração Ansible
