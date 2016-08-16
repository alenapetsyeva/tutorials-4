---

title:fsvfdvfdvfd Continuous Integration (CI) Best Practices with SAP: Landscape Configuration
description:vfvfvfdvfvd Pfart 3.4: Configuring the CI Component Landscape.
tags: [  tutorial>advanced, tutorial:type/project ]

---

## Prerequisites  

    - [Source](http://go.sap.com/developer/tutorials/ci-best-practices-scm.html)
 

## Next Steps

  - [Back to the Navigator](http://go.sap.com/developer/tutorials/ci-best-practices-intro.html)
  
---


After having installed and started the components that are involved in our CI process landscape, there are some more steps to configure to make them smoothly work together within a process pipeline.


### Gerrit Parent Project

To avoid the need to maintain the Jenkins permissions in Gerrit for each project separately, it is a good practice to create a common parent project that hosts the needed permissions.
