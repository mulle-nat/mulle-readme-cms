## Reuse an existing README.md

### Decompose

The decomposition step is useful, to separate those parts from a README.md
file that can be shared with other (sibling) projects.

Decompose the existing file into parts with:

``` sh
mulle-readme-decompose README.md
```

This will cut the file into parts, which were formerly separated by `##`
headers. Some manual labor may be required.


### Create or reuse an existing README.md.scion template

A very simple template could look like this:

``` markdown
# ${{ project.name }}

{% includes optionally "description.md" %}

{% includes optionally "howto-install.md" %}

{% includes optionally "standard-footer.md" %}
```


