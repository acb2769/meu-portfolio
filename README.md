![Status do Deploy](https://github.com/acb2769/meu-portfolio/actions/workflows/cd.yml/badge.svg)
![Status da Validacao CI](https://github.com/acb2769/meu-portfolio/actions/workflows/ci.yml/badge.svg)

# Portfólio Profissional - Esteira CI/CD

Este repositório contém meu portfólio profissional automatizado com GitHub Actions para validação contínua (CI) e entrega contínua (CD) no GitHub Pages.

## Funcionalidades da Pipeline
* **Proteção de Branch:** Validação de HTML, tamanho de arquivos (< 500KB), bloqueio de palavras sensíveis e checagem de links quebrados.
* **Matrix Strategy:** Testes executados simultaneamente no Node.js 18 e Node.js 20.
* **Deploy Automático:** Publicação direta no GitHub Pages após o merge na `main`.
