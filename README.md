Search Plugin
========================

[![Downloads](https://poser.pugx.org/ed3/search/d/total.png)](https://packagist.org/packages/ed3/search)
[![Latest Version](https://poser.pugx.org/ed3/search/v/stable.png)](https://packagist.org/packages/ed3/search)

This **Search** plugin enables developers to quickly implement the [POST-Redirect-GET](Docs/Documentation/Post-Redirect-Get.md) pattern.

The Search plugin is an easy way to implement PRG in your application, and provides you with a paginate-able search in any controller. It supports simple methods to search inside models using strict and non-strict comparing, but also allows you to implement any complex type of searching.

* **PRG Component:** The component will turn GET parameters into POST to populate a form and vice versa.
* **Search Behaviour:** The behavior will generate search conditions passed in the provided GET parameters.

This is *not* a Search Engine or Index
--------------------------------------

As mentioned before, this plugin helps you to implement searching for data using the [PRG](Docs/Documentation/Post-Redirect-Get.md) pattern. It is **not** in any way a search engine implementation or search index builder, although it can be used to search an index such as *Elastic Search* or *Sphinx*.

Requirements
------------

* CakePHP 3.5+
* PHP 5.6+

Documentation
-------------

For documentation, see the [Docs](../tree/master/Docs/Home.md) directory of this repository.
