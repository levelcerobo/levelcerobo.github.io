# Level 0 · Guías gratis de Cubo Rubik 3x3

Página estática (GitHub Pages) con las guías imprimibles gratis de Level 0 Store.

**https://levelcerobo.github.io**

| Guía | Enlace directo |
|---|---|
| Método principiante: el cubo en 7 pasos, capa por capa | https://levelcerobo.github.io/guia-principiante.pdf |
| F2L: los 41 casos con su algoritmo | https://levelcerobo.github.io/guia-f2l.pdf |
| OLL: 2-look y los 57 casos | https://levelcerobo.github.io/guia-oll.pdf |
| PLL: 2-look y los 21 casos | https://levelcerobo.github.io/guia-pll.pdf |

Síguenos en [TikTok @level.cero.bo](https://www.tiktok.com/@level.cero.bo) y
[YouTube @LevelCeroBo](https://www.youtube.com/@LevelCeroBo).

## Contenido

- `index.html`: la página (HTML y CSS en un solo archivo, sin dependencias ni build).
- `guia-principiante.pdf`, `guia-f2l.pdf`, `guia-oll.pdf`, `guia-pll.pdf`: las guías.
- `img/`: logo y portadas.
- `.nojekyll`: GitHub Pages sirve los archivos tal cual.

## Actualizar una guía

Los PDF se generan en el repositorio de contenido
([`levelcerobo/content`](https://github.com/levelcerobo/content)): `rubik-guia-principiante/build.py`,
`rubik-guia-f2l/build.py`, `rubik-guia-oll/build.py` y `rubik-guia-pll/build.py`. Copia el PDF nuevo aquí **con el mismo nombre de archivo** y haz push.
Los QR impresos en los stickers apuntan a estas URLs, así que no se deben renombrar ni mover.
