# README

## Installation

1. Install nodejs
2. Install reveal-md: `npm install -g reveal-md`

## Usage

To develop with live reloading: `reveal-md <slides.md> --theme hogent.css --watch`

To generate a static site to `./build`: `reveal-md --static build --static-dirs img --theme hogent.css --listing-template index-template.html`

You can change the template `index-template.html` to create a nice landing page for your course.

To generate a PDF: `reveal-md <slides.md> --theme hogent.css --print slides.pdf --print-size A4`

The resulting PDF isn't very nice though ... .

## Bugs

* https://github.com/webpro/reveal-md/issues/439
* 