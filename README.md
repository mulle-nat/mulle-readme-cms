# 🦋 Compose README.md or other markdown files from various reusable parts

... for Android, BSDs, Linux, macOS, SunOS, Windows (MinGW, WSL)

You could call it a [Content Management System](ttps://de.wikipedia.org/wiki/Content-Management-System)
for README.md files. Not useful if you have only one project to maintain.
Indispensable when you have dozens of projects.


| Release Version                                       | Release Notes
|-------------------------------------------------------|--------------
| ![Mulle kybernetiK tag](https://img.shields.io/github/tag/mulle-nat/mulle-readme-cms.svg?branch=release) [![Build Status](https://github.com/mulle-nat/mulle-readme-cms/workflows/CI/badge.svg?branch=release)](//github.com/mulle-nat/mulle-readme-cms/actions)| [RELEASENOTES](RELEASENOTES.md) |

## Executables

| Executable                    | Description
|-------------------------------|--------------------------------------------
| **mulle-template-composer**   | Create a file from template pieces
| **mulle-markdown-decomposer** | Create distinct pieces from a markdown file
| **mulle-jekyll-decomposer**   | Extract yaml or text from jekyll post
| **mulle-readme-make**         | Run the composer on demand, if files changed


## Example

Look at the [cola](cola) folder, then run

``` sh
mulle-readme-make --protect --mulle --preview
```







## Install

The command to install the latest mulle-readme-cms into
`/usr/local` (with **sudo**) is:

``` bash
curl -L 'https://github.com/mulle-nat/mulle-readme-cms/archive/latest.tar.gz' \
 | tar xfz - && cd 'mulle-readme-cms-latest' && sudo ./bin/installer /usr/local
```



## Author

[Nat!](https://mulle-kybernetik.com/weblog) for Mulle kybernetiK


