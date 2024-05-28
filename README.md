<p><a target="_blank" href="https://app.eraser.io/workspace/6A0H5vU8C2KxQO3MMKGe" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

## PROJECT OVERVIEW👋
**Here are some ideas to get you started:**

This is the [﻿eraser.io](https://eraser.io/) code to get the visualisation of the `Microservice-Based System Overview` 

```
// Title and Nodes
title Microservice-Based System Overview

ERP Service [color: blue, icon: tool] {
  ERP Frontend [icon: react]
  ERP Backend [icon: nodejs, label: "ERP Backend"] // entry point
  ERP Database [icon: postgresql, label: "erp"]
}

HRM Service [color: green, icon: users] {
  HRM Frontend [icon: react]
  HRM Backend [icon: nodejs, label: "HRM Backend"] // entry point
  HRM Database [icon: postgresql, label: "hrm"]
}

PMS Service [color: red, icon: heart] {
  PMS Backend [icon: laravel] // entry point
  PMS Database [icon: postgresql, label: "laravel"]
}

 Syncronizer{
Message Broker [icon: RabbitMQ]
Message Broker alternative [icon: kafka]
 }

// Connections
ERP Frontend > ERP Backend
ERP Backend > ERP Database
HRM Frontend > HRM Backend
HRM Backend > HRM Database
PMS Backend > PMS Database

// Message broker connections
ERP Backend <> Message Broker: subscribe/publish user.created
HRM Backend <> Message Broker: subscribe/publish user.created
PMS Backend <> Message Broker: subscribe/publish user.created

// Special case handling
PMS Backend > ERP Backend: publish user of type host to customer table
```
it looks like : 

![cloud arch.png](/.eraser/6A0H5vU8C2KxQO3MMKGe___zP77iWJowZaHU8vz46YnpVCw3sT2___MMguNGhPmr3PHo-InZyOE.png "cloud arch.png")

![user sync flow seq diag.png](/.eraser/6A0H5vU8C2KxQO3MMKGe___zP77iWJowZaHU8vz46YnpVCw3sT2___wi7T15nUV7TjkJq9UWTNE.png "user sync flow seq diag.png")

You can get a view on the project link at [﻿View on canvas](https://app.eraser.io/workspace/6A0H5vU8C2KxQO3MMKGe?elements=uLSIuWuo0M9P4Y_rSQzrgw) or the entier project at [﻿View ](https://app.eraser.io/workspace/6A0H5vU8C2KxQO3MMKGe?elements=uLSIuWuo0M9P4Y_rSQzrgw) 


<!-- eraser-additional-content -->
## Diagrams
<!-- eraser-additional-files -->
<a href="/README-User Data Synchronization in Microservice-Based System-1.eraserdiagram" data-element-id="A7OhIStffAweH5_4ohAkJ"><img src="/.eraser/6A0H5vU8C2KxQO3MMKGe___zP77iWJowZaHU8vz46YnpVCw3sT2___---diagram----0593dd465fd0d1692f646f9a6d5b06dc-User-Data-Synchronization-in-Microservice-Based-System.png" alt="" data-element-id="A7OhIStffAweH5_4ohAkJ" /></a>
<a href="/README-Microservice-Based System Overview-2.eraserdiagram" data-element-id="GHjEBQmIXW3A5wt6s7X36"><img src="/.eraser/6A0H5vU8C2KxQO3MMKGe___zP77iWJowZaHU8vz46YnpVCw3sT2___---diagram----770dede005fc132d018dae8cd4d117f2-Microservice-Based-System-Overview.png" alt="" data-element-id="GHjEBQmIXW3A5wt6s7X36" /></a>
<!-- end-eraser-additional-files -->
<!-- end-eraser-additional-content -->
<!--- Eraser file: https://app.eraser.io/workspace/6A0H5vU8C2KxQO3MMKGe --->