# Quarto extension for ON-LiMiT website theming

This repository contains a Quarto extension with style files used across
ON-LiMiT websites.

## Installing

To use this format, you need to install the extension in your
repository. You can do this by running the following command in the
terminal from your project directory:

``` bash
quarto add onlimit-study/onlimit-theme
```

This will install the extension by adding a `_extensions/` folder to the repository.

## Using

To use the ON-LiMiT theme, add following lines to your `_quarto.yml`
file:

``` yaml
project:
  type: onlimit-theme

format:
  onlimit-theme-html:
    theme:
      - brand
```

## Example

Here is the source code for a minimal sample document:
[index.qmd](index.qmd).

## Features

This is a simple theme that provides a colour scheme for the ON-LiMiT
websites. It includes:

-   A consistent navbar
-   ON-LiMiT logo and favicon
-   Fonts
-   Emojis
