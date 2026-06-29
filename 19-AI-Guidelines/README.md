# 19 · AI Guidelines — Documento-mestre

> **Esta é a pasta mais importante do repositório.** Cole o conteúdo abaixo (ou linke este arquivo) no início de qualquer conversa com uma IA que vai produzir material da Bionex.
>
> Atualizado com dados **oficiais e verificados** do manual de Identidade Visual (2025) e da Apresentação Comercial (2026) enviados pelo Matheus.

## 1. Identidade

Bionex Soluções Ambientais — "Nascida no coração da Amazônia". Serviços: Controle de pragas, Sanitização, Gerenciamento de Resíduos Comuns, Gerenciamento de Resíduos Perigosos/Infectantes (destinação final por incineração), Consultoria Ambiental, Desobstrução de tubulações, Higienização de caixas-d'água. Matriz em Manaus/AM. CNPJ 43.552.121/0001-59. Licenças: DEVISA · FVS · IPAAM · IBAMA.

**Missão oficial**: "Transformamos desafios ambientais em Soluções Sustentáveis."

## 2. Cores (oficial, ver `../03-Colors`)

| Token | HEX | CMYK oficial | Uso |
|---|---|---|---|
| Verde | `#8EC36D` | 51,0,71,0 | Logo, destaques, headlines de impacto |
| Creme | `#F2F2EA` | 7,4,10,0 | **Fundo padrão** (nunca branco puro) |
| Dark | `#1C2621` | 79,59,66,77 | Texto principal, cards escuros |
| Cinza | `#5E5E5E` | 58,48,47,37 | Texto secundário |

**Nunca** use texto Verde sobre fundo Creme para corpo de texto (contraste 1,83:1, insuficiente). Use Dark sobre Creme (13,84:1) como combinação de texto padrão.

## 3. Tipografia (ver `../04-Typography`)

Fonte única: **DM Sans**, 5 pesos oficiais (ExtraLight 200, Regular 400, Medium 500, SemiBold 600, Bold 700). Hero words curtas (40–60pt bold) em arte comercial; títulos 28–36pt em comunicado.

## 4. Logo (ver `../02-Identity`, arquivos reais em `../20-Assets/logos`)

4 versões SVG oficiais: `BIONEX_logo_1.svg` (verde+dark, fundos claros) · `BIONEX_logo_2.svg` (verde+creme, fundos escuros) · `BIONEX_logo_positivo.svg` (monocromática dark) · `BIONEX_logo_negativo.svg` (monocromática creme). Proporção oficial **≈2,82:1** (viewBox real 1920×680). Favicon/ícone de app: apenas o símbolo "B", container quadrado de cantos arredondados (não chanfrado).

## 5. Forma

**Cantos chanfrados** confirmados no manual oficial ("elementos de apoio", pág. 8) em cards/blocos de destaque — exceto favicon/ícone de app (ver acima).

## 6. Hierarquia e espaçamento

- Cada container = **um** elemento dominante.
- Grid de colunas explícito.
- Ícones de contato sempre no mesmo eixo Y, mesmo tamanho, mesmo gap.

## 7. Layout — duas mentalidades diferentes

| Comunicado/documento | Arte comercial |
|---|---|
| Header → corpo → footer | Hook visual em 1 segundo |
| Carga informacional alta | Tipografia como herói (1-2 palavras grandes) |

## 8. Fotografia (ver `../07-Photography`)

Foto oficial já em uso: profissional com capacete verde, colete verde, em ambiente real de trabalho — confirmado tanto na apresentação comercial quanto no manual de identidade. Estilo documentário real, nunca banco de imagens genérico.

## 9. Ícones (ver `../09-Icons`)

`FaGlobe` para site, `FaWhatsapp`, `FaInstagram`, `FaEnvelope`, `FaMapMarkerAlt`.

## 10. Tom de voz (ver `../01-Brand/tone-of-voice.md`)

Direto, técnico, institucional, sem urgência falsa — confirmado pelo texto real dos materiais oficiais.

## 11. UX / UI

Um único CTA primário por tela/card. Logo discreta no canto inferior em arte comercial.

## 12. Copywriting / Marketing

Ver `../12-Marketing`. Frases curtas, sem jargão genérico, sem urgência falsa. Exemplo real: "Transformamos desafios ambientais em Soluções Sustentáveis."

## 13. Dados comerciais oficiais (ver `../13-Commercial`)

CNPJ 43.552.121/0001-59 · Matriz Manaus/AM · WhatsApp (092) 99526-8752 · bionexambiental.com.br · @bionex.ambiental.

## 14. Acessibilidade

Contraste WCAG AA — valores calculados em `../03-Colors/accessibility-contrast.md` (não afetados pela correção de CMYK, pois usam RGB).

## 15. Consistência — checklist final antes de entregar qualquer peça

1. [ ] Nenhum texto estourou seu container?
2. [ ] Nenhum texto sobrepondo a ilustração/foto?
3. [ ] Nenhuma URL passou da margem?
4. [ ] Telefone em uma única linha?
5. [ ] Card de CTA com apenas 1 elemento dominante?
6. [ ] Logo correta para o fundo (ver tabela do item 4), proporção ≈2,82:1 mantida?
7. [ ] Ícones de contato alinhados no mesmo eixo?
8. [ ] Nenhum número/prazo/regulamentação não confirmado foi inventado?
9. [ ] Endereço usado é o de Manaus (matriz confirmada), não o de Maués desatualizado?
10. [ ] Logo não foi recriada — usou o SVG real de `../20-Assets/logos`?

Se qualquer item falhar, refaça antes de entregar.
