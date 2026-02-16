# FDRI Gridded Data

A Quarto website project for FDRI gridded data workshops.

## Requirements
- [Quarto](https://quarto.org/)
- [uv](https://docs.astral.sh/uv/)

## Quick Start

1. Sync dependencies with uv:
    ```bash
    uv sync
    ```
2. Add the quarto-live extension:
    ```bash
    quarto add r-wasm/quarto-live
    ```
3. Preview the Quarto site:
    ```bash
    quarto preview
    ```

## Publish
1. Render the website:
    ```bash
    quarto render
    ```
2. Add and push the `/docs` folder to github:
    ```bash
    git add docs/
    git push
    ```

## Import a python notebook `*.ipynb`
Python notebooks (`.ipynb`) can be imported and converted to quarto (`.qmd`) using the following command:
```bash
quarto convert
```
