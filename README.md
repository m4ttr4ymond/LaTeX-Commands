# LaTeX-Commands
## About
This repo is ust a place for me to keep LaTeX commands that I've written. I think they're really helpful, and I'm more than happy to share with whoever wants to use them. No attribution required, but feel free to submit your own.  

___

## Commands
### Note
Bold notes with the text underneath.  
Usage: `\deff{<title_phrase>}{definition}`  
```
\newcommand{\deff}[2]{\textbf{#1}\\
\begin{tabular}{|p{10cm}}
    #2\\
\end{tabular}}
```

### Math
Shortcut so I don't have to keep typing `$$`.  
Usage: `\mt{<equation>}`  
```
\newcommand{\mt}[1]{$ #1 $}
```

### Compact Notation
A simplified way to write notations such as product and summation notation.  
Usage: `\snote{<big_symbol>}{<overset_text>}{<underset_text>}`  
```
\newcommand{\snote}[3]{\overset{#2}{\underset{#3}{#1}}}
```
