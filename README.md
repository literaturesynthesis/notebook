<!-- Logo & Title -->

<h1 align="center">
  <br>
  <img src="images/readme/logo-readme.png" alt="Logo" width="200">
  <br>
  A Notebook on
  <br>
  Meta-analyses & Systematic reviews
  <br>
</h1>


<!-- View presentation -->

<br>
<p align="center"><a href="https://literaturesynthesis.github.io/notebook" target="_blank"><b>View online book</b></a>
</p>
<br>


<!-- Badges -->

<p align="center">

  <!-- Quarto -->
  <a href="https://quarto.org/">
    <img src="https://img.shields.io/badge/Made%20with-Quarto-blue.svg" alt="Quarto">
  </a>
  
  <!-- License -->
  <a href="https://choosealicense.com/licenses/cc-by-4.0/">
    <img src="https://img.shields.io/badge/License-CC%20BY%204.0-green.svg" alt="License CC BY 4.0">
  </a>
  
  <br/>
  
  <!-- Quarto render -->
  <a href="https://github.com/literaturesynthesis/notebook/actions/workflows/render-book.yml">
    <img src="https://github.com/literaturesynthesis/notebook/actions/workflows/render-book.yml/badge.svg" alt="GHA render">
  </a>
  
  <!-- GitHub deployment -->
  <a href="https://github.com/literaturesynthesis/notebook/actions/workflows/pages/pages-build-deployment">
    <img src="https://github.com/literaturesynthesis/notebook/actions/workflows/pages/pages-build-deployment/badge.svg" alt="GHA deploy">
  </a>
</p>


<!-- Table of content -->

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#usage">Usage</a> •
  <a href="#citation">Citation</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#acknowledgments">Acknowledgments</a>
</p>


## Overview

This repository contains files used to generate the online book [Meta-analyses & Systematic reviews](https://literaturesynthesis.github.io/notebook) based on [Quarto](https://quarto.org/).



## Usage

If you want to render the book locally, you need to install the following tools:

- [`R`](https://cran.r-project.org/) and [`RStudio Desktop`](https://posit.co/download/rstudio-desktop/)
- [`Quarto CLI`](https://quarto.org/docs/get-started/)

[Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) this repository and [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) your copy.


Then,

- edit the `_quarto.yml` to change the configuration of the book
- edit the `index.qmd` to modify the home page
- edit `.qmd` files in `chapters/` to modify book content

If you want to add a new chapter, create a new `.qmd` file in `chapters/` and add an entry in the `_quarto.yml` like this:

```yml
chapters:
  - chapters/chapter-name.qmd
```

To update the book, run in a **terminal** the following command:

```sh
quarto render
```



## Citation

Coming soon...


## Contributing

All types of contributions are encouraged and valued. For more information, check out our [Contributor Guidelines](https://github.com/literaturesynthesis/notebook/blob/main/CONTRIBUTING.md).

Please note that the `notebook` project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.


## Acknowledgments

This project has been developed for the [FRB-CESAB](https://www.fondationbiodiversite.fr/en/about-the-foundation/le-cesab/) training courses [program](https://frbcesab.github.io/content/courses.html).
