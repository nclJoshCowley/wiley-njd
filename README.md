
# <%= title %>

## Purpose

Allow for the use of the [Wiley NJD][wiley-njd] template within Quarto.

## Creating a New Article

To create a new article using this format:

```sh
quarto use template nclJoshCowley/wiley-njd
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```sh
quarto add nclJoshCowley/wiley-njd
```

Then, add the format to your document options:

```yaml
format:
  wiley-njd-pdf: default
```

## Template Options

TODO: Document which options are provided by the LaTeX template.

## Example

To see the template in action, see [template.qmd](template.qmd).

<!-- External Links -->

[wiley-njd]:
  https://authorservices.wiley.com/author-resources/Journal-Authors/Prepare/new-journal-design.html