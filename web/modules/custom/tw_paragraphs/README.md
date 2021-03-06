# Tailwind CSS Paragraphs

[![drupal](https://img.shields.io/badge/drupal-^8.9%20||%20^9-blue.svg?style=flat-square&logo=drupal)](https://drupal.org/)
[![tailwindcss](https://img.shields.io/badge/tailwindcss-%3E%3D%202.2.7-blue.svg?style=flat-square&logo=tailwindcss)](https://tailwindcss.com)
[![LICENSE](https://img.shields.io/github/license/drupix/tw_paragraphs?style=flat-square)](https://raw.githubusercontent.com/drupix/tw_paragraphs/master/LICENSE.txt)

**:warning: WARNING: Tailwind CSS Paragraphs is under development and not yet ready for production 🐞**

## CONTENTS OF THIS FILE

* Introduction
* Requirements
* Installation
* Configuration
* Maintainers

## INTRODUCTION

A suite of **Drupal** Paragraph bundles made for **Tailwind CSS** framework.

For content creators, attempts to use WYSIWYG editors to create structured
layouts typically lead to frustration and compromise. With this module, you can
easily position chunks of content (Paragraph bundles) within a structured
layout of your own design.

This suite of [Paragraphs](https://www.drupal.org/project/paragraphs) bundles
works within the [Tailwind CSS](https://tailwindcss.com/) framework.

* For a full description of the module, visit the project page:
  <https://github.com/drupix/tw_paragraphs>

* To submit bug reports and feature suggestions, or to track changes:
  <https://drupal.org/project/issues/tw_paragraphs>

This module is built on the premise that all good things in Drupal 8 are
entities and we can use Paragraphs and Reference fields to allow our content
creators to harness the power of the Tailwind CSS framework for functionality
and layout.

This module is ready for Drupal 9.

## Bundle Types

* Simple HTML

### Other Bundle Types to come as soon as possible

* Image
* Blank
* Accordion
* Carousel
* Columns (Equal, up to 6)
* Columns (Three Uneven)
* Columns (Two Uneven)
* Contact Form
* Drupal Block
* Modal
* Tabs
* View

<!--
**Backgrounds:**

Each Paragraph has width and background color options. Included are over 50
background colors and five empty background classes for you to customize in
your own theme.

**Widths:**

* Tiny - col-4, offset-4
* Narrow - col-6, offset-3
* Medium - col-8, offset-2
* Wide - col-10, offset-1
* Full - col-12
-->

## REQUIREMENTS

This module requires the following modules outside of Drupal core:

* [Entity Reference Revisions](https://www.drupal.org/project/entity_reference_revisions)
* [Paragraphs](https://www.drupal.org/project/paragraphs)
* [Views Reference Field](https://www.drupal.org/project/viewsreference)
* Tailwind CSS framework and JS included in your theme
  * Check the [TWEco](https://github.com/drupix/tweco) Theme that was built
    on top of Tailwind CSS

## INSTALLATION

* Install as you would normally install a contributed Drupal module. Visit:
  <https://www.drupal.org/node/1897420> for further information.
* Verify installation by visiting /admin/structure/paragraphs_type and seeing
  your new Paragraph bundles.
* On the Simple and ~~Blank~~ bundles, select Manage fields and choose which Text
  formats to use.
  We recommend a *Full HTML* for the Simple ~~~and a *Full HTML - No Editor* for
  the Blank~~~.

## CONFIGURATION

* Go to your content type and add a new field of type Entity revisions,
   Paragraphs.
* Allow unlimited so creators can add more than one Paragraph to each node.
* On the field edit screen, you can add instructions, and choose which
   bundles you want to allow for this field. Check all but Accordion Section and
   Tab Section. Those should only be used inside Accordions and Tabs.
* Arrange them as you see fit. I prefer Simple, Image, and Blank at the top,
   then the rest in Alphabetical order. Select Save Settings.
* Adjust your form display, placing the field where you want it.
* Add the field into the Manage display tab.
* Start creating content!

## MAINTAINERS

Current maintainers:

* [drupix](https://www.drupal.org/u/drupix)

This project has been sponsored by:

* [drupal-solutions.ch](https://drupal-solutions.ch)
