# Steve's 3rd Article/Manuscript Template, but in Quarto

This Quarto format will create spiffy PDF documents for you using Quarto. I talk [a bit about this template here](https://svmiller.com/blog/2023/05/a-third-rmarkdown-article-manuscript-template/) in its R Markdown form. This would be a basic port and slight improvement on the template as presented there.

# Installing the Template

In a terminal, run one of the following two commands.

`quarto use template svmiller/qarticle3`

The above would download all files in the Github repository, including the example .qmd file (`ms.qmd`). A sample `.bib` file in an `inst/` directory comes as well. Alternatively, you could run the following:
  
`quarto add svmiller/qarticle3`

This would just download the contents of the `_extensions` directory.

# Usage

The YAML of the the example .qmd file has several moving pieces. I'll add more a bit later as I'm still monkeying with it.