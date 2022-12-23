# fb2schema

This repository contains a handwritten xml schema for the FictionBook 2.2 format in the RELAX NG compact syntax.

It was implemented because of the [official repository](https://github.com/gribuser/fb2) contains an outdated schema and the [official site](http://www.fictionbook.org/index.php/XML_%D1%81%D1%85%D0%B5%D0%BC%D0%B0_FictionBook2.2) was down. Also, the official site stil contains dead links to `xsd`-files.

Also the repository contains the reference XSD schema for the FictionBook 2.2 restored with the web-archive searches.

## Deviations

My schema has following deviations from the reference scheme:

- It doesn't describe `FictionBook/description/output` element (in-document instruction for generating output free and payed documents)
- Has a merged genre list for the FictionBook 2.0 and FictionBook 2.2 (some real world books have a list with the old and new genres)
- Only two bodies are supposed: for the main text and for footnotes (like a FictionBook 2.0)