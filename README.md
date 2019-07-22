This repo was created during the CSAMA2019 workshop in Brixen!

- [A gentle introduction to git and Github](https://lgatto.github.io/github-intro/)
- [Happy Git and Github](https://happygitwithr.com)
- [Version Control with Git and SVN](https://support.rstudio.com/hc/en-us/articles/200532077?version=1.1.463&mode=desktop)

## Adding a remote

Adding a remote and pushing via ssh (requires ssh key set up):

```
git remote add origin git@github.com:lgatto/rmd_github.git
git push -u origin master
```

Adding a remote and pushing via https (using password when pushing):

```
git remote add origin https://github.com/lgatto/rmd_github.git
git push -u origin master
```

## Notes


### Set up

-   Create a new **project** in RStudio, using `git` (requires installation of `git`).
-   Stage and commit `.gitignore` and `.Rproj` files (1st time point in repo history).
-   Add an Rmd file
-   Exercise: Stage and commit it, view history.
-   Modify the Rmd, commit it, view history.

### R markdown

-   Describe and experiment with Rmd.
-   Basic markdown syntax.
-   Knitting document.
-   R code chunk.
-   Code chunk parameters: `eval`, `echo`.

### Github

-   Show Github
-   For those that don't have an account, create one.
-   Create Github repo.
-   Add remote to local repository and push.
-   Show issues.
-   Exercise: as to comment or create a new issue.
-   Show how to render the html using rawgit.
-   Exercise: add a README.md file

### More (depending on time)

-   Caching code chunk, using `Sys.sleep()`.
-   Github pages

#### Examples

-   The CSAMA practicals
-   R package vignettes: [Biostrings](https://github.com/Bioconductor/Biostrings)
-   Bioconductor [workflows](http://bioconductor.org/packages/release/workflows/)
-   [F1000 Bioconductor channel](https://f1000research.com/gateways/bioconductor)
-   Paper written using Rmd (or Rmw) on github ([github-paper](https://github.com/lgatto/github-paper),
    [QSep-manuscript](https://github.com/lgatto/QSep-manuscript), [TAGMworkflow](https://github.com/lgatto/TAGMworkflow), ...)
-   Also mention: references with bibtex, show templates, bookdown,
    blogdown, ...