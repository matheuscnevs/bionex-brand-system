# 19 · AI Guidelines — Documento-mestre

> **Esta é a pasta mais importante do repositório.** Cole o conteúdo abaixo (ou linke este arquivo) no início de qualquer conversa com uma IA que vai produzir material da Bionex.

## 1. Identidade

Bionex Soluções Ambientais — controle de pragas, dedetização, sanitização, gerenciamento de resíduos (incluindo infectantes), caixas d'água, desentupimento de fossas, consultoria ambiental. Base no Amazonas (matriz Maués, filial Manaus). Licenças: DEVISA · FVS · IPAAM · IBAMA.

## 2. Cores (ver `../03-Colors`)

| Token | HEX | Uso |
|---|---|---|
| Verde | `#8EC36D` | Logo, destaques, headlines de impacto |
| Verde stroke | `#7AB55A` | Outlines, ícones |
| Verde dark | `#6A9F4A` | Pré-headers, labels |
| Creme | `#F2F2EA` | **Fundo padrão** (nunca branco puro) |
| Dark | `#1C2621` | Texto principal, cards escuros |
| Cinza | `#5E5E5E` | Texto secundário |

**Nunca** use texto Verde sobre fundo Creme para corpo de texto (contraste 1,83:1, insuficiente). Use Dark sobre Creme (13,84:1) como combinação de texto padrão.

## 3. Tipografia (ver `../04-Typography`)

Fonte única: **DM Sans**. Hero words curtas (40–60pt bold) em arte comercial; títulos 28–36pt em comunicado.

## 4. Forma

**Cantos chanfrados** (não arredondados) em cards/blocos de destaque. Radius total apenas em pills/badges pequenos.

## 5. Hierarquia e espaçamento

- Cada container = **um** elemento dominante. Nunca 3 textos competindo no mesmo card.
- Grid de colunas explícito (texto de um lado, imagem do outro) — nunca elementos se sobrepondo.
- Ícones de contato sempre no mesmo eixo Y, mesmo tamanho, mesmo gap.

## 6. Layout — duas mentalidades diferentes

| Comunicado/documento | Arte comercial |
|---|---|
| Header → corpo → footer | Hook visual em 1 segundo |
| Carga informacional alta | Tipografia como herói (1-2 palavras grandes) |
| Moldura e selos enfileirados aceitáveis | Sem moldura, sem header grande, sem 4 selos enfileirados |

Identifique qual é o caso **antes** de desenhar a peça (ver `../18-Documents` vs `../17-Social-Media`).

## 7. Fotografia e ilustração (ver `../07-Photography`, `../08-Illustrations`)

- Fotografia: estilo documentário real (EPI completo, equipamento moderno, contexto amazônico) — nunca banco de imagens genérico.
- Sem foto disponível → ilustração SVG outline + cores chapadas, reconhecível em <1 segundo (tabela de referência por serviço em `../08-Illustrations`).
- Toda peça comercial precisa de imagem — tipografia pura sem elemento visual parece slide de PowerPoint.

## 8. Ícones (ver `../09-Icons`)

Use `FaGlobe` para site (nunca `FaPaperPlane`), `FaWhatsapp`, `FaInstagram`, `FaEnvelope`, `FaMapMarkerAlt`. Mesmo eixo Y, mesmo tamanho.

## 9. Tom de voz (ver `../01-Brand/tone-of-voice.md` — rascunho)

Direto, técnico quando necessário, honesto sobre prazos. **Nunca** "24h"/"emergência" sem confirmação real.

## 10. UX / UI

- Um único CTA primário por tela/card (ver `../05-Components`).
- Logo discreta no canto inferior em arte comercial; versão completa só na capa de apresentações/comunicados.

## 11. Copywriting / Marketing

Ver `../12-Marketing`. Palavras curtas, sem jargão genérico, sem urgência falsa.

## 12. Acessibilidade

Todas as combinações de texto/fundo devem atingir contraste WCAG AA (≥4,5:1 texto normal, ≥3:1 título) — valores calculados em `../03-Colors/accessibility-contrast.md`.

## 13. Consistência — checklist final antes de entregar qualquer peça

1. [ ] Nenhum texto estourou seu container?
2. [ ] Nenhum texto sobrepondo a ilustração/foto?
3. [ ] Nenhuma URL passou da margem? (`bionexambiental.com.br` cabe em 10,5pt)
4. [ ] Telefone em uma única linha?
5. [ ] Card de CTA com apenas 1 elemento dominante?
6. [ ] Logo legível mas não dominante, versão correta para o fundo usado?
7. [ ] Ícones de contato alinhados no mesmo eixo?
8. [ ] Nenhum número/prazo/regulamentação não confirmado foi inventado?
9. [ ] Contraste de cor verificado contra `../03-Colors/accessibility-contrast.md`?
10. [ ] Logo não foi recriada — usou o PNG real de `../20-Assets`?

Se qualquer item falhar, refaça antes de entregar.
