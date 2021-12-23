# README

This repository contains common macros, commands, and utilities commonly shared by
my other course package repositories.

Packages are labelled with the given suffixes

- **[l]** - Lab: Contains lab only commands
- **[m]** - Macros: Contains general macros, commands shared by the course
- **[w]** - Workspace: Contains homework/assignment specific macros and commands.

## Features

### Shorthands

dy\dx:
``` latex
- \dyx
```

Number Sets Symbols:
``` latex
- \N, \R, \Z, \O, \Q, \C
```

## Commands

New Section
``` latex
- \sect{Section Heading}
```

New Sub Section
``` latex
- \subsect{Sub Section Heading}
```

Question: Shorthand for Q#n
``` latex
- \q{1}
```

Centered Title
``` latex
\ctitle{Title}
```

Alphanumeric enums
``` latex
(a), (b), (c)
\begin{litem}
\item
\item
\item
\end{litem}
```

Arbitrary alphanumeric character lists
``` latex
d), e), f)
\alist{d}
\alist{e}
\alist{f}
```

Circled Numbers
``` latex
\circled{1}
```

Inline Markdown code blocks
``` latex
\code{add\_two\_lists} % Note that underscores have to be escaped
```
