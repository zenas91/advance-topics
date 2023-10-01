# Minimalist LaTeX Template for Academic Presentations

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic presentation. The template uses the [Beamer class](https://github.com/josephwright/beamer). The template carefully follows typographical best practices and has a minimalist design.

## Documentation

The template is documented at https://pascalmichaillat.org/d1/.

## Features

+ The font for text, roman math, and numbers is [Source Sans Pro](https://github.com/adobe-fonts/source-sans).
+ The font for Greek and calligraphic math is [Euler](http://luc.devroye.org/fonts-26139.html).
+ No colors are used in the text (only grayscale) to reduce distraction; colors are reserved for graphs and alerts.
+ Margins, spacing, and font size are set for comfortable reading.
+ There are no frills at the periphery of the slides.
+ Slides with figures, tables, and section headings can easily be inserted into the presentation.
+ The aspect ratio is set to 4:3.
+ The file `presentation.pdf` illustrates the output of the template.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `presentation.tex` to replace the boilerplate content with the content of your presentation. 
+ Replace the figures in the PDF file `figures.pdf` with the figures that will be included in the presentation. There should be one figure per page.
+ Compile `presentation.tex` with pdfTeX. This will generate a new PDF file named `presentation.pdf`.
+ The LaTeX style file `presentation.sty` collects all the commands to format the presentation. The file must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
+ The file `presentation.pdf` is not required to use the template. It only illustrate the output of the template, and will be overridden once `presentation.tex` is compiled.

## Software

The template was developed on a Mac with the MacTeX-2021 distribution, and it continues to work with the MacTeX-2023 distribution. Hopefully, it should also work on other machines and with other distributions.

## License

The content of this repository is licensed under the terms of the MIT License.

## Related resources

+ [LaTeX template for academic papers](https://github.com/pmichaillat/latex-paper) – This template produces academic papers following the same principles, and with a similar appearance, as this presentation template. 
+ [LaTeX commands to write math](https://github.com/pmichaillat/latex-math) – These commands make it easy to write mathematical expressions. They can be used in combination with this paper template.
