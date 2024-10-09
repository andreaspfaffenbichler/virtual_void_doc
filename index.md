---
title: virtual void
layout: home
nav_order: 1
permalink: /
---

# virtual void - a vocabulary library for programming in the large
# terms and definitions in context of this documentation

##  erased interface
an object, whitch , members are function pointers, and every function has as first parameter "self". This is a pointer to (eventually const )void.

##  implemented interface
an object derived from an interface, with no additional members and where all members point to vaild functions.
Thes funtion are filled by a templated consztuctuer. The pemplate parameter is called the erased type.
These functions cast the self parameter to a pointer to the erased type, and delegete via this pointer to the function, for witch this was erased through self.

## lifetime holder
An object with manages the lifetime of an other object. There are 
### observer
### shard const
### unique
### value

## erased lifetime holders

## static cast

## dynamic cast

## upcast 
static

## downcast
static, dynamic

## crosscast
dynamic , from one "interface" to an other

## open method


[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
