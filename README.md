# Wiki Ragnalothus

Wiki do servidor Ragnalothus, feita com [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

- As páginas ficam em `docs/` (Markdown). O menu fica em `mkdocs.yml` (`nav:`).
- Ver no PC: `python -m mkdocs serve` e abrir http://127.0.0.1:8000
- Publicar: enviar para a branch `main` no GitHub; o GitHub Actions (`.github/workflows/publicar.yml`) gera e publica sozinho.
