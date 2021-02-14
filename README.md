![GitHub language count](https://img.shields.io/github/languages/count/aaqibb13/Resume?color=brightgreen) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/aaqibb13/LaTeX-Template-for-Resume) ![GitHub repo size](https://img.shields.io/github/repo-size/aaqibb13/LaTeX-Template-for-Resume)

This was adapted from the template [here](https://github.com/sb2nov/resume), with some modifications to design, the code, and ability to get up and running.

# Usage:

There are 5 distinct components: header, sections, entry type 1 (title, subheading, date(s), location), entry type 2 (title, date(s)), and entry type 3 (single list no bullet, with a bold prefix). 
You can also modify the colour scheme (primary, secondary, accent, and link colours).

# Header:

Change the variables at the top of the document, and then modify the order you want to present your info in the `\headertype{}{}{}{}{}{}` argument at the beginning of the document. You can choose `\doublecol` or `\singlecol`.

# Section:

`\section{<icon>}{Text}`

<icon> can be anything; fontawesome icons are great.


# Entry:

Preceed it by `\resumeEntryStart` and end it with `\resumeEntryEnd`.

## Entry type 1:

`\resumeEntryTSDL{Title}{Date(s)}{Subheading}{Location}`

## Entry type 2:

`\resumeEntryTD{Title}{Date(s)}`

## Entry type 3:

`\resumeEntryS{Bold}{RegularText}`

# Entry Details:

Preceed it by `\resumeItemListStart` and end it with `\resumeItemListEnd`. Each item is a `\resumeItem`.

# Preview:

## Resume Header:

![](/Resumeheader.png)

## Resume Preview:

![](Resume.png)

# Acknowledgements:

Modified template from [here](https://github.com/sb2nov/resume)
