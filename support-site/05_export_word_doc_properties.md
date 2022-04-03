---
layout: page
title: Export word documents 
---

## Introduction
Exporting to word 



## Document properties 
The title of the report is taken from the title html element if present, if not the query name Is used. 
By default we populate the following properties  of the exported word document 
*	Title
*	Creator
*	Creted
*	Modified 
*	Last modified by 


### Setting document properties in the template 
You can create and set document properties in the exported document by rendering a META tag 
```xml
<meta name="word-properties"  data-propName="Prop value" data-prop2Name="prop 2 value"/>
```


### Setting properties at runtime 
We also push all Options as custom properties, enabling the user to fill values at run time and have them exported as document properties in word. 



