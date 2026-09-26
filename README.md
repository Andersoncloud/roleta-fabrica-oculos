# Roleta Promocional — Fábrica de Óculos

Aplicação web estática para publicação no GitHub Pages.

## Estrutura

- `index.html` — roleta completa.
- `.nojekyll` — evita processamento desnecessário pelo Jekyll.
- `README.md` — documentação.

## GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html`, `.nojekyll` e `README.md` para a raiz.
3. Vá em `Settings` → `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Selecione `main` e `/(root)`.
6. Salve e aguarde a publicação.

## Prêmios

Os prêmios podem ser alterados no início do JavaScript.

`probability` controla o peso relativo do sorteio. Com todos em `1`, todos possuem o mesmo peso.

## Importante

O sorteio é executado no navegador. Para uma promoção oficial que exija controle de tentativas, estoque, auditoria ou validação de prêmios, o sorteio deve ser realizado em um backend.
