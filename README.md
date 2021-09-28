# FNAL ECA Preproposal Template

This repository facilitates the combination of user content with central style and formatting provided by FNAL.

Users should enter content in the following locations:
1. [info.tex](./info.tex): details for cover page
2. [packages.tex](./packages.tex): any additional packages used
3. [content.tex](./content.tex): the actual proposal content

## Compilation

For standalone use, basic compilation is as simple as:
```bash
pdflatex main.tex
```

Depending on your use of references, bibliography tools, etc., you may need to run `pdflatex` multiple times and/or run `bibtex` explicitly.

This repository can also be used as a base to create new projects on [Overleaf](https://overleaf.com).
There are several methods for this:
1. New Project -> Import from GitHub (requires linking your GitHub account)
2. Upload Project (download [zip file](https://github.com/kpedro88/FNAL_ECA_Template/archive/refs/heads/main.zip))

This repository is set up on GitHub as a "template repository", so you can create your own repository based on it *without* needing to make a public fork, if desirable.
