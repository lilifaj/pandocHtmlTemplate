# Pandoc HTML5 template

A GitHub flavored markdown which render `.md` to `.html`.

# Installation

On linux, the file can be downloaded running:

```
wget https://raw.githubusercontent.com/lilifaj/pandocHtmlTemplate/master/pandocHtmlTemplate.html5
```

It should be copied in the subfolder `~/.pandoc/templates/`. If it appears you don't have the folder, you can create it by using:

```
mkdir -p ~/.pandoc/templates
```

# Use the template

You can download pandoc on the official [website](https://pandoc.org/).

To run it, use the `--template=pandocHtmlTemplate.html5` option:

```
pandoc --template=pandocHtmlTemplate.html5 README.md -o README.html
```