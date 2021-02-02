---
title: "Basics of Markdown Coding"
date: 2019-06-17T23:53:00+01:00
draft: true
hideLastModified: true
summary: "This summary \
is \
multiline"
tags: ["custom_summary", "code"]
---

Example code:


Lists
-----

To define a list of items, just put a `*`, a `-`, or a `+` at the start of the line of each item of the list followed by at least a space, to end the list, leave a blank line

* red
* green
* blue

- white
- grey
- black
+ yellow
+ pink
+ orange

You can also define numbered list, putting a number followed by a `.` or a `)` and a space at the start of the line (you may use any number, the first one is taken to start counting, then it will increment by one):

3.
2. you may leave blank items
1) or start
1) again

You can insert any block inside a list, you have to respect the indentation of the text of the list item

- A *paragraph* of text
  (spanning multiple lines),

  ```
  fenced code,
  ```

      indented code (4 spaces + 2 spaces for the list
      indentation, one blank line above, one below),

  > quotes,

  - another
    * list
      + (and so on...),

  - ### or
