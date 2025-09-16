# FinApp - Aplicativo de Finanças Pessoais 💰

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-brightgreen)
![Java](https://img.shields.io/badge/Java-21-orange)
![React Native](https://img.shields.io/badge/React%20Native-0.79.6-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue)
![Expo](https://img.shields.io/badge/Expo-53.0.22-black)

**Desenvolvedor Responsável:** Fábio Hiroshi Damazio Matsumura

## 📋 Sobre o Projeto

O FinApp é um aplicativo de finanças pessoais desenvolvido para auxiliar os usuários a controlarem melhor sua vida financeira. O sistema oferece ferramentas práticas, seguras e intuitivas para registro de despesas, criação de orçamentos, acompanhamento detalhado de gastos e promoção da educação financeira.

## 🎯 Missão

Fornecer uma plataforma completa e intuitiva que incentive boas práticas financeiras, promova o equilíbrio econômico dos usuários e facilite o controle e planejamento financeiro pessoal através de tecnologia moderna e funcionalidades offline.

## 🎯 Objetivos

- ✅ Permitir registro organizado de receitas e despesas
- ✅ Facilitar a criação de orçamentos personalizados por categoria
- ✅ Oferecer acompanhamento de metas de economia
- ✅ Fornecer lembretes automáticos de contas a pagar
- ✅ Garantir funcionamento offline com sincronização automática
- ✅ Promover educação financeira através de conteúdo educativo
- 🔄 Implementar relatórios visuais para análise de padrões de gasto
- 🔄 Integrar com instituições bancárias para importação de dados
- 🔄 Permitir exportação de dados em formatos PDF e planilhas

## 🛠️ Tecnologias Utilizadas

### Backend
- **Spring Boot 3.2.0** - Framework principal
- **Java 21** - Linguagem de programação
- **H2 Database** - Banco de dados em memória
- **JWT** - Autenticação e autorização
- **Swagger/OpenAPI** - Documentação da API
- **Maven** - Gerenciador de dependências

### Frontend Mobile
- **React Native 0.79.6** - Framework mobile
- **Expo 53.0.22** - Plataforma de desenvolvimento
- **TypeScript 5.8.3** - Linguagem de programação
- **TanStack Query** - Gerenciamento de estado
- **SQLite** - Banco de dados local
- **Expo Notifications** - Sistema de notificações


## 📜 Product Backlog <a name="backlog"></a>

| RANK | SPRINT | PRIORIDADE | ESTIMATIVA | USER STORY (NOME) | STATUS |
|:----:|:------:|:----------:|:----------:|:-----------------:|:------:|
| 1 | 1 | Alta | 8 | Como usuário, quero criar um perfil individual com minhas informações básicas, para personalizar minha experiência financeira | ✅ |
| 2 | 1 | Alta | 5 | Como usuário, quero fazer login seguro com JWT, para proteger meus dados financeiros | ✅ |
| 3 | 1 | Alta | 8 | Como usuário, quero registrar receitas e despesas com valores, categorias e datas, para acompanhar minha movimentação financeira | ✅ |
| 4 | 1 | Alta | 5 | Como usuário, quero criar e gerenciar categorias personalizadas, para organizar minhas transações | ✅ |
| 5 | 1 | Alta | 3 | Como usuário, quero receber sugestões automáticas de categorias baseadas em transações anteriores, para agilizar o cadastro | ✅ |
| 6 | 1 | Alta | 8 | Como usuário, quero criar orçamentos personalizados por categoria e período, para controlar meus gastos | ✅ |
| 7 | 1 | Alta | 5 | Como usuário, quero definir limites de gastos mensais por categoria, para manter o controle financeiro | ✅ |
| 8 | 1 | Alta | 8 | Como usuário, quero receber alertas automáticos quando me aproximar dos limites de orçamento, para evitar gastos excessivos | ✅ |
| 9 | 1 | Alta | 13 | Como usuário, quero usar o app offline e sincronizar automaticamente quando conectar, para ter acesso sempre | ✅ |
| 10 | 1 | Média | 8 | Como usuário, quero criar metas de economia com objetivos e prazos, para alcançar meus sonhos financeiros | ✅ |
| 11 | 1 | Média | 5 | Como usuário, quero acompanhar o progresso das minhas metas de economia, para me manter motivado | ✅ |
| 12 | 1 | Média | 8 | Como usuário, quero programar lembretes de contas a pagar, para não esquecer pagamentos importantes | ✅ |
| 13 | 1 | Média | 5 | Como usuário, quero configurar transações recorrentes, para automatizar registros mensais | ✅ |
| 14 | 1 | Média | 8 | Como usuário, quero consultar histórico detalhado de movimentações, para revisar gastos e receitas passados | ✅ |
| 15 | 1 | Média | 8 | Como usuário, quero visualizar análise de fluxo de caixa mensal, para saber se estou positivo ou negativo | ✅ |
| 16 | 2 | Baixa | 5 | Como administrador, quero gerenciar conteúdo educacional sobre finanças, para educar os usuários | 🔄 |
| 17 | 2 | Alta | 8 | Como usuário, quero receber notificações motivacionais sobre o progresso das metas, para me manter engajado | 🔄 |
| 18 | 2 | Média | 13 | Como usuário, quero visualizar relatórios em gráficos e tabelas, para entender meus padrões de gasto | ❌ |
| 19 | 2 | Baixa | 5 | Como usuário, quero usar autenticação biométrica, para maior segurança e praticidade | ❌ |
| 20 | 3 | Alta | 13 | Como usuário, quero integrar minhas contas bancárias, para importar transações automaticamente | ❌ |
| 21 | 3 | Média | 8 | Como usuário, quero exportar meus dados em PDF ou planilhas, para arquivar ou compartilhar informações | ❌ |
| 22 | 3 | Baixa | 5 | Como usuário, quero personalizar a interface com temas e cores, para uma experiência mais agradável | ❌ |
| 23 | 3 | Baixa | 3 | Como usuário, quero acessar conteúdo educativo sobre finanças, para aprender conceitos importantes | ❌ |
| 24 | 3 | Baixa | 8 | Como usuário, quero receber atualizações automáticas do app, para ter sempre as melhorias de segurança | ❌ |
| 25 | 3 | Baixa | 8 | Como usuário, quero receber sugestões de categorias | ❌ |

### Legenda de Status:
- ✅ **Implementado**: Funcionalidade completamente desenvolvida e funcional
- 🔄 **Parcialmente**: Backend implementado, necessita integração ou refinamentos
- ❌ **Não Implementado**: Funcionalidade planejada para desenvolvimento futuro


## 🏗️ Arquitetura do Sistema

O FinApp utiliza uma arquitetura **offline-first** que garante funcionamento completo mesmo sem conexão à internet:

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   React Native  │    │   Spring Boot    │    │   SQL Database   │
│     Mobile      │◄──►│     Backend      │◄──►│                 │
│                 │    │                  │    │                 │
│   - SQLite      │    │   - JWT Auth     │    │   - JPA/Hibernate│
│   - Sync Queue  │    │   - REST API     │    │   - Transactions │
│   - Offline UI  │    │   - Swagger      │    │   - Users/Budget │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```


## 🚀 Instalação e Execução

### Pré-requisitos
- Java 21+
- Node.js 18+
- Expo CLI
- Maven 3.6+

### Backend (Spring Boot)
```bash
cd a/crud
mvn clean install
mvn spring-boot:run
```

A API estará disponível em `http://localhost:8080`
Documentação Swagger: `http://localhost:8080/swagger-ui.html`

### Frontend Mobile (React Native)
```bash
cd finAppMobile
npm install
npx expo start
```

### Executar no Dispositivo
- Instale o Expo Go no seu smartphone
- Escaneie o QR code gerado pelo comando `expo start`
- Ou execute `npx expo run:android` / `npx expo run:ios`

## 📚 Documentação da API

A API REST está completamente documentada com Swagger/OpenAPI:

**Base URL**: `http://localhost:8080/api`


## 📁 Estrutura do Projeto

```
FinApp/
├── a/crud/                          # Backend Spring Boot
│   ├── src/main/java/com/fabio/crud/
│   │   ├── controllers/             # REST Controllers
│   │   ├── services/               # Business Logic
│   │   ├── models/                 # Entities & DTOs
│   │   ├── repositories/           # Data Access
│   │   ├── config/                 # Configurations
│   │   └── utils/                  # Mappers & Utilities
│   └── pom.xml                     # Maven Dependencies
├── finAppMobile/                   # Frontend React Native
│   ├── src/
│   │   ├── components/             # Reusable Components
│   │   ├── screens/               # App Screens
│   │   ├── services/              # API & Offline Services
│   │   ├── navigation/            # Navigation Setup
│   │   └── types/                 # TypeScript Types
│   └── package.json               # NPM Dependencies
├── Requirements.txt               # Requisitos do Projeto
└── README.md                     # Este arquivo
```

## 👨‍💻 Desenvolvedor

**Fábio Hiroshi Damazio Matsumura**
- Desenvolvimento Full-Stack
- Arquitetura Offline-First
- Experiência Mobile com React Native

## 📄 Licença

Este projeto é desenvolvido para fins educacionais e demonstração de competências técnicas.

---

