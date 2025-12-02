---
title: "Code and Technical Writing"
---

# 8. Code and Technical Writing

## Code block formatting

In R Markdown or Quarto, specify language using braces:

```markdown
```{r}
# R code
```

```{python}
# Python code
```

```{html}
<!-- HTML code -->
```
```

In plain Markdown, specify language without braces:

```markdown
```r
# R code
```

```python
# Python code
```

```html
<!-- HTML code -->
```
```

`Inline code` should be marked consistently.

## Variable naming

Prefer camelCase for variables.  
Use underscores mainly for filenames.

## Mathematical expressions

Render using MathJax or LaTeX when supported.  
Otherwise use clear text with proper spacing and typographic symbols.

## Acronym expansion

Expand acronyms on first use (e.g., Attention Deficit/Hyperactivity Disorder (ADHD)).  
Use `<abbr>` in HTML when supported.

Return to the [manual index](../).
