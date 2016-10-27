# Protocol Buffers for LaTeX listings

Language definitions and styles for adding 'protobuf' highlighting to the
'listings' package in LaTeX.

## Usage

```latex
\documentclass{article}
\usepackage{listings}
\usepackage{protobuf/lang}  % include language definition for protobuf
\usepackage{protobuf/style} % include custom style for proto declarations.
\begin{document}
% Use custom language and style for Protocol Buffers.
\lstinputlisting[language=protobuf2,style=protobuf]{search.proto}
\end{document}
```

Information about
[Protocol Buffers](https://developers.google.com/protocol-buffers/docs/proto)

## Example

An example of this package's usage can be found in the 'example' directory.
There you'll also find the following screenshots of the three different
contained styles.

Currently you can change the used style only by editing
```protobuf/style.sty (but this shouldn't be too muich hassle).

![](https://raw.githubusercontent.com/aytchell/latex-listings-protobuf/master/example/solarized.png)
*Solarized style*

![](https://raw.githubusercontent.com/aytchell/latex-listings-protobuf/master/example/blueish.png)
*Blue-ish style*

![](https://raw.githubusercontent.com/aytchell/latex-listings-protobuf/master/example/tomorrow.png)
*'Tomorrow' style*

## Public domain

The source code and any original content of this repository is hereby released into the [public domain].

[public domain]: https://creativecommons.org/publicdomain/zero/1.0/

## Acknowledgments

The structure of the package, this README file and the blue-ish theme are
inspired by Robin Eklind's
[definitions and styles for listings](https://github.com/mewspring/latex)
