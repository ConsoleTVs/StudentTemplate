# StudentTemplate
Pandoc LaTeX Student Template

## Information

This template works on linux machines and it provides a very efficient PDF template for
pandoc. The template will replace the original one, so all your PDF conversions will
use the template.

## Installation

```
cd ~
git clone https://github.com/ConsoleTVs/StudentTemplate.git .pandoc
```

*Note:* You will need Pandoc (http://pandoc.org/installing.html) installed and ```texlive``` to generate PDFs using LaTeX

## Usage

After you followed the installation proccess you'll be able to use the template.

```
pandoc test.md -o test.pdf
```

## Common settings

A part from the default settings, you  can use the following ones:

```
---
title: The main title
subtitle: A very cool subtitle
author: Èrik Campobadal
autodate: true
logo: true
numbersections: true
toc: true
lof: true
listings: true
lol: true
---
## Hello World

This is a simple Document

\lstinputlisting[language=Vhdl, caption=Codi de la ALU]{ALU32.vhdl}

```

More Info: http://wiki.itic.cat/LaTexTemplateUpc
