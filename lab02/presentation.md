---
## Front matter
lang: en-US
title: Laboratory Work Report No. 2
subtitle: Practical Scientific Writing
author:
  - Nadia Ezzakate
institute:
  - Peoples' Friendship University of Russia, Moscow, Russia
  - Joint Institute for Nuclear Research, Dubna, Russia
date: September 27, 2025

## i18n babel
babel-lang: english
babel-otherlangs: russian

## Formatting pdf
toc: false
toc-title: Table of Contents
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Information

## Presenter

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Nadia Ezzakate
  * Physics and Mathematics Student
  * Peoples' Friendship University of Russia
  * <https://github.com/nadiaelfe>



:::
::::::::::::::

## Work Objectives and Tasks

The objective of this laboratory work is to familiarize with the document structure in LaTeX.

**Tasks:** Review and work with the document structure in TexLive:

1. Try adding text to your first document, typesetting and seeing the changes in your PDF.
2. Make some different paragraphs and add variable spaces.
3. Explore how your editor works; click on your source and find how to go to the same line in your PDF.
4. Try adding some hard spaces and see how they influence line-breaking.

# Theoretical Introduction

## Basic LaTeX Document Structure

```latex
\documentclass{article}
\usepackage[T1]{fontenc}
\begin{document}
Hey world!
This is a first document.
\end{document}
```

(see Fig. [-@fig:001])
![](presentation/img2.png){ #fig:001 width=100% }
## Running LaTeX

### Compilation Process

(see Fig. [-@fig:002])

![](presentation/img3.png){ #fig:002 width=100% }

(see Fig. [-@fig:003])

![](presentation/img6.png){ #fig:003 width=100% }



# Laboratory Work Execution

## Task 1: Creating First Document

### Adding Text and Typesetting

(see Fig. [-@fig:004])

![](image/img8.jpg){ #fig:004 width=100% }

```latex
\documentclass[a4paper,12pt]{article}
\usepackage[T1]{fontenc}

\begin{document}

\title{My First LaTeX Assignment}
\author{Nadia Ezzakate}
\date{\today}

\maketitle

% --- Introduction ---
\section*{Introduction}
Hey world!  
This is my first document in \LaTeX.  
I want to learn how to structure text, use formatting, and create a clean PDF.

% --- Paragraphs with formatting ---
\section*{Main Content}
Here is a paragraph with some \textbf{bold text} and some \textit{italic text}.  
It helps emphasize important points.

Another paragraph shows how LaTeX treats       multiple spaces:  
extra spaces are automatically reduced to a single space in the output PDF.  

% --- Hard spaces ---
Sometimes we need words to stay together:  
Dr.~Brown lives in New~York~City.  
The tilde (~) keeps these words on the same line.

% --- Lists ---
Here is a small list of things I want to remember about LaTeX:
\begin{itemize}
    \item Paragraphs are separated by blank lines.
    \item Special characters like \%, \$, \#, \_ must be escaped.
    \item Footnotes add extra information without breaking the text\footnote{This is an example footnote.}.
    \item Hard spaces (~) prevent unwanted line breaks.
\end{itemize}

% --- Conclusion ---
\section*{Conclusion}
Overall, creating this document helped me understand the basics of LaTeX: paragraphs, formatting, lists, footnotes, and spacing.  
I am ready to explore more advanced features in the next assignments.

\end{document}

```
(see Fig. [-@fig:005])

![](presentation/pic1.png){ #fig:005 width=100% }

## Task 2: Paragraphs and Variable Spaces

### Creating Different Paragraph Structures

(see Fig. [-@fig:006])

![](presentation/pic1.1.png){ #fig:006 width=100% }

## Task 3 & 4: Editor Exploration and Hard Spaces

### Editor Features and Line-breaking Control

![](presentation/img4.png){ #fig:007  width=100% }

(see Fig. [-@fig:008])

![](presentation/img4.1.png){ #fig:008 width=100% }

# Conclusion

Thus, the objective of installing TeXlive was achieved, and I became familiar with working with its structure as well as with the LaTeX system. The laboratory work allowed me to practice creating LaTeX documents, understanding paragraph formatting, and using non-breaking spaces to control line-breaking behavior.

## {.standout}

Thank you for your attention
