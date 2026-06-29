# 09 · Icons

## Sistema recomendado

Use **react-icons** (`Fa*` — Font Awesome) como padrão já validado nas peças aprovadas da marca. Lucide e Phosphor são alternativas aceitáveis para contextos onde react-icons não estiver disponível (ex.: Figma), desde que mantenham o estilo outline simples, sem preenchimento pesado.

## Mapeamento oficial (validado)

| Para | Ícone correto | Nunca usar |
|---|---|---|
| Site / web | `FaGlobe` | `FaPaperPlane` (parece Telegram) |
| WhatsApp | `FaWhatsapp` | — |
| Instagram | `FaInstagram` | — |
| E-mail | `FaEnvelope` | — |
| Endereço | `FaMapMarkerAlt` | — |
| CTA / seta de ação | `FaArrowRight` | — |
| Confirmação/check | `FaCheck` ou `FaCheckCircle` | — |

## Especificação de renderização

- Renderizar em `size: 256` (alta resolução de origem) e exibir entre **0,16" e 0,45"** na peça final.
- Todos os ícones de uma mesma linha de contato devem ficar **no mesmo eixo Y, mesmo tamanho, mesmo gap** em relação ao texto ao lado — nunca alinhamento improvisado.
- Cor do ícone segue a regra de contraste do fundo onde ele está (ver `../03-Colors/accessibility-contrast.md`).
