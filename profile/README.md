### HRGUEDES - Developer Internal Rules ☕️💻

Este é o repositório de perfil da organização **HRGUEDES**. Este documento serve como o Guia de Padronização para todos os colaboradores e projetos internos.

### 🎯 Nossa Missão
Entregar software robusto com agilidade, mantendo o código limpo e a infraestrutura segura.

---

### 🛠️ Guia de Padronização e Governança

Para manter a casa organizada, todos os membros devem seguir estas diretrizes ao criar ou manter repositórios:

#### 1. Nomenclatura de Repositórios
Utilizamos o padrão **[PRODUTO]-[NOME-DO-PROJETO]**. 
Exemplos:
* `mob-vendas-app` (Para projetos do produto MOB)
* `crm-api-backend` (Para projetos do produto CRM)
* `web-landing-page`

#### 2. Higiene do Código (Setup Inicial)
Todo novo repositório **deve obrigatoriamente** conter:
* Um arquivo `.gitignore` apropriado para a linguagem/framework utilizada.
* Um arquivo `README.md` explicando como rodar o projeto localmente.

#### 3. Segurança em Primeiro Lugar (Zero Leak Policy) 🔐
É terminantemente proibido o versionamento de:
* Chaves de API, senhas de banco de dados ou tokens.
* Arquivos `.env` ou arquivos de configuração com dados sensíveis.
> **Dica:** Utilize variáveis de ambiente no servidor e arquivos `.env.example` no repositório.

---

### 🚀 Fluxo de Trabalho
1. **Branching:** Use `main` para produção e `develop` para integração.
2. **Pull Requests:** Todo código deve ser revisado antes do merge.
3. **Commits:** Prefira mensagens claras e em português (ou padrão definido no projeto).

---

### 📞 Canais de Contato e Suporte
Se encontrar algum problema de infraestrutura ou precisar de acesso a novas ferramentas:

* **CTO / Admin:** [Hugo Guedes]
* **E-mail Corporativo:** [hugo.guedes@hrguedes.dev]

---
*HRGUEDES - Transformando café em soluções digitais.*
