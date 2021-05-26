# UNINOVE Beamer Template
[![GitHub license](https://badgen.net/github/license/kai-tub/latex_beamer_pure_minimalistic/)](https://github.com/kai-tub/latex_beamer_pure_minimalistic/blob/master/LICENSE)

Beamer Minimalistic template for UNINOVE presentations.

## Pure Minimalistic Theme

This template is based on the [Pure Minimalistic Theme](https://github.com/kai-tub/latex-beamer-pure-minimalistic)

## Required Packages

```bash
beamer textpos babel biblatex inputenc csquotes xpatch tikz pgfplots silence appendixnumberbeamer fira fontaxes mwe noto
```

## Plots

If you are plotting stuff and want to use the dark theme you'll probably want to add this to the preamble:

```latex
\usepackage{pgfplots}
\pgfplotsset{height=7cm,  % only if needed
             width=12cm,  % only if needed
             compat=1.18, % only if needed
             legend style = {fill = black, draw = white}}
```

## License
This software is released under the GNU GPL v3.0
[License](LICENSE).
