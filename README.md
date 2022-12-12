# Math In One TeX

![CoverImage](https://raw.githubusercontent.com/makabaka1880/MathInOneTeX/main/CoverArt.png)

Math In One TeX aims to document as much mathematic knowledge in one TeX file (.tex) as possible. It is completely open-sourced, and all are welcome to modify and improve.

## Navigation

### Source
 Search for
 ```
 % Sec. <Section Number> Subsec. <Subsection Number> Subsubsec. <Sub-subsection Number> ...
 ```

For example, if you are to search for Basic Arithmatic / Subtraction, you search for `% Sec. 2 Subsec. 2`

![Example of searching in source](https://raw.githubusercontent.com/makabaka1880/MathInOneTeX/main/READMEArt/1-1-1.png)

### PDF

If your PDF viewer supports viewing the Table of Contents, just look for the section: 

![Example of searching in side bars](https://raw.githubusercontent.com/makabaka1880/MathInOneTeX/main/READMEArt/1-2-1.png)
![Example of searching in side bars and displaying the section](https://raw.githubusercontent.com/makabaka1880/MathInOneTeX/main/READMEArt/1-2-2.png)

## Template

``` latex
% Sec. <Section Number>
\clearpage
\section{Section Name}
Description of this section...

% Sec. <Section Number> Subsec. <Subsection Number>
\subsection{<Subsection Name>}
\label{section:<Lowercased Section Name>}

% Sec. <Section Number> Subsec. <Subsection Number> Subsubsec. 1
\subsection{Definition}
Content here...

% Sec. <Section Number> Subsec. <Subsection Number> Subsubsec. 2
\subsection{Pronunciation \& Notation}
Content here...

% Sec. <Section Number> Subsec. <Subsection Number> Subsubsec. 3
\subsection{Laws \& Principles}
Content here...
```

## Current Table of Contents

```
1. Introduction
2. Basic Constant Arithmatic
    |
    - Addition
    - Subtraction
    - Multiplication
    - Division
```
