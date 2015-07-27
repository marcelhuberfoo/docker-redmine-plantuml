# Redmine 2.6-latest image with [graphviz][graphviz] and [plantuml][plantuml] installed [![](https://badge.imagelayers.io/marcelhuberfoo/redmine-plantuml.svg)](https://imagelayers.io/?images=marcelhuberfoo/redmine-plantuml 'Get your own badge on imagelayers.io')

Docker build for an extended [redmine 2.6-latest docker image][redmineimage].

## Purpose

This docker image is based on the latest redmine 2.6 image provided by sameersbn.
It provides these features:

* graphviz installed, provides `dot`, `neato`, etc.
* plantuml, java library to render UML and sequence charts based on textual input.

## Usage

This image is best used with the [wiki external filter plugin][wikiexternalplugin] by Alexander Tsvyashchenko.

[redmineimage]: https://registry.hub.docker.com/u/sameersbn/redmine/
[wikiexternalplugin]: http://www.ndl.kiev.ua/content/redmine-wiki-external-filter-plugin
[graphviz]: http://www.graphviz.org/
[plantuml]: http://plantuml.sourceforge.net/
