# ITables and Jupytext: Lightning Talk at PyData London 2026

This is my lightning talk for PyData London 2026.

[View the presentation](https://mwouts.github.io/pydata_london_2026_itables_and_jupytext_lightning_talk/)

## ITables

Turns your Pandas and Polars DataFrames into interactive datatables with

```
import itables

itables.init_notebook_mode()
```

Uses datatables.net under the hood. Both ITables and datatables.net are free to use (MIT licence). Allan maintains datatables.net full-time — consider sponsoring him at [github.com/AllanJard](https://github.com/AllanJard).

## Jupytext

Text notebooks are user- and AI-friendly!

## Build the presentation

Install [pixi](https://pixi.sh), then run:

```sh
pixi run build     # render to _site/index.html
pixi run python -m http.server --directory _site
```

The presentation is authored in `slides.qmd` (Quarto + revealjs). Python code cells (e.g. the live ITables demo) are executed at build time. It is automatically deployed to GitHub Pages on every push to `main`.


