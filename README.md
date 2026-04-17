# ajl-poster 

This is a modified version of the [Quarto poster](https://github.com/quarto-ext/typst-templates/tree/main/poster) format. The current version results in an error regarding the headings when the user attempts to render the poster. As a result, this template is virtually the same as the Quarto version but with heading numbers removed. 

To reflect my current (as of 4/16/2026) status as a student at the University of California, San Diego, I replaced the NCSU logo with one from UCSD. The default font has also been changed to Carlito, which can be obtained [here](https://fonts.google.com/specimen/Carlito).

## Installing

To install, run the following command in a terminal:

```bash
quarto use template andrewjliang/ajl-poster
```

This will install the format extension and create an example qmd file
that you can use as a starting place for your document.


## Changing Fonts

The default font is Fira Sans, but you can use any font that is installed locally on your computer. Simply include the following in the YAML:

```yaml
font: default
```   


## License

This template modifies the [Quarto Typst poster template](https://github.com/quarto-ext/typst-templates?tab=readme-ov-file), published under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) public domain license. This poster template is distributed under the [MIT license](/LICENSE.md). 