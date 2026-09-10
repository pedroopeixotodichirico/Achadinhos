# Achadinhos da Cris

Site de ofertas de afiliado. Publicado pelo GitHub Pages.

## Como funciona

- `produtos.json` — os achadinhos. É a única fonte da verdade.
- `index.html` — o site. Lê o `produtos.json` toda vez que alguém abre a página.
- `admin.html` — o painel da Cris. Grava direto neste repositório.
- `*.webp` — as fotos dos produtos.

A Cris publica pelo painel, o arquivo muda aqui, e o site já mostra na próxima
visita. Não existe processo de build, tarefa agendada nem computador que precise
estar ligado.

O primeiro produto da lista vira automaticamente o "Achadinho do dia" em destaque,
com a porcentagem de desconto calculada a partir dos dois preços.

## Mexer no visual

Edite o `index.html` direto. O CSS está todo lá dentro.
