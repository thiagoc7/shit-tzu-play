# Arte do menu inicial

`casa-pixel.webp` é o fundo em uso. Vem da prancha da casa em pixel art gerada no Higgsfield em 13/09/2026 e aprovada pela família como direção v04 do 2D; o original fica em `2D/studies/v04/proposta-pixel.png` (2688×1520, RGB), com prompt, referências e custo em `2D/studies/v04/`.

A prancha é desenhada em blocos de 2 px, então a cópia do menu foi reduzida exatamente 2:1 com Python Pillow e reamostragem NEAREST (1344×760), o que cai em cima da grade nativa e mantém o pixel limpo; fica abaixo do teto de 1600 px de largura combinado para o fundo. Convertida em WebP com qualidade 82, sem canal alfa. Regerar com Pillow a partir do mesmo PNG sempre que a prancha aprovada mudar, mantendo a redução em múltiplo inteiro e o NEAREST — reduções fora da grade embaralham o pixel art.

`casa-pintada.webp` é a prancha antiga em direção pintada (guache e pastel), derivada de `2D/studies/v02/proposta-pintada.png`. Ficou no repositório apenas como histórico da v02 e não é mais referenciada por `menu/style.css`.

A direção de arte e a paleta estão em `2D/docs/DIRECAO-2D.md`. Os dois arquivos `.webp` seguem pelo Git LFS, pela regra `*.webp` do `.gitattributes`.
