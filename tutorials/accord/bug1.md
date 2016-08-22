---

title: User is redirected in bottom by click next accordion if previous accordion has long content
description: Part 3.1: Setting up a Git/Gerrit Instance.
tags: [  tutorial>intermediate, tutorial:type/project ]

---

## Prerequisites

  - **Proficiency:** Intermediate

## Next Steps
 
  - [Build Scheduler](http://go.sap.com/developer/tutorials/ci-best-practices-build.html)
  - [Back to the Navigator](http://go.sap.com/developer/tutorials/ci-best-practices-intro.html)

---


What we offer in this part is not more than a basic recipe to set up a minimum installation including only those components on Linux that we consider as absolutely necessary to run a CI/CD process for development with SAP. However, the setup best suited to your concrete requirements cannot be part of this document because it highly depends on your concrete local situation, the network setup, the overall landscape into which the CI/CD process will be embedded, and so on. Therefore, we will restrict ourselves here to showing only the principles and the core elements.

[ACCORDION-BEGIN [STEP 1](#1 short)]
You can use:

***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 2](#2long)]
Mandamus adversarium intellegebat per ne, ex graece animal nec. Eu purto dicat nam. Duo quas lorem maluisset cu, elit equidem vis at. Simul quodsi ne eum, ne sit incorrupte complectitur. Ad pro discere corrumpit adipiscing, ex mei docendi efficiantur, eam epicurei reprehendunt ne.

Dolorem partiendo salutatus ne sea, eum quodsi molestie no. Sed ne error soluta. Dicit cotidieque interpretaris cum ea, mel dictas evertitur ut, usu at postulant appellantur. Meis nostrum nam eu, ne consul cotidieque sea, audiam dolorem temporibus est ea. Vel labitur epicuri ne. Id vix duis fabellas.

Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
Laoreet deseruisse ut pro, ad cetero definiebas usu, at commodo senserit deterruisset mel. Ex graeco sanctus his, has no ullum adolescens, cu vix quando probatus vulputate. Albucius consequat mel eu, id maiestatis comprehensam eum, has civibus ullamcorper in. Erant feugait oporteat at his, te eam graecis constituto.
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 3](#3short)]
***Code blocks:***

```markup
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 4](#4long)]
```markup
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
```
[ACCORDION-END]  

[ACCORDION-BEGIN [STEP 5]()]
You can use:

***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 6]()]
***Headers***

  **Example:** 
## This is an h2 header 
### This is an h3 header
###### This is an h6 header
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 7](#the 7th step)]
***Images*** (all images are stored on GitHub, URLs are rewritten to absolute)

Format: `![Alt Text](url)`

  **Example:** 
![Image](https://octodex.github.com/images/yaktocat.png)
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 8]()]
***Blockquotes***

  **Example:** 
In the words of Abraham Lincoln:
> Pardon my French
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 11](#11)]
***There are three different types of messages: Note, Caution and Warning.***

>### Warning
>jhkjhkjhkjhkj
>>### Warning
>>>### Warning
>>>>### Warning
>>>>This is a Warning. 

&nbsp;

>### Caution
>iikjhiojhioji
>>### Caution
>>This is a Caution. 
gfhfdghfhfghfhggfjhgfjghfj
&nbsp;

>### Note
>This is a note. 

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Note
>This is a note. 

&nbsp;

>### Caution
>iikjhiojhioji

&nbsp;

>### Warning
>jhkjhkjhkjhkj

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9,1](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Note
>This is a note. 

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9,2](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Caution
>iikjhiojhioji

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9,3](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Warning
>jhkjhkjhkjhkj

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9,4](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Note
>This is a note. 

&nbsp;

>### Caution
>iikjhiojhioji

&nbsp;
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 9,5](#9)]
***There are three different types of messages: Note, Caution and Warning.***

>### Note
>This is a note. 

&nbsp;

>### Warning
>jhkjhkjhkjhkj

&nbsp;
[ACCORDION-END] 


[ACCORDION-BEGIN [STEP 10](#10)]
***Tables:***

  **Example:** 

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

[ACCORDION-END] 



[ACCORDION-BEGIN [STEP 12](#12)]
[ACCORDION-END] 

Other contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther contentOther content

[ACCORDION-BEGIN [header2]()]
***Headers***

  **Example:** 
## This is an h2 header 
[ACCORDION-END]

[ACCORDION-BEGIN [header3]()]
### This is an h3 header
[ACCORDION-END]

[ACCORDION-BEGIN [header4]()]
#### This is an h4 header
[ACCORDION-END]

[ACCORDION-BEGIN [header5]()]
##### This is an h5 header
[ACCORDION-END]

[ACCORDION-BEGIN [header6]()]
###### This is an h6 header
[ACCORDION-END]






