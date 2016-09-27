---
title: validate
description: validated
tags: [products>sap-hana-cloud-platform, topic>cloud, topic>java, tutorial>intermediate]
---

[ACCORDION-BEGIN [STEP 1](#1Rule exact-match)]

### Question
url https://kb.epam.com?
### Match
200

[VALIDATE_1]

>### Note
>This is a note. 
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 1.1](#1Rule exact-match)]

### Question
Marina's age?
### Match
секрет на 100 лет 

[VALIDATE_1]

>### Caution
>iikjhiojhioji

&nbsp;

>### Warning
>jhkjhkjhkjhkj

&nbsp;

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 2](#1###Ruleregex-substring)]

###Question
Marina's age?

###Match
secret

[VALIDATE_4]

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 3](#1###regex-begins-with)]
###Question
Enter Marina's surname?

###Match
A

[VALIDATE_7]

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

[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 4](#1###regex-with-id-exact-match)]

###Rule
regex-with-id-exact-match

###Question
Enter URL to your application //[id] will be changed to uid

###Match

###Question
Enter your  //[id] 

###Match
user [id]

[VALIDATE_10]

[ACCORDION-END] 





