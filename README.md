# Doctorial Thesis

[![compile-test](https://github.com/wenh06/Doctorial-Thesis/actions/workflows/compile.yml/badge.svg)](https://github.com/wenh06/Doctorial-Thesis/actions/workflows/compile.yml)
![GitHub Release Date - Published_At](https://img.shields.io/github/release-date/wenh06/Doctorial-Thesis)
![GitHub commits since latest release (by SemVer including pre-releases)](https://img.shields.io/github/commits-since/wenh06/Doctorial-Thesis/latest)

Doctorial thesis on the problem of counting multiplicities in a hypersurface over number fields.

## Usage

### Overleaf

One can compile via `Import from GitHub` using [Overleaf](https://www.overleaf.com/). This project is compiled successfully with

```
Compiler: XeLaTeX
Tex Live version: 2020
```

### Local

Run the following command to compile locally:

```python
python compile.py
```

then the compiled PDF file will be in the `build` directory.

Alternatively, one can use `latexmk` directly:

```bash
mkdir -p build
latexmk -xelatex -f main.tex
```
