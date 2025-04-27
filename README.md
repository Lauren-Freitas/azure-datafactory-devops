# azure-datafactory-devops

🔄 Projeto: Integração do Azure Data Factory com Azure DevOps
Este repositório documenta a configuração do controle de versionamento e backup automático de artefatos do Azure Data Factory usando Azure DevOps.

📌 Objetivo
Implementar a integração entre o Azure Data Factory (ADF) e o Azure DevOps para permitir:

Controle de versão dos pipelines, datasets e linked services.

Histórico de alterações.

Organização do desenvolvimento com branches.

Preparação do ambiente para automações de CI/CD no futuro.

⚙️ Principais Configurações Realizadas
Criação de um repositório no Azure DevOps (Dio-Project-Lauren).

Definição de branches:

branch (desenvolvimento)

adf_publish (publicação).

Conexão do ADF ao repositório Git via "Git Configuration".

Publicação de artefatos automáticos (datasets, pipelines, linked services).

## 🖼️ Prints do Projeto

### 🔧 Configuração no Azure Data Factory
![Configuração Git no ADF](imagens/configuracao_git_adf.png)

### 📂 Estrutura de Repositório no Azure DevOps
![Arquivos no Azure DevOps](imagens/estrutura_devops_repositorio.png)

### 🌿 Controle de Branches no ADF
![Branches no ADF](imagens/controle_branches_adf.png)

📚 Aprendizados
Conectar Azure Data Factory ao Azure DevOps.

Criar e gerenciar branches de colaboração e publicação.

Versionar e visualizar alterações de artefatos diretamente pelo Git.

Melhorar a governança e rastreabilidade de projetos de dados.

👩‍💻 Sobre mim
Me chamo Lauren Freitas, sou comissária de bordo em transição para a área de tecnologia.
Atualmente estudo Análise e Desenvolvimento de Sistemas e estou aprendendo sobre dados, automação e nuvem.


✨ Projeto desenvolvido como parte do bootcamp DIO – Azure Data Fundamentals.
