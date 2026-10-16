# Testes BDD com Gherkin e Cucumber - Patrick Ataíde Portfolio

## Objetivo

Projeto de testes funcionais em BDD (Behavior Driven Development) para o site [https://www.patrickataide.com.br/](https://www.patrickataide.com.br/) utilizando Gherkin e Cucumber.js (com Playwright).

Este repositório faz parte de uma série de projetos de demonstração de ferramentas de teste (Cypress, Playwright, Selenium, Robot Framework e BDD com Cucumber).

## Tecnologias

- [Cucumber.js](https://cucumber.io/docs/cucumber/)
- Gherkin (linguagem natural)
- Playwright (para automação do browser)
- GitHub Actions (CI/CD)

## Plano de Testes

O plano de testes funcionais está disponível em `plano-testes.csv`. Os cenários Gherkin estão também nos arquivos `.feature`.

## Como executar localmente

### Pré-requisitos

- Node.js 18+
- npm

### Instalação

```bash
npm install
npx playwright install
```

### Executar testes

```bash
npm test
```

## CI/CD

Os testes são executados automaticamente via GitHub Actions.

## Autor

Patrick Ataíde - [patrickataide.com.br](https://www.patrickataide.com.br/)
