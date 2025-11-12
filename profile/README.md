<p align="center">
  <a href="https://www.fidelyn.com" target="_blank">
    <img src="https://raw.githubusercontent.com/fidelyn-app/.github/refs/heads/main/profile/assets/logo.png" alt="Fidelyn Logo" width="200"/>
  </a>
</p>



# Bem-vindo ao Fidelyn 🚀

Somos uma equipe focada no desenvolvimento de soluções digitais para **fidelização e engajamento de clientes**. Nosso objetivo é simplificar a conexão entre empresas e consumidores através de tecnologia ágil e escalável.

---

## 🛠️ Tech Stack & Ferramentas

Nossa arquitetura é baseada em tecnologias modernas para garantir performance e facilidade de manutenção:

### Mobile & Frontend
![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

### Backend & Infra
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### Pagamentos & Integrações
![Stripe](https://img.shields.io/badge/Stripe-5433FF?style=for-the-badge&logo=stripe&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 📂 Estrutura dos Repositórios

Para facilitar a navegação, organizamos nossos projetos da seguinte forma:

| Repositório | Descrição | Stack Principal |
| :--- | :--- | :--- |
| **[`fidelyn-user-app`](#)** | Aplicativo do cliente final (iOS/Android) | Flutter |
| **[`fidelyn-store-app`](#)** | Aplicativo do logista (iOS/Android) | Flutter |
| **[`fidelyn-api`](#)** | API Principal, regras de negócio e Webhooks | NestJS / Postgres |
| **[`fidelyn-landing-page`](#)** | Landing page com informações e contato | HTML / CSS / JS |

---

## ⚡ Guia Rápido (Onboarding)

Se você acabou de chegar no time, siga estes passos para configurar seu ambiente:

1. **Clone os projetos:** Certifique-se de ter acesso à organização.
2. **Ambiente:** Tenha Docker e Node.js (v18+) instalados.
3. **Variáveis de Ambiente:** Copie o arquivo `.env.example` para `.env` em cada projeto.
4. **Start:**
   - No Backend: `npm run start:dev`
   - No Mobile: `flutter run`

> 🔒 **Segurança:** Nunca suba chaves de API (Stripe Secret Keys) para o repositório. Use Secrets do GitHub Actions para CI/CD.

---

## 📫 Contato & Suporte

- **Dúvidas Técnicas:** Abra uma [Issue](#) no repositório correspondente.

## 📋 Modelo de criação de Histórias


### 📖 A História (User Story)
**Como** [tipo de usuário: ex: admin, cliente]
**Eu quero** [ação: ex: ver meus pontos]
**Para que** [benefício: ex: saber se já posso trocar por prêmios]

---

### ✅ Critérios de Aceite (O que define "Pronto"?)
Para essa task ser considerada concluída, o seguinte deve funcionar:

- [ ] O usuário deve conseguir visualizar X...
- [ ] Se der erro, deve aparecer a mensagem Y...
- [ ] O layout deve seguir o protótipo...
- [ ] Deve salvar no banco de dados...

---

### 🛠 Notas Técnicas / Implementação
* **Endpoint:** `GET /api/v1/...`
* **Tabelas afetadas:** `users`, `transactions`
* **Obs:** Lembrar de tratar o caso quando a lista estiver vazia.