# 05 · Components

Padrões de componentes de UI da Bionex — para uso em sites, landing pages, apps e proteótipos Figma. Cores e tipografia seguem sempre [`../03-Colors`](../03-Colors) e [`../04-Typography`](../04-Typography).

## Forma característica

A Bionex usa **cantos chanfrados** (corner cut / chamfer), não cantos arredondados, como assinatura visual em cards e blocos de destaque. Pills/badges arredondados (`border-radius` = metade da altura) são aceitos apenas para badges pequenos.

```
Card dark chanfrado (referência de proporção de corte):
M 0 30 L 30 0 L (largura-30) 0 L largura 30
L largura (altura-30) L (largura-30) altura L 30 altura L 0 (altura-30) Z
```

## Buttons

| Tipo | Fundo | Texto | Uso |
|---|---|---|---|
| Primário | Dark | Creme | CTA principal (único por tela/card) |
| Secundário | Verde | Dark | Ação de apoio |
| Outline | Transparente, borda Dark | Dark | Ação terciária, baixa ênfase |

Regra de ouro: **um único CTA dominante por tela/card** — nunca dois botões primários competindo.

## Cards

- Fundo Creme (padrão) ou Dark (card de destaque/CTA).
- Cantos chanfrados.
- **Um único elemento dominante por card** — nunca 3 textos competindo pela atenção no mesmo card.

## Inputs & Forms

- Fundo Creme ou branco suave, borda 1px Cinza, foco com borda Verde dark.
- Label sempre visível acima do campo (não depender só de placeholder).
- Botão de envio = padrão "Primário" acima.

## Navbar

- Fundo Creme ou Dark.
- Logo à esquerda (versão conforme fundo — ver `../02-Identity/logo.md`).
- CTA principal (geralmente WhatsApp) sempre visível à direita, destacado.

## Footer

- Fundo Dark, texto Creme.
- Contém: logo, contatos oficiais (ver `../19-AI-Guidelines`), selos de licença (DEVISA · FVS · IPAAM · IBAMA) em linha pequena — nunca 4 selos grandes enfileirados.

## Tables

- Cabeçalho Dark/Creme, linhas zebradas em Creme/branco suave, nunca verde como cor de linha (contraste insuficiente — ver `../03-Colors/accessibility-contrast.md`).

## Badges / Alerts

- Badge de status positivo: fundo Verde, texto Dark.
- Alerta/aviso: fundo Dark, texto Creme, ícone de alerta em Verde stroke. Nunca usar vermelho genérico — não faz parte da paleta.

## Hero / CTA

- Estrutura coluna esquerda (texto) / coluna direita (imagem ou ilustração) — grid explícito, nunca elementos se sobrepondo.
- CTA final em card Dark chanfrado, com **um** elemento dominante (ex.: telefone gigante), conforme padrão validado em `../19-AI-Guidelines`.

## Sections / FAQ

- Perguntas em Dark bold, respostas em Cinza regular.
- Background alternando Creme / branco suave entre seções para criar ritmo, sem nunca usar branco puro como único fundo.

## Timeline / Gallery

- Timeline: marcadores em Verde, linha conectora em Cinza claro, texto em Dark.
- Gallery: fotos seguindo `../07-Photography` (nunca fotos genéricas de banco de imagens fora do estilo documentado).

## Modals

- Fundo Creme, título Dark bold, único CTA primário + um link de "fechar/cancelar" discreto (nunca dois botões de mesmo peso visual).
