---
title: Presentation Title
subtitle: Subtitle
author: Author
institute: UIUC
date: 12/34/5678

theme: metropolis
classoption: aspectratio=169
slide_level: 2
toc: false

header-includes: 
	- \metroset{progressbar=frametitle,sectionpage=progressbar}
	- \setbeamerfont{footnote}{size=\tiny}
	- \hypersetup{colorlinks,linkcolor=,urlcolor=blue}
	- \setbeamerfont{caption}{size=\scriptsize}
	- \usefonttheme[onlymath]{serif}
---

# Section 1

## Slide 1
Command to build the output:

```bash
pandoc [markdown_file.md] -t beamer -o [output_file.pdf]
```

## Slide 2
- item 1
- item 2
	- item 3

# Section 2
## Slide 3
### Slide 3.1
$$E=mC^2$$

## Slide 4
| a | b | c |
|---|---|---|
| 0 | 1 | 2 |
| 0 | 1 | 2 |
| 0 | 1 | 2 |
