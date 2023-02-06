## Install

### mulle-sde

Use [mulle-sde](//github.com/mulle-sde) to build and install {{ project.name }}{{ dependencies.count ? " and all dependencies" : "" }}:

``` sh
mulle-sde install --prefix /usr/local \
   https://{{ project.host ? project.host : "github.com"}}/{{ project.username }}/{{ project.reponame }}/archive/latest.tar.gz
```

### Manual Installation

{% if dependencies.count %}
Install the requirements:

| Requirements                                 | Description
|----------------------------------------------|-----------------------
{% for item in dependencies %}
| [{{ item.name}}]({{ item.url }})             | {{ item.description }}
{% endfor %}
{% endif %}

Install into `/usr/local` with [cmake](https://cmake.org):

``` sh
cmake -B build \
      -DCMAKE_INSTALL_PREFIX=/usr/local \
      -DCMAKE_PREFIX_PATH=/usr/local \
      -DCMAKE_BUILD_TYPE=Release &&
cmake --build build --config Release &&
cmake --install build --config Release
```
