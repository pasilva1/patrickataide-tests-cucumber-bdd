# Comandos Essenciais - Cucumber.js + Playwright (BDD puro)

## Instalação completa

```bash
npm install
npx playwright install --with-deps
```

## Rodar todos os testes

```bash
npm test
# ou
npx cucumber-js
```

## Rodar somente um arquivo .feature

```bash
npx cucumber-js features/portfolio.feature
```

## Rodar somente um cenário (pelo nome)

```bash
npx cucumber-js features/portfolio.feature --name "FT-001"
```

## Rodar somente cenários com tag

```bash
npx cucumber-js --tags "@smoke"
```

## Rodar em modo dry-run (sem executar)

```bash
npx cucumber-js --dry-run
```

## Limpar e reinstalar

```bash
rm -rf node_modules package-lock.json
npm install
npx playwright install
```
