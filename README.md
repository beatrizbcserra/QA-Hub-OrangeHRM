# QA Hub — OrangeHRM


![Cypress Tests](https://github.com/beatrizbcserra/qa-hub-orangehrm/actions/workflows/cypress.yml/badge.svg)
![k6 Performance](https://github.com/beatrizbcserra/qa-hub-orangehrm/actions/workflows/k6.yml/badge.svg)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)


> Projeto integrado de QA sobre o OrangeHRM: cobertura completa em 5 camadas —
> testes manuais, automação E2E, performance, mobile e CI/CD.


## Sobre o Projeto


O **QA Hub** demonstra maturidade em Quality Assurance aplicada a um sistema
real de RH. Cada camada foi projetada para cobrir riscos específicos do produto,
seguindo boas práticas de documentação, automação e entrega contínua.


| Camada          | Ferramenta        | Status       |
|-----------------|-------------------|--------------|
| Testes Manuais  | Markdown + Excel  | ✅ Concluído |
| Automação E2E   | Cypress           | 🚧 Em andamento |
| Performance     | k6                | 🔜 Planejado |
| Mobile          | Appium            | 🔜 Planejado |
| CI/CD Pipeline  | GitHub Actions    | ✅ Concluído |


## Como Rodar


```bash
# Clone o repositório
git clone https://github.com/beatrizbcserra/qa-hub-orangehrm


# Instale as dependências
npm install


# Execute os testes Cypress
npx cypress open


# Execute os testes de performance
k6 run performance/k6/scenarios/load-test.js
```


## Documentação


- [Plano de Teste](docs/test-plan.md)
- [Casos de Teste — Login](docs/test-cases/TC_LOGIN.md)
- [Casos de Teste — Funcionários](docs/test-cases/TC_EMPLOYEE.md)
- [Bug Reports](docs/bug-reports/)
