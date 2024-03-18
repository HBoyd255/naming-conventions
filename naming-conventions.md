# Naming Conventions

Harry Boyd - hboyd255@gmail.com - 18/03/2024

This document stands to outline the naming conventions that I use. It also holds
the reasoning behind each convention, and any references that may be relevant.
For any context in which official naming conventions exist, those conventions
should be used, and this document will link to their documentation.

This document only covers the conventions that I use in my work, and is not
intended to be a comprehensive guide to naming conventions. This is a living
document, so will be updated as I standardize more of my work.

The official and up to date home of this document is in a public GitHub
repository titled
[naming-conventions](https://github.com/HBoyd255/naming-conventions/blob/main/naming-conventions.md).

If you notice and factual errors, or have any suggestions for improvement, feel
free to open an issue or email me directly at the address at the top of this
document.

## Table of Contents

- [Github Repositories](#github-repositories)
- [Markdown Files](#markdown-files)
- [Directories and File Paths](#directories-and-file-paths)

## Github Repositories

Names of GitHub repositories should be in `kebab-case`, all lowercase, with
words separated by hyphens. This makes the repository name easy to read and
url-friendly. It also makes it easy to read at a glance, and easy to type.

Additionally, although not formally standardized, it is the convention seen in
many github guides and tutorials.

- [GitHub Docs: Creating a repository](https://docs.github.com/en/get-started/quickstart/create-a-repo)

## Markdown Files

Markdown files should be named in `kebab-case`, all lowercase, with words
separated by hyphens. This does however have a few exceptions.

README files along with other files that server similar purposes, TODO.md,
MOTIVATION.md, etc. should be named in `UPPERCASE`. This is to make them stand
out in the file tree, and to make them easy to find. The decision of what
content should be in the README.md vs TODO.md is not the focus of this document,
but is something that I have addressed in my [Project Project]().

- [GitHub Docs: Creating new files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

For repositories in which a single markdown file is the main focus, such as this
one, the file should not be named README.md, but rather named after the
repository itself. Although naming the file README.md would make more visible in
GitHub, the file should be able to stand alone, and thus should be named
accordingly.

## Directories and File Paths

This is a difficult one to standardize, as it is often dependent on the
environment in which the file is being used. I will come back to this one.

One point I will outline is that if a directory, is the local counterpart to a
GitHub repository, it should be named the same as the repository, and thus use
`kebab-case`.

In every instance, the file extension should be `lowercase`.
