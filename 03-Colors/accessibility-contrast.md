# Contraste e Acessibilidade

Razões de contraste calculadas pela fórmula oficial WCAG (luminância relativa). Critério: **AA texto normal ≥ 4,5:1** · **AA texto grande/título ≥ 3:1**.

| Combinação | Razão | AA texto normal | AA texto grande/título |
|---|---|---|---|
| Dark sobre Creme | **13,84:1** | ✅ Passa | ✅ Passa |
| Creme sobre Dark | **13,84:1** | ✅ Passa | ✅ Passa |
| Cinza sobre Creme | **5,76:1** | ✅ Passa | ✅ Passa |
| Dark sobre Verde | **7,55:1** | ✅ Passa | ✅ Passa |
| Branco sobre Verde dark | **3,15:1** | ❌ Falha | ✅ Passa (apenas título/headline grande) |
| Verde sobre Creme | **1,83:1** | ❌ Falha | ❌ Falha |
| Creme sobre Verde | **1,83:1** | ❌ Falha | ❌ Falha |

## Regras práticas

- **Nunca** use texto Verde (`#8EC36D`) sobre fundo Creme para corpo de texto — a razão de 1,83:1 é muito baixa para qualquer leitura confortável, mesmo em título. Use Verde apenas como elemento gráfico (ícone, stroke, destaque pontual de 1-2 palavras em fonte grande/bold), nunca como cor de texto corrido.
- **Sempre** use **Dark** como cor de texto sobre Creme (corpo e títulos) — é a combinação de maior contraste do sistema.
- Para texto sobre fundo Verde (cards, badges), use **Dark**, nunca Creme/Branco — a diferença de contraste é grande (7,55:1 vs 1,83:1).
- Branco sobre Verde dark só é seguro para **títulos grandes**, nunca para texto corrido.
