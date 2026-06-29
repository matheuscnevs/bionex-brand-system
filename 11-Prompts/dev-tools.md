# Prompts — Lovable / Bolt / Cursor / v0

Use como instrução de projeto (system prompt / project rules) antes de gerar qualquer tela:

```
Design system: Bionex Soluções Ambientais.

Cores (Tailwind custom ou CSS vars):
  --bionex-green: #8EC36D;
  --bionex-green-stroke: #7AB55A;
  --bionex-green-dark: #6A9F4A;
  --bionex-cream: #F2F2EA;   /* fundo base, nunca usar #FFFFFF puro */
  --bionex-dark: #1C2621;    /* texto principal */
  --bionex-gray: #5E5E5E;    /* texto secundário */

Fonte: "DM Sans" (Google Fonts), pesos 400/500/700.

Forma: cantos chanfrados em cards/seções de destaque (clip-path
poligonal), border-radius padrão apenas em badges/pills pequenos.

Regra de contraste: nunca usar texto verde (#8EC36D) sobre fundo creme
para corpo de texto — contraste insuficiente (1.83:1). Texto principal
é sempre Dark sobre Creme, ou Creme sobre Dark.

Componentes seguem ../05-Components/README.md deste repositório.
```
