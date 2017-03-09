# StudentTemplate
Pandoc LaTeX Student Template

## Information

This template works on linux machines and it provides a very efficient PDF template for
pandoc. The template will replace the original one, so all your PDF conversions will
use the template.

## Installation

```
cd ~
mkdir .pandoc
cd .pandoc
git clone https://github.com/ConsoleTVs/StudentTemplate.git
```

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

```
