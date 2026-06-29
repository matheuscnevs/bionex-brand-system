# Paleta Oficial Bionex

Fonte: skill oficial de design da Bionex (v7). Conversões HEX→RGB→CMYK calculadas de forma determinística — os valores de CMYK são uma conversão matemática padrão (sem perfil de cor de impressão); **para impressão profissional, valide a prova de cor com a gráfica antes de fechar o arquivo**.

| Token | HEX | RGB | CMYK (aprox.)* | Uso |
|---|---|---|---|---|
| **Verde** | `#8EC36D` | 142, 195, 109 | 27, 0, 44, 24 | Logo, headlines de impacto, destaques |
| **Verde stroke** | `#7AB55A` | 122, 181, 90 | 33, 0, 50, 29 | Outlines, ícones, headlines em texto colorido |
| **Verde dark** | `#6A9F4A` | 106, 159, 74 | 33, 0, 53, 38 | Pré-headers, labels com tracking |
| **Creme** | `#F2F2EA` | 242, 242, 234 | 0, 0, 3, 5 | **Fundo padrão** (nunca branco puro) |
| **Dark** | `#1C2621` | 28, 38, 33 | 26, 0, 13, 85 | Texto principal, cards escuros, footer |
| **Cinza** | `#5E5E5E` | 94, 94, 94 | 0, 0, 0, 63 | Texto secundário, legendas legais |

*\* CMYK calculado via conversão RGB→CMYK padrão (fórmula naive). Não substitui prova de cor física.*

## Regra de fundo

O fundo padrão da marca é **sempre Creme (`#F2F2EA`)**, nunca branco puro (`#FFFFFF`). Branco puro quebra a identidade — se precisar de um fundo "claro", use Creme.

## Hierarquia de aplicação

1. **Verde** é a cor de impacto — usar com moderação, em headlines e elementos de destaque. Não pintar grandes áreas de fundo em Verde puro (ver razão de contraste abaixo).
2. **Dark** é a cor de texto e de cards escuros — funciona como "segunda cor de fundo" em blocos de CTA.
3. **Creme** é o fundo base de qualquer peça.
4. **Cinza** é só para texto de apoio/legal, nunca para elementos estruturais.

Ver razões de contraste exatas em [`accessibility-contrast.md`](./accessibility-contrast.md) antes de decidir qual cor de texto usar sobre qual fundo.
