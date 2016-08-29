---
title: validate
description: validated
tags: [tutorial:product/hana_studio]
---

[ACCORDION-BEGIN [STEP 1](#1Rule exact-match)]

### Rule
exact-match

### Question
Marina's age?

### Match
секрет на 100 лет

[VALIDATE_1]

>### Note
>This is a note. 
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 2](#1###Ruleregex-substring)]

You can use:

***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font

[DONE]
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 3](#1###Ruleregex-substring)]

### Rule
regex-substring

### Question
Marina's age?

### Match
secret

[VALIDATE_4]

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 4](#the 3th step)]
***Code blocks:***

```markup
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 5](#1###regex-begins-with)]
### Rule
regex-begins-with

### Question
Enter Marina's surname?
A. Amosova
B. Mamosova
C. GFkjdf

### Match
A

[VALIDATE_7]

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 6](#the 6 step)]
***Lists***

  **Example:** 
  
Sometimes you want numbered lists:

1. One
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 7](#1###regex-with-id-exact-match)]

###Rule
regex-with-id-exact-match

###Question
Enter URL to your application //[id] will be changed to uid

###Match
https://codejam[id]trail.hanatrial.ondemand.com/codejam/mylibrary.xsjs

[VALIDATE_11]

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 8](#the sпрпр lectitur. Adl nec. Eu p pro disceecond step)]
### Rule
regex-begins-with

### Question
age?

### Match
se c ret

[VALIDATE_10]

[ACCORDION-END] 



