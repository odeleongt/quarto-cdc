# `quarto-cdc` format for slides following the CDC template

## Installing

Set the working directory in your RStudio session to the folder where you want
your slides code, and run the following command in the RStudio `Terminal` pane.

``` bash
quarto use template CDCgov/quarto-cdc
```

This will install the extension and create an example `qmd` file that you can
use as a starting place for your `revealjs` slides.




## Using

Make sure you keep the `# Disclaimer` slide.
It doesn't need to be the last slide, but needs to be there.

You can remove the author `affiliation` fields if you don't want them.
For more author information options, check the
[official Quarto documentation](https://quarto.org/docs/journals/authors.html).

This format is based on the `revealjs` format.
The [official documentation](https://quarto.org/docs/presentations/revealjs/)
shows several additional features not included in the template.




## Format Options

If you want the name of your CIO on the banner in the title slide,
set it on the `title-cio` option in the YAML header.
Otherwise, set that option to blank quotes (`""`).

If you want to remove or modify the footer that appears on all slides,
change the `footer` option in the
`_extensions/odeleongt/quarto-cdc/_extension.yml` file.




## Example

Here is the source code for a minimal sample document:
[template.qmd](template.qmd).
