# onlimit-theme format

This repository contains a Quarto extension with style files used across
ON-LiMiT websites.

## Installing

To use this format, you need to install the extension in your repository. You can do this
by running the following command in the terminal from your project
directory:

``` bash
quarto use template on-limit/onlimit-theme
```


This will install the extension and create an example index file, `index.qmd` that you
can use as a starting place for your repository.

## Using

To use the ON-LiMiT theme, add following lines to your `_quarto.yml` file:

```yaml
format:
  onlimit-theme-html:
    theme:
      - brand
```

## Example

Here is the source code for a minimal sample document:
[index.qmd](index.qmd).

## Features

This is a simple theme that provides a colour scheme for the ON-LiMiT websites. It includes:

- A consistent navbar
- ON-LiMiT logo and favicon
- Fonts
- Emojis