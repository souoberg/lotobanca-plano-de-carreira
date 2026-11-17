# Plano de Carreira lotobanca — Proposta para validação

Página de apresentação do conceito de **Plano de Carreira para vendedores do lotobanca**, em linguagem de negócio, para validação do cliente.

## Link público

**https://souoberg.github.io/lotobanca-plano-de-carreira/**

> A página tem `<meta name="robots" content="noindex, nofollow">` para não ser indexada por buscadores.

## O que a página contém

- Conceito do programa (carreira, metas/sequência e ranking)
- Benefícios para a banca
- Como os pontos são contados (R$ 1 vendido = 1 ponto, exemplo)
- Escada de níveis e prêmios (exemplo)
- Metas diárias + sequência (7/15/30 dias)
- Ranking diário
- Como seria no lotobanca (experiência do vendedor e painel da banca)
- Personalização: cada banca com o seu próprio plano
- Regras transparentes
- Checklist de validação com observações por área e botão de copiar respostas
- Botão de imprimir/salvar PDF

## Observações do cliente

Cada área da página tem um campo de observação. As anotações e o checklist são salvos **apenas no navegador do cliente** (`localStorage`, chave `lbpc-avaliacao-v1`). O botão **“Copiar minhas respostas”** gera um texto com os pontos marcados e todas as observações por área para o cliente enviar ao time.

## Como editar

Todo o conteúdo está em `index.html` (HTML + CSS + JS, sem build). Basta editar o arquivo, commitar e dar push — o GitHub Pages publica automaticamente.

## Deploy

Publicado via GitHub Pages a partir da branch `main`, na raiz do repositório.

```bash
git add .
git commit -m "Atualiza proposta"
git push origin main
```
