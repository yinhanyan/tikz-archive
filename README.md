# tikz-archive
Archive of my PGF/TikZ works.

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

[[![Householder Reflector](images/Householder_Reflector.svg)]](./Householder_Reflector.tex)

[[![Integration trick for series](images/Integration_Trick_for_Series.svg)]](./Integration_Trick_for_Series.tex)

## Compile method

```bash
lualatex --output-format=dvi <file_name>.tex
dvisvgm --no-fonts <file_name>
```

White background:
```tex
\special{background White}
```