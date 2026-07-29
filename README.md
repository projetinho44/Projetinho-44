# SIGRI370 v2.0.0 — Base de Produção

Sistema Integrado de Gestão para Registro de Imóveis 370.

Esta entrega transforma a demonstração estática em uma arquitetura com frontend, API e banco de dados central.

## Estrutura

```text
frontend/   Aplicação web estática para Vercel
backend/    API FastAPI, autenticação e regras de negócio
render.yaml Infraestrutura de API e PostgreSQL no Render
docs/       Implantação, escopo e segurança
```

## Funcionalidades incluídas

- autenticação e perfis;
- pessoas;
- protocolos;
- depósito prévio;
- créditos, débitos, complementações, aplicações e restituições;
- saldo e extrato;
- Livro de Controle de Depósito Prévio;
- Termo de Abertura e Termo de Encerramento;
- biblioteca de normas com pesquisa e histórico;
- pendências, checklist e produtividade;
- auditoria;
- configurações;
- backup e restauração de dados operacionais.

## Publicação

Leia primeiro:

`docs/DEPLOY-PASSO-A-PASSO.md`

## Aviso

A base técnica está pronta para implantação e testes multiusuário. Ela ainda precisa de configuração do ambiente, conferência dos modelos registrais, revisão das normas, testes de restauração e homologação jurídica, operacional, de segurança e LGPD antes do uso com dados reais.
