# math-problems
Hello! This repository contains all the math problems[^1] and solutions I have been solving as a student. I have been trying to import the solutions into **LaTeX** file format. Every week, there will be a math problem I will be solving! 

So here's the code for the preamble:

```
\documentclass[12pt]{article}
\usepackage[framemethod=TikZ]{mdframed}
\usepackage{amsthm}
\usepackage{tcolorbox}
\usepackage[paperheight=13in, paperwidth=8.5in, margin=0.75in]{geometry}
\usepackage{setspace}
\usepackage{amsmath}
\usepackage{cancel}
\usepackage{multicol}
\usepackage{multirow}
\usepackage{fancyhdr}
\pagestyle{fancy}
\usepackage{lastpage} 
\usepackage{array, caption, tabularx,  ragged2e}
\usepackage{colortbl}
\usepackage{amssymb}
\usepackage{graphicx}
\usepackage[parfill]{parskip}
\setlength{\parskip}{0pt}
\lhead{Jhon Christian N. Rozano}
\chead{}
\rhead{July 21, 2021}

\lfoot{Source: Brilliant}
\cfoot{}
\rfoot{Page \thepage\ of \pageref{LastPage}}

\renewcommand{\headrulewidth}{1pt}

\renewcommand{\footrulewidth}{1pt}

\renewcommand{\familydefault}{\sfdefault}
\def\mathLarge#1{\mbox{\LARGE $#1$}}
```

[^1]: MPOTD: Math Problem of the Day

