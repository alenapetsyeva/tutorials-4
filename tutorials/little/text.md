---
title: text
description: text with qr
tags: [tutorial:product/sapHana, tutorial:product/hana_studio]
qrcode: true
---
***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font

## Prerequisites  
 - **Proficiency:** Intermediate
 - **Tutorials:** While not required, it would be useful to complete the [An Open Data Protocol (OData) primer for developers](http://go.sap.com/developer/tutorials/hcp-webide-odata-primer.html) and be familiar with SAP Web IDE before beginning this tutorial.

## Next Steps
 - [Build an SAPUI5 app based on your data model and run it with mock data](http://go.sap.com/developer/tutorials/hcp-webide-build-app-mock-data.html)

## Details
### You will learn  
In most cases, a live OData service will be available when building an application. For times when a service is not available, it is still possible to build apps with SAP Web IDE with a file-based data model and then run on simulated data (referred to as “mock data” in SAP Web IDE). Once the data service is available, the app can then be configured to run against the service rather than the mock data with no other changes. The mock data approach is also useful if you want to prototype an app and have realistic data appear in the UI.

In this tutorial, you will create an OData model with a Sales Order related data fields in two parts:
 - **Part 1:** Create the minimum data model needed to build a basic app based on one OData collection
 - **Part 2:** The second part adds an additional collection as a `NavigationProperty` to your primary collection similar to what you used in the earlier Mobile Guides.

Both versions of the metadata document will allow you to use the Web IDE template wizard to create an app in the next tutorial (and then switch it to a live service).

Additionally, the full data model is provided at the bottom of this document if you want to refer to it later for use in your projects.

**Background:**

A metadata document is defined in the Common Schema Definition Language (CSDL). There is an exhaustive description of [CSDL](http://docs.oasis-open.org/odata/odata/v4.0/odata-v4.0-part3-csdl.html) here, but this tutorial will focus on a subset of the full language to build the metadata needed for this tutorial.  

The metadata document you will build for part 1 (one OData collection) will have the following structure:

Component         | Description
:--------------   | :-------------
XML declaration   | Not necessary for `.edmx` files, but useful to include if you want to view the file in an editor that supports XML syntax highlighting
`Edmx` and `DataServices` elements | The “wrapper” for your data model
`Schema`          | Container for the `EntityTypes`, `Associations` and `EntityContainer` elements
`EntityType`      | Defines the data model for the OData collection
`EntityContainer` | Exposes the OData collection

 ![Part 1 OData Model Structure](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-create-odata-model/mob4-1_part1_intro.png)

Part two of this tutorial adds in a second `EntityType` and the required elements to set up the `NavigationProperty`. In the Web IDE template you have been using the data from the `NavigationProperty` (Suppliers) has been displayed in the Info or Suppliers tab.

### Time to Complete
**20 Min**.

### Part 1

1. Open Web IDE, select the Local folder and create a new folder called `Metadata`.

2. Right-click on the `Metadata` folder, and create a new file named `m104metadata_no_nav.edmx`.

3. To start with, paste in the text below as the entity model wrapper of the metadata file. The wrapper consists of the following:

    Item          | Description
    :------------ | :-------------
    `<?xml ...?>` | XML encoding declaration. Here you specify the XML version, the encoding used in the file, and that it is stand-alone (does not rely on information from an external source)
    `edmx:DataServices` | A CSDL formatted document requires `edmx:Edmx` as the root element, and that it contains a single `edmx:DataServices` element
