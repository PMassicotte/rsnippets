# rsnippets
Snippets for RStudio

```r
snippets_dir <- fs::path_home_r(".R", "snippets")
fs::dir_create(snippets_dir) # make sure ~/.R/snippets exists
```

```r
snippr::snippets_install_github("pmassicotte/rsnippets", language = "r")
```
