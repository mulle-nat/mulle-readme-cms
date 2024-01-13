# mulle-readme-cms

#### 🦋 Compose README.md or other markdown files from various reusable parts

You could call it a [Content Management System](https://de.wikipedia.org/wiki/Content-Management-System)
for README.md files. Not useful if you have only one project to maintain.
Indispensable when you have dozens of projects.



## Executables

| Executable                   | Description
|------------------------------|--------------------------------------------
| **mulle-readme-cms**         | Run the mulle-template-composer, if files changed
| **mulle-markdown-decompose** | Create distinct pieces from a markdown file
| **mulle-jekyll-decompose**   | Extract yaml or text from jekyll post
| **mulle-template-compose**   | Create a file from template pieces


## Example

Look at the [cola](cola) folder, then run

``` sh
mulle-readme-cms --protect --mulle --preview
```







## Install

Install the requirements:

| Requirements                                 | Description
|----------------------------------------------|-----------------------
| [mulle-bashfunctions](https://github.com/mulle-nat/mulle-bashfunctions)             | 🥊 A collection of shell functions
| [mulle-scion](https://github.com/MulleWeb/mulle-scion)             | 🌱 A modern template engine for Objective C (tool & documentation) 
| [mulle-markdown](https://github.com/MulleWeb/mulle-markdown)             | 👯 mulle-markdown turns markdown into HTML


The command to install the latest mulle-readme-cms into
`/usr/local` (with **sudo**) is:

``` bash
curl -L 'https://github.com/mulle-nat/mulle-readme-cms/archive/latest.tar.gz' \
 | tar xfz - && cd 'mulle-readme-cms-latest' && sudo ./bin/installer /usr/local
```



## Author

[Nat!](https://mulle-kybernetik.com/weblog) for Mulle kybernetiK  


