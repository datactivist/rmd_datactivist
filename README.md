<img src="https://github.com/rstudio/rmarkdown/blob/main/man/figures/logo.png" align="right" alt="rmarkdown" width="140" />

# rmarkdown

The **rmarkdown** package helps you create dynamic analysis documents that combine code, rendered output (such as figures), and prose. You bring your data, code, and ideas, and R Markdown renders your content into a polished document that can be used to:

- Do data science interactively within the RStudio IDE,
- Reproduce your analyses,
- Collaborate and share code with others, and
- Communicate your results with others.

R Markdown documents can be rendered to many output formats including HTML documents, PDFs, Word files, slideshows, and more, allowing you to focus on the content while R Markdown takes care of your presentation.

## Templates de R Markdown à la charte Datactivist

Installer le package via la commande suivante à éxecuter dans R :

```r
remotes::install_github('datactivist/rmd_datactivist')
```

Créer un nouveau document R Markdown à partir du menu :

- *File -> New File -> R Markdown -> From Template -> RMD Datactivist blanc* pour un document avec un arrière-plan blanc ;
- *File -> New File -> R Markdown -> From Template -> RMD Datactivist rose* pour un document avec un arrière-plan rosé.

Un exemple de R Markdown à la charte Datactivist s'ouvrira, appuyer sur le bouton '*knit*' pour compiler et visualiser la page HTML.
