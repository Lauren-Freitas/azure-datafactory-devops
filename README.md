# azure-datafactory-devops

# 🔄 Projeto: Integração do Azure Data Factory com Azure DevOps

Este repositório documenta a configuração do controle de versionamento e backup automático de artefatos do Azure Data Factory usando Azure DevOps.

---

## 📌 Objetivo

Implementar a integração entre o Azure Data Factory (ADF) e o Azure DevOps para permitir:

- Controle de versão dos pipelines, datasets e linked services.
- Histórico de alterações.
- Organização do desenvolvimento com branches.
- Preparação do ambiente para automações de CI/CD no futuro.

---

## ⚙️ Principais Configurações Realizadas

- Criação de um repositório no Azure DevOps (`Dio-Project-Lauren`).
- Definição de branches:  
  - **branch** (desenvolvimento)  
  - **adf_publish** (publicação).
- Conexão do ADF ao repositório Git via "Git Configuration".
- Publicação de artefatos automáticos.

---

## 🖼️ Prints do Projeto

### 🔧 Configuração no Azure Data Factory
![01_adf_git_configuration](https://github.com/user-attachments/assets/59ad54a6-5264-4590-b0fc-58717d49db26)

### 📂 Estrutura de Repositório no Azure DevOps
![02_azuredevops_repositorio](https://github.com/user-attachments/assets/4ad54c93-82bc-4fdc-907c-c35811574650)

### 🌿 Controle de Branches no ADF
![03_adf_branches](https://github.com/user-attachments/assets/78bef449-4595-41c5-9da8-b9a841168dc7)

## 📚 Aprendizados

- Conectar Azure Data Factory ao Azure DevOps.
- Criar e gerenciar branches de colaboração e publicação.
- Versionar e visualizar alterações de artefatos diretamente pelo Git.
- Melhorar a governança e rastreabilidade de projetos de dados.

---

## 👩‍💻 Sobre mim

Me chamo **Lauren Freitas**, sou comissária de bordo em transição para a área de tecnologia.  
Atualmente estudo **Análise e Desenvolvimento de Sistemas** e estou aprendendo sobre **dados, automação e nuvem**.

[![LinkedIn](https://img.shields.io/badge/-Lauren%20Freitas-0077B5?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/laurend-freitas)  
[![GitHub](https://img.shields.io/badge/-@Lauren--Freitas-181717?logo=github&style=for-the-badge)](https://github.com/Lauren-Freitas)

---

✨ Projeto desenvolvido como parte do **bootcamp DIO – Azure Data Fundamentals**.
