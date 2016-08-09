---
title: Create a native app in SAP HANA Cloud Platform mobile service for development and operations
description: Learn how to create a native app definition in SAP HANA Cloud Platform mobile service for development and operations
tags: [  tutorial>intermediate, topic>cloud, topic>mobile, products>sap-hana-cloud-platform ]

---
## Prerequisites  
  - **Proficiency:** Intermediate

## Next Steps
   - [Artifact Repository](http://go.sap.com/developer/tutorials/ci-best-practices-artifacts.html)
  - [Back to the Navigator](http://go.sap.com/developer/tutorials/ci-best-practices-intro.html)
  
 
#### Prerequisites
- An appropriate Java JDK version for Nexus is installed on the machine.

### Time to Complete
**10 min**

---

1. Once you have your APPID, create a new service class with the following properties:

    - **Package name:** `com.sap.hana.cloud.samples.weatherapp.api`
    - **Classname:** `WeatherService`

    ![Creating a new Java class](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-java-weatherapp-part8/e2e_08-1.png)

2. Replace the contents of the `WeatherService.java` file with [this code from Github](https://raw.githubusercontent.com/SAP/cloud-weatherapp/0f16e22720cbc5032e9a63af4ee95e2ead6e0761/src/main/java/com/sap/hana/cloud/samples/weatherapp/api/WeatherService.java) and save your changes.


3. Include the full-qualified classname of the `WeatherService` class in the list of JAX-RS services specified in the `web.xml` configuration you did before. The corresponding <init-param> element should now look like this:

    ```xml
    <init-param>
    	<param-name>jaxrs.serviceClasses</param-name>
       	<param-value>
       		com.sap.hana.cloud.samples.weatherapp.api.AuthenticationService,
			com.sap.hana.cloud.samples.weatherapp.api.FavoriteCityService,
			com.sap.hana.cloud.samples.weatherapp.api.WeatherService
		</param-value>
    </init-param>
    ```

    ![Modifying the web.xml file to include the new service](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-java-weatherapp-part8/e2e_08-3.png)
