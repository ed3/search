Search Plugin
========================

[![Packagist](https://packagist.org/packages/ed3/search)](https://packagist.org/packages/ed3/search)

This **Search** plugin enables developers to quickly implement the [POST-Redirect-GET](docs/Documentation/Post-Redirect-Get.md) pattern.

The Search plugin is an easy way to implement PRG in your application, and provides you with a paginate-able search in any controller. It supports simple methods to search inside models using strict and non-strict comparing, but also allows you to implement any complex type of searching.

* **PRG Component:** The component will turn GET parameters into POST to populate a form and vice versa.
* **Search Behaviour:** The behavior will generate search conditions passed in the provided GET parameters.

This is *not* a Search Engine or Index
--------------------------------------

As mentioned before, this plugin helps you to implement searching for data using the [PRG](Docs/Documentation/Post-Redirect-Get.md) pattern. It is **not** in any way a search engine implementation or search index builder, although it can be used to search an index such as *Elastic Search* or *Sphinx*.

Requirements
------------

* Search 3.2 => minimum CakePHP 3.10 and PHP 5.6
* Search 4.x => minimum CakePHP 4.4 and PHP 7.4
* Search 5.x => minimum CakePHP 5.0 and PHP 8.1

Documentation
-------------

For documentation, see the [Docs](docs/Home.md) directory of this repository.
