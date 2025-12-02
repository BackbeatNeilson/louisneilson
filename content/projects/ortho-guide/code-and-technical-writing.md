---
title: "Code and Technical Writing"
weight: 9
hero: images/guide/rob-wingate-LnzSzH24XS8-unsplash.jpg
---

# 9. Code and Technical Writing

## Code block formatting

In R Markdown or Quarto, specify language using braces:

\`\`\`{r}  
\# R code  
\`\`\`

\`\`\`{python}  
\# Python code  
\`\`\`

\`\`\`{html}  
\<!-- HTML code -->  
\`\`\`

In plain Markdown, specify language without braces:

\`\`\`r  
\# R code  
\`\`\`

\`\`\`python  
\# Python code  
\`\`\`

\`\`\`html  
\<!-- HTML code -->  
\`\`\`

`Inline code` should be \`marked\` consistently.

## Variable naming

Prefer camelCase for variables.  
Use underscores mainly for spaces in filenames.

## Mathematical expressions

Render using [MathJax](https://www.mathjax.org/) where possible, else LaTeX when supported.  
Otherwise use clear text with proper spacing and typographic symbols. See also: [Punctuation → Mathematical Operators](../punctuation/#mathematical-operators).


## Acronym expansion

Expand acronyms on first use (e.g., Attention Deficit/Hyperactivity Disorder (ADHD)).  
Use `<abbr>` in HTML, or similar tools where supported.

Return to the [manual index](../).
