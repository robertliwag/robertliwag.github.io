# Bookdown Notes {#bookdownnotes}
The **bookdown** package can be installed from CRAN or Github:

```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

## A typical bookdown book
- contains multiple chapters, and one chapter lives in one R Markdown file, with the filename extension ` .Rmd` . 
- Each R Markdown file must start immediately with the chapter title using the first-level heading, e.g., # Chapter Title. 
  - Always label chapter and section titles using {#label} after them or automatic labels will be done anyway. Manual labeling prevents complications.
- All R Markdown files must be encoded in UTF-8, especially when they contain multi-byte characters such as Chinese, Japanese, and Korean.  

## Compilation
- By default, bookdown merges all Rmd files by the order of filenames, e.g., `01-intro.Rmd` will appear before `02-literature.Rmd`. 
- Filenames that start with an underscore _ are skipped. If there exists an Rmd file named `index.Rmd`, it will always be treated as the first file when merging all Rmd files. The reason for this special treatment is that the HTML file index.html to be generated from index.Rmd is usually the default index file when you view a website.
- override the above behavior by including a configuration file named `_bookdown.yml` in the book directory.  You can use a field named rmd_files to define your own list and order of Rmd files for the book. For example: `rmd_files: ["index.Rmd", "abstract.Rmd", "intro.Rmd"]`
- set `new_session: yes` in the configuration file `_bookdown.yml` in order that other chapters will compile from clean slate when using `knitr` on `index.Rmd`.

## Formatting
### Inline
- *italic* formatting: use `*italic*` or `_italic_`
- **bold** formatting: use `**bold**` or `__bold__`
- for subscripts as in H~2~O: surround the subscript with `~` like `H~2~O`
- superscripts such as x^2^ + y^2^: surround by `^` symbol like `x^2^ + y^2^`
- for `inline code` like this: surround text by backticks `` `inline code` ``
- for <span style="font-variant:small-caps;">Small Caps</span>: use `<span style="font-variant:small-caps;">Small Caps</span>` 
- link such as [RStudio](https://www.rstudio.com): use `[text](link)`, e.g. `[RStudio](https://www.rstudio.com)`
- use similar syntax when inserting an image; just add  bang symbol `!`: `![alt text or image title](path/to/image)`
- For inline LaTex **math expressions** such as $x^2+y^2$: surround expression by `$` sign as in `$x^2 + y^2$`

### Block elements
- Section headers: use a number of `#` signs
  + `# Chapter`
  + `## Section`
  + `### Subsection`
  + `#### Subsubsection`
- To remove heading number, use `{-}`
  + example: `# Preface {-}`
- For unordered lists, start the item with `*`, `-`, or `+` 
  + nest using the same prefixed with two spaces for each inner list
- For ordered list, use numbers. the same principle follows for nested lists.
- For block or display style LaTex **math expressions**, enclose the expression with `$$`. This expression `$$f(k) = {n \choose k} p^{k} (1-p)^{n-k}$$` has this output:
$$f(k) = {n \choose k} p^{k} (1-p)^{n-k}$$

### Math equation environments (blocks), labels, and referencing
- To number equations and refer to them, place them in the equation environment and assign to them labels using the syntax `(\#eq:label)`. For instance, 

```
\begin{equation}
   f(k) = {n \choose k} p^{k} (1-p)^{n-k}
   (\#eq:binom)
\end{equation}
```

renders 
\begin{equation}
   f(k) = {n \choose k} p^{k} (1-p)^{n-k}
   (\#eq:binom)
\end{equation}
and refer using `\@ref(eq:binom)`, e.g., see \@ref(eq:binom)
