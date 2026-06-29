# 🌿 BIONEX Brand OS

**Fonte única de verdade da marca Bionex Soluções Ambientais.**

Este repositório é o Brand Operating System oficial da Bionex. Todo material produzido — apresentações, landing pages, propostas comerciais, posts, documentos, interfaces, campanhas e qualquer geração por IA (Claude, ChatGPT, Midjourney, Figma AI, etc.) — **deve seguir este sistema**.

> ⚠️ **Status do conteúdo**: as pastas de identidade visual (cores, tipografia, ícones, formas, componentes) contêm dados **verificados** com a skill oficial da Bionex. As pastas de **estratégia de marca** (`01-Brand`) contêm **rascunhos** propostos que ainda precisam de validação do Matheus antes de serem tratados como oficiais — ver aviso em `01-Brand/README.md`.

---

## Visão geral

A Bionex Soluções Ambientais atua em controle de pragas, dedetização, sanitização, gerenciamento de resíduos (incluindo infectantes), caixas d'água, desentupimento de fossas e consultoria ambiental, com base no Amazonas (matriz em Maués, filial em Manaus). Esse contexto real é o que orienta toda a direção de marca abaixo — nada aqui foi pensado de forma genérica.

## Propósito deste repositório

1. Eliminar inconsistência visual entre peças feitas por pessoas e por IA diferentes.
2. Servir de contexto único que qualquer ferramenta de IA pode ler antes de gerar uma peça da Bionex.
3. Reduzir retrabalho: em vez de reexplicar a marca a cada prompt, aponte para este repositório.

## Como utilizar

- **Pessoas**: comece pelo `README.md` de cada pasta numerada — ele resume o conteúdo da pasta e linka os arquivos internos.
- **IA generativa**: comece por `19-AI-Guidelines/README.md`. Esse arquivo é o resumo operacional de todo o sistema, pensado para ser colado (ou referenciado) em um prompt.
- **Antes de criar qualquer peça**: confira `03-Colors`, `04-Typography`, `02-Identity` (uso de logo) e o checklist de proibições em `19-AI-Guidelines`.

## Estrutura do projeto

| Pasta | Conteúdo |
|---|---|
| `01-Brand` | Missão, visão, valores, propósito, brand story, personalidade, posicionamento, tom de voz, palavras-chave, o que não fazer — **rascunhos a validar** |
| `02-Identity` | Logo, área de proteção, tamanhos mínimos, versões, uso incorreto |
| `03-Colors` | Paleta oficial, HEX/RGB/CMYK, contraste e acessibilidade, combinações permitidas |
| `04-Typography` | DM Sans, hierarquia tipográfica para comunicado e arte comercial |
| `05-Components` | Padrões de UI: botões, cards, inputs, navbar, tabelas, badges, hero, CTA, FAQ, timeline, modais |
| `06-Layouts` | Padrões de página: landing page, institucional, blog, serviço, comercial, dashboard, app |
| `07-Photography` | Direção fotográfica (o que mostrar / o que evitar) |
| `08-Illustrations` | Estilo de ilustração SVG por serviço |
| `09-Icons` | Sistema de ícones e regras de uso |
| `10-Templates` | Estruturas para propostas, orçamentos, apresentações, relatórios, posts, banners |
| `11-Prompts` | Prompts prontos para Claude, ChatGPT, Midjourney, Ideogram, Figma AI, Lovable, Bolt, Cursor, v0 |
| `12-Marketing` | Copywriting, SEO, Ads, redes sociais, e-mail marketing |
| `13-Commercial` | Padrões de proposta, orçamento, negociação, follow-up |
| `14-Proposals` | Templates de proposta prontos para preencher |
| `15-Presentations` | Estrutura de apresentações de slides |
| `16-Website` | Padrões de homepage, sobre, serviços, contato, blog, FAQ |
| `17-Social-Media` | Padrões de feed, stories, reels, carrossel, anúncios |
| `18-Documents` | Padrão de comunicados oficiais (A4) |
| `19-AI-Guidelines` | **Documento-mestre** para qualquer IA produzir no padrão Bionex |
| `20-Assets` | Índice dos arquivos binários oficiais (logos, ícones, mockups) |
| `21-Examples` | Exemplos de referência de peças aprovadas |
| `22-Internal` | Changelog e processo de revisão interno |

## Convenções

- Todo conteúdo em Markdown, com tabelas sempre que possível.
- Arquivos `README.md` em cada pasta funcionam como índice.
- Nunca duplicar informação — sempre linkar para a fonte (ex.: cores são definidas uma vez em `03-Colors/palette.md` e referenciadas nas demais pastas).
- Valores numéricos verificáveis (HEX, contraste WCAG) vêm de cálculo determinístico, não de estimativa.
- Conteúdo estratégico/de copy é marcado como **rascunho** até validação humana — nunca tratado como fato institucional sem revisão.

## Integração com Claude

Cole o conteúdo de `19-AI-Guidelines/README.md` no início de qualquer conversa em que o Claude for gerar uma peça Bionex (post, proposta, slide, landing page). Os prompts prontos de `11-Prompts/claude.md` já fazem essa referência automaticamente.

## Integração com Figma

- Use os tokens de `03-Colors/palette.md` para criar as *color styles* da biblioteca Figma.
- Use a hierarquia de `04-Typography/dm-sans.md` para os *text styles*.
- Os componentes de `05-Components` servem como especificação para a biblioteca de componentes Figma.
- Para Figma AI, use o prompt em `11-Prompts/figma-ai.md`.

## Integração com IA generativa

Ferramentas de imagem (Midjourney, Ideogram, GPT Image) **não devem recriar a logo** — apenas gerar fotografia/ilustração de apoio seguindo `07-Photography` e `08-Illustrations`. A logo real (PNG) é sempre aplicada depois, via `20-Assets`.

## Boas práticas

1. Sempre confira `19-AI-Guidelines` antes de gerar uma peça nova.
2. Nunca invente números, prazos ou regulamentações sobre os serviços — confirme com o Matheus (ver `13-Commercial/README.md`).
3. Nunca recrie a logo em vetor/SVG — use os arquivos reais de `20-Assets`.
4. Toda peça comercial passa pelo checklist de QA visual antes de ser entregue (ver `19-AI-Guidelines`).
