TODO:
- define a typographic grid


page:
- A5 portrait double sided
- unit mm
- inside: 20mm
  outside: 40mm
  top: 14.111
  bottom 20.111
- bleeds: 5mm

paragraph styles:
- title:
- h1
- h2
- h3
- toc_h1: tab right 87.647
- toc_h2: tab right 87.647

templates:
- chapter title
  - right page
  - gray rectangle:
    x:0mm, y:60mm, w:pagewidth, h:41.5(41.423mm), black, shade: 30% (both fill and stroke)
  - guides:
    h:52.268mm
- normal right
  - guides:
    v:128.171 (aim right align page number and non body text content)
  - page number: x: 116.318mm, y: 199.493mm, w:12.582mm, h:11.793mm, right align, Bitsream Charter Bold, Fixed Linespacing 15pt
  - footer: x: 38.677mm, y: 200.617, w: 69.153, h:5.175, CMU Classical Serif italic, 7pt (partially with a saturation of 50%), Fixed Linespacing: 10pt, Right align
- normal left
  - guides:
    v:18.062 (aim left align page number and non body text content)
  - page number: x: 18.374mm, y: 199.493mm, w:12.582mm, h:11.793mm, right align, Bitsream Charter Bold, Fixed Linespacing 15pt
- empty left
  - 

Chapter title page:
- title as h1

Table of contents:
- title as h2
