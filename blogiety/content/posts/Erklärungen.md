---
layout: post
title:  How To Blogiety
description: ""
date: 2018-03-08
tags: [sample post,deutsch]
image:
  feature: /images/abstract-3.jpg
  credit: traedas
---

Hier ist eine kurze Erkklärung wie ihr Posts bearbeiten könnt

# Heading 1  wird mit einer '#' gemacht

## Heading 2 wird mit einer '##' gemacht

### Heading 3 wird mit einer '###' gemacht

#### Heading 4 wird mit einer '####' gemacht

##### Heading 5 wird mit einer '#####' gemacht

###### Heading 6 wird mit einer '######' gemacht

### Hier wird Heading 3 benutzt

 **Das ist Fett gedruckt**. Um einen Text Fett gedruckt zu bekommen verwenden man  '** ihr text **'  

<img alt="Smithsonian Image" src="/images/3953273590_704e3899d5_m.jpg" style="float: right;"/>
Bilder werden via HTML eingefügt. Die Pfade sind dabei Relativ anzulegen. Vergesst bitte nicht die Bilder in das Repository hochzuladen.<br><br> Allgemein ist zu sagen, dass die Posts HTML verstehen können. <br><br>
*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times <cite>(That’s a citation)</cite>. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and <abbr title="cascading stylesheets">CSS<abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two
 1. fd
  1. sdf
  2. fsdf

 1. fd
  1. sdf
2. fsdf

Es wird hierbei hochgezählt solange man eine zahl verwendet - 
'1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two
 1. fd
  1. sdf
  2. fsdf'
### Unordered Lists

* Item one
* Item two
* Item three

ungeordnete Listen erstellt man mit einer '*'
## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
| Foot1   | Foot2   | Foot3


So wurde diese Tabelle erstellt.<br>

| Header1 | Header2 | Header3 |<br>
|:--------|:-------:|--------:|<br>
| cell1   | cell2   | cell3   |<br>
| cell4   | cell5   | cell6   |<br>
| cell1   | cell2   | cell3   |<br>
| cell4   | cell5   | cell6   |<br>
| Foot1   | Foot2   | Foot3<br><br>


Einfach kopieren und los geht es!

## Code Snippets

Syntax highlighting mithilfen von Rouge

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

Solche Snippets erstellt ihr wenn ihr folgendes eingebt:<br>
'```css
#container {<br>
  float: left;<br>
  margin: 0 -240px 0 0;<br>
  width: 100%;<br>
}```'


kopiert den nächsten teil und erstetzt den HTML Code durch euren HTML Code
Non Pygments code example

    <div id="awesome">
        <p>This is great isn't it?</p>
    </div> 

 


## Buttons

Buttons könnt ihr auch noch verwenden . Dazu einfach in euren HTML Code welche sich im Post befindet die Klasse btn verwenden. `.btn`.

```html
<a href="#" class="btn btn-success">Success Button</a>
```

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="/" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>
