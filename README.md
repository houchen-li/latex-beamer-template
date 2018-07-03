<div align="center">

# LaTeX Beamer Template

![LaTeX](https://img.shields.io/badge/LaTeX-Beamer-purple)
![XeLaTeX](https://img.shields.io/badge/engine-XeLaTeX-green)

A LaTeX Beamer presentation template using the Metropolis theme, featuring
New Computer Modern fonts with full CJK (Chinese) support via XeLaTeX.

</div>

## Features

- **Theme**: Metropolis (modern, minimalist)
- **Fonts**: New Computer Modern (serif, sans, math) + Source Han (CJK serif, sans)
- **CJK Support**: xeCJK with bundled font files (git submodule)
- **Build**: latexmk with XeLaTeX engine

## Usage

```bash
# Clone with fonts submodule
git clone --recurse-submodules git@github.com:houchen-li/latex-beamer-template.git

# Build
latexmk main.tex

# Clean
latexmk -C
```

## Project Structure

```
├── main.tex          # Main document
├── .latexmkrc        # latexmk configuration
└── fonts/            # Font files (git submodule)
```

## License

CC BY-NC-SA 3.0
