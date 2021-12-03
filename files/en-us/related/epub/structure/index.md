---
title: 'EPUB Structure'
slug: Related/EPUB/Structure
tags:
  - EPUB
  - Ebook
  - Ebooks
  - Guide
  - Reference
---
{{EPUBRef}}

An unzipped EPUB file is a folder containing two primary directories and a `mimetype` file. One of
the directories is always named [`META-INF`](/en-US/docs/Related/EPUB/Structure/META-INF) and houses
the container file (`container.xml`). This file defines the path to the
[package file](/en-US/docs/Related/EPUB/Package) in the other directory (the
[content directory](/en-US/docs/Related/EPUB/Structure/Content)). The content directory is commonly
named `OEBPS` (Open Ebook Publication Structure) or `OPS` (Open Publication Structure) and is where
the ebook's navigation, XHTML, CSS and other assets are stored.

An EPUB's structure is made up of the following key components:

* [Open container format](/en-US/docs/Related/EPUB/Structure/OCF) (special zip file that houses the
  publication)
* [`mimetype`](/en-US/docs/Related/EPUB/Structure/mimetype)
* [`META-INF`](/en-US/docs/Related/EPUB/Structure/META-INF) (includes `container.xml`)
* [Content directory](/en-US/docs/Related/EPUB/Structure/Content) (XHTML, CSS, images, audio, etc.)
  * [Package file](/en-US/docs/Related/EPUB/Package) (XML)
  * [Navigation](/en-US/docs/Related/EPUB/Navigation) (XHTML)
