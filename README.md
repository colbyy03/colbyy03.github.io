# colbyy03.github.io

This repository serves as a personal Quarto website and professional portfolio. It includes a home page, about page, and blog posts including reproducable computational posts for R and Python.

## Requirements

- [Quarto](https://quarto.org) (version 1.10.18)
- [uv](https://docs.astral.sh/uv/) (version 0.12.7)
- R (version 4.6.1)

## Build Instructions

From the top level of the repo:

```sh
git clone git@github.com:colbyy03/colbyy03.github.io.git
cd colbyy03@github.io
```

Set up the python environment:

\`\`\`sh
uv sync
\`\`\`

Start an R session:

\`\`\`sh
R
\`\`\`

Set up the R environment:

\`\`\`R
renv::restore()
\`\`\`

Select "y":
\`\`\`sh
y
\`\`\`

Close the R session:

\`\`\`R
q()
\`\`\`

Select "n":

\`\`\`sh
n
\`\`\`

Render the site:

\`\`\`sh
uv run quarto render
\`\`\`

## Local site viewing

The built site is accessible in `docs/` locally. Open the `docs/index.html` folder to view it, or:

View the site:

\`\`\`sh
quarto preview
\`\`\`

## Data source

- [Star Wars API](https://swapi.dev/), via dplyr package. No network access needed.
- [Palmer Penguins](https://allisonhorst.github.io/palmerpenguins/), Palmer Station Antarctica LTER. No network access needed.