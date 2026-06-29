# Logo Bionex

## Versões oficiais (corrigido com os arquivos SVG reais)

| Arquivo | Composição | Quando usar |
|---|---|---|
| `BIONEX_logo_1.svg` | "B" Verde `#8ec36d` + wordmark Dark `#1c2621` | **Padrão em fundos claros** |
| `BIONEX_logo_2.svg` | "B" Verde `#8ec36d` + wordmark Creme `#f2f2ea` | Fundos escuros |
| `BIONEX_logo_positivo.svg` | Tudo Dark `#1c2621` | Monocromática, fundos claros |
| `BIONEX_logo_negativo.svg` | Tudo Creme `#f2f2ea` | Monocromática, fundos escuros |

Os arquivos reais (SVG vetorial) ficam em [`../20-Assets/logos`](../20-Assets/logos). **Nunca recrie a logo à mão** — use sempre esses arquivos.

## Proporção (corrigida)

> ⚠️ O valor de **4,87:1** documentado numa versão anterior deste arquivo estava errado (vinha de uma estimativa da skill de design, sem acesso ao arquivo real). O viewBox real dos 4 SVGs é `0 0 1920 680`, ou seja, a proporção oficial é **≈2,82:1** (1920:680).

- Em PPTX/Figma: se a altura (`h`) for definida, a largura é `w = h × 2,8235`.
- Nunca distorça essa proporção.

## Área de proteção e malha construtiva

O manual de identidade visual oficial contém uma página de "malha construtiva" (grid de construção da logo) que define as proporções internas entre símbolo e wordmark. O arquivo-fonte dessa malha não foi enviado a este repositório; se precisar dela para um redesenho preciso, peça ao Matheus a página 5 do manual.

## Tamanho mínimo de exibição

- Em peças digitais (redes sociais, slides): altura mínima recomendada de **0,42"**, conforme padrão validado nas artes comerciais aprovadas.

## Favicon / ícone de app (exceção confirmada)

Para favicon e ícone de app, use **apenas o símbolo "B" em Verde**, sem o wordmark, dentro de um contêiner quadrado de cantos arredondados (convenção de plataforma) — não chanfrado. Confirmado no manual de identidade visual, pág. 9.

## Posicionamento padrão

- **Arte comercial (redes sociais)**: logo discreta, no rodapé inferior esquerdo.
- **Comunicado oficial (A4)**: logo no cabeçalho (header dark), versão `BIONEX_logo_2.svg`.
- **Apresentações**: logo no canto inferior de cada slide de conteúdo; versão cheia apenas no slide de capa.
- **Uniformes**: logo completa nas costas (versão creme sobre tecido verde), símbolo "B" isolado no peito — confirmado em foto real de uniforme aprovado.
- **Frota de veículos**: aplicação real confirmada — wrap diagonal verde/branco, logo `BIONEX_logo_positivo.svg`-equivalente (dark) sobre área branca.

## Uso incorreto

| ❌ Nunca | ✅ Sempre |
|---|---|
| Recriar a logo em SVG/vetor à mão | Usar os arquivos SVG oficiais de `../20-Assets/logos` |
| Distorcer a proporção ≈2,82:1 | Redimensionar mantendo a proporção travada |
| Logo grande dominando o header de uma arte comercial | Logo discreta no canto inferior |
| Aplicar a versão colorida sobre fundo verde | Usar a versão monocromática dark ou creme conforme o fundo |
| Usar wordmark completo em favicon/ícone de app | Usar apenas o símbolo "B" nesses contextos |
