# Notes

## Importing content from a PDF

With Scribus 1.5.x you can directly open a PDF with Scribus. This function is still rather experimental and but there are alternative ways to do it:

- for the text, export all of it with pdftotext (or pdftohtml) and load
  it into scribus *or* open it with evince and copy paste it column by
  column.

- for the pictures, export all of them with pdfimages (maybe export them
  once to png and once to jpg, depending on the type of images in your
  document) or open each pdf page with inkscape and copy paste each
  picture into scribus.

- for vector images: open the page with inkscape and copy paste them
  into scribus (you'll get the artwork and the text as vectors) or open
  the page with gimp and save the relevant part as a png.

## File formats support for formatted text

- ODT (Libreoffice, Openoffice, Microsoft Office)
- HTML (Web, Office)
- tagged text
- XTG (Quark Express Tags Documents
- IDML, INDS, ICML Adobe Indesign export files
- PUB (MS Publisher)
- RTF (Microsoft Office)

Partially supported file formats:
- .doc(x) files can be imported through `antiword` but all formatting will be lost.
- .pdf

Sources:
- [Scribus 1.5.0 Release Schedule](http://wiki.scribus.net/canvas/Scribus_1.5.0_Release_Schedule)

## Supported formatting

- Paragraph style
- Character style
- Font name
- Text size
- Bold
- Italic
- Sup / Sub
- underline
- http links
- text alignement
- paragraph (left, right, hanging) indents
- tables
- footnotes
- bullet/ordered lists
- text and background color
- embedded images
- images
- vector graphic
- embedded formulas
- language
- notes
