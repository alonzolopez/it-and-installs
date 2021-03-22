# Latex in VS Code
In order to draft and build Latex files in VS Code, first install TexLive with
```
sudo apt install texlive-full
```
Then, install the LaTex Workshop plugin for VS Code.

# Template
```LaTex
\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{amsmath}
\usepackage{hyperref}
\def\code#1{\texttt{#1}}
\usepackage{xcolor}

\pagecolor[rgb]{0,0,0} %black

\color[rgb]{0.8,0.8,0.8} %grey


\title{Title Here}
\author{Alonzo Lopez}
\date{Date Here}

\begin{document}

\maketitle

\section{Intro}
\subsection{subseciton}


\end{document}
```