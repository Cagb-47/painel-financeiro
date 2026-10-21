# Painel da Família

App simples de orçamento familiar para sair do aperto financeiro. Abre no celular, funciona sem instalar nada.

## Como usar
- **Hoje:** mostra quanto ainda pode gastar hoje. Toque em **+ Gasto**, digite o valor, escolha a categoria e pronto.
- **Espera 24h:** coloque ali compras fora do plano. Se a vontade passar, o valor vira economia.
- **Metas:** reserva em três etapas (sair do sufoco, guardar, prosperar) e o seu compromisso escrito.
- **Guia:** perguntas antes de comprar, roteiro para negociar a fatura e conversa com a família.

## Instalar no celular
- **Android (Chrome):** abra o link → menu ⋮ → **Instalar app** (ou "Adicionar à tela inicial").
- **iPhone (Safari):** abra o link → botão Compartilhar → **Adicionar à Tela de Início**.

Depois de instalado, abre em tela cheia e funciona mesmo sem internet.

## Dados e sincronização
Os dados ficam no Firebase (Firestore) do projeto da família e sincronizam entre os celulares. Cada celular entra com o **código da família**, digitado uma vez no primeiro acesso. O código não fica no repositório.

A configuração do Firebase fica em `config.js`.

## Publicar no GitHub Pages
Settings → Pages → Branch `main` / pasta `/ (root)` → Save. O app fica em `https://<usuario>.github.io/painel-financeiro/`.

Ideias aplicadas de *As Armas da Persuasão* (Cialdini), *Gatilhos Mentais* (Gustavo Ferreira) e *Como Fazer Amigos e Influenciar Pessoas* (Dale Carnegie).
