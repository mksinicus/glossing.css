# glossing.css

A minimalist CSS library for linguistic glossing.

This stylesheet integrates best with [pandoc Markdown](https://pandoc.org/MANUAL.html) with extension `table_captions` enabled. Yes, we use `<table>` to represent glossings in HTML, because glossings are literally data. 

With pandoc extension `table_captions`, we take contents generated into  `<caption>` as the line for translation in linguistic glossing, which is apparently more reasonable than using table cell with `colspan` attribute. 

## How to use

*todo*

## Note

We used selector `:is()`, if you need you may change that into more primitive expressions. 

## To-dos

- minimize to a `glossing.min.css`

