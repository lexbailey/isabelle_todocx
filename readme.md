# Isabelle theory to docx converter

## Why?

Isabelle can generate LaTeX and HTML for theory files, for presenting theory files in technical papers or on the internet.

I much prefer using Word instead of LaTeX, so I want to be able to write technical papers with properly formatted Isabelle theory code in Word.

Word can read .docx files, so can LibreOffice writer

## How?

This program takes the .html output from isabelle and produces a .docx

## Usage

1. Ask isabelle for some html

`isabelle build -P <html_out_dir> -d <your_session_dir> -b <session_name>`

2. Generate a .docx

`./makedoc <input.html> <output.docx>`
