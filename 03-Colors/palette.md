# Paleta Oficial Bionex

Fonte: **Manual de Identidade Visual oficial da Bionex** (Proposta Identidade Visual BIONEX, 2025) — valores de HEX/RGB/CMYK extraídos diretamente da página "paleta de cores" do manual, não calculados.

| Token | HEX | RGB | CMYK (oficial) | Uso |
|---|---|---|---|---|
| **Verde** | `#8EC36D` | 142, 195, 109 | 51, 0, 71, 0 | Logo, headlines de impacto, destaques |
| **Creme** | `#F2F2EA` | 242, 242, 234 | 7, 4, 10, 0 | **Fundo padrão** (nunca branco puro) |
| **Dark** | `#1C2621` | 28, 38, 33 | 79, 59, 66, 77 | Texto principal, cards escuros, footer |
| **Cinza** | `#5E5E5E` | 94, 94, 94 | 58, 48, 47, 37 | Texto secundário, legendas legais |

> ⚠️ **Correção**: a versão anterior deste documento trazia valores de CMYK **calculados por fórmula matemática** (RGB→CMYK genérica), com a ressalva de que precisariam de validação. Agora temos os valores **oficiais do próprio manual de identidade visual**, que substituem os calculados ‒ eles são bem diferentes (ex.: Dark era calculado como C26 M0 Y13 K85; o valor oficial real é C79 M59 Y66 K77). Use sempre os valores desta tabela.
>
> Os tokens **Verde stroke** (`#7AB55A`) e **Verde dark** (`#6A9F4A`) documentados anteriormente vinham da skill de design (não do manual oficial) — mantenha-os como tons de apoio válidos para outline/labels, mas saiba que não aparecem na paleta principal de 4 cores do manual oficial.

## Regra de fundo

O fundo padrão da marca é **sempre Creme (`#F2F2EA`)**, nunca branco puro (`#FFFFFF`). Confirmado tanto na skill de design quanto no manual oficial (todas as páginas de fundo claro do manual usam o tom creme, nunca branco).

## Hierarquia de aplicação

1. **Verde** é a cor de impacto — usar com moderação, em headlines e elementos de destaque. Não pintar grandes áreas de fundo em Verde puro (ver razão de contraste abaixo) — excepcionalmente, o manual oficial mostra o Verde como fundo cheio em 1 das 4 versões monocromáticas da logo (pág. 3), o que é aceitável para essa aplicação específica de identidade, mas não como fundo de texto corrido.
2. **Dark** é a cor de texto e de cards escuros — funciona como "segunda cor de fundo" em blocos de CTA.
3. **Creme** é o fundo base de qualquer peça.
4. **Cinza** é só para texto de apoio/legal, nunca para elementos estruturais.

Ver razões de contraste exatas em [`accessibility-contrast.md`](./accessibility-contrast.md) antes de decidir qual cor de texto usar sobre qual fundo (esses cálculos de contraste continuam válidos — baseiam-se no RGB, que não mudou).
