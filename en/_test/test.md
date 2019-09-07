TAGS: test
AUTHORS: Masahiro Fujimoto; mfujimot@gmail.com; github:mfuji09
         Sphinx; sphinx@mozilla.net; mdn:SphinxKnight

# Examples for demonstration

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
This page lists out the default bindings (keyboard shortcuts).

The second paragraph. Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

A [link](https://dookbook.info/).
A **strong text**,
*italic text*,
++inserted text++,
~~deleted text~~,
`code text`,
2^10^=1024,
H~2~O=water.

## Heading 2-1

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

## Table

| Key | Command | Hot |
| ------------- | --- | --- |
| !!!Ctrl!!! + C | Copy | 5 |
| !!!Ctrl!!! + V | Paste | 1 |
| !!!Ctrl!!! + B | Bold | 2 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |
| !!!Ctrl!!! + B | Bold | 3 |

### Table with column alignment

| Key | Command | Hot |
| ------------- | :---: | ---: |
| !!!Ctrl!!! + C | Copy | 5 |
| !!!Ctrl!!! + V | Paste | 1 |
| !!!Ctrl!!! + B | Bold | 2 |
| !!!Ctrl!!! + B | Bold | 3 |

## Heading 2-2

something about heading 2

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

### Heading 3

Something about heading 3

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

## List

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).

### Unordered List

* Windows lets you perform most tasks directly from the keyboard
* Windows lets you perform most tasks directly from the keyboard
* Windows lets you perform most tasks directly from the keyboard

### Ordered List

1. Windows lets you perform most tasks directly from the keyboard
2. Windows lets you perform most tasks directly from the keyboard
3. Windows lets you perform most tasks directly from the keyboard

### Definition List

Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

## Block Quote

As Kanye West said:

> We're living the future so
> the present is our past. 你好,世界！

## Horizontal Rule

***

## Abbreviation

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium

## Attribute List {: #head-id}

Windows lets you perform most tasks directly from the keyboard.
This page lists out the default bindings (keyboard shortcuts).
Windows lets you perform most tasks directly from the keyboard.
This page lists out the **default**{: attrname="value" } bindings (keyboard shortcuts).
{: #someid .someclass attrname='value' }

## Code Block

### HTML

```html
<!DOCTYPE html>
<html>
<head>
  <title>Title</title>
  <style>body {width: 500px;}</style>
</head>
<body>
  <p checked class="title" id='title'>Title</p>
  <!-- here goes the rest of the page -->

  <script>
    function $init() {return true;}
  </script>
</body>
</html>
```

### XML

```xml
<xml>
  <tag1 attr="value">tag-1 text</tag>
</xml>
```

### CSS

```css
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}

body, .usertext {
  color: #F0F0F0; background: #600;
  font-family: Chunkfive, sans;
}

@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
```

### JavaScript

```javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }
}

export  $initHighlight;
```

### Python

```python
import sys

print('hello')
sys.exit()

@requires_authorization
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
```

### Markdown

```markdown
## Heading 2

### Heading 3

A paragraph with a **strong** text and *italic* text.
```

### Bash

```bash
#!/bin/bash

###### CONFIG
ACCEPTED_HOSTS="/root/.hag_accepted.conf"
BE_VERBOSE=false

if [ "$UID" -ne 0 ]
then
 echo "Superuser rights required"
 exit 2
fi

genApacheConf(){
 echo -e "# Host ${HOME_DIR}$1/$2 :"
}
```

### INI/TOML

```toml
; boilerplate
[package]
name = "some_name"
authors = ["Author"]
description = "This is \
a description"

[[lib]]
name = ${NAME}
default = True
auto = no
counter = 1_000
```

## Footnote

Footnotes have a label[^label1] and the footnote's content[^label2].

[^label1]: A footnote on the label: "label1".
[^label2]: A footnote on the label: "label2".

///Footnotes Go Here///

## Admonition

!!! warn
    You should note that the title will be automatically capitalized.

!!! error "Don't try this at home"
    You should note that the title will be automatically capitalized.

!!! info ""
    This is a admonition box without a title.

## Glossary

This is a glossary: Computer Programming, Computer programming, computer pRogramming.

## Image

![An image](github-logo.svg)
