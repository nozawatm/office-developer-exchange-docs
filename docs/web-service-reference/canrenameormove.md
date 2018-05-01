---
title: "CanRenameOrMove"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
 
localization_priority: Normal
api_name:
- CanRenameOrMove
api_type:
- schema
ms.assetid: fe0cdb04-5f2b-4f1d-9d12-7ace0883cd86
description: "The CanRenameOrMove element indicates whether a managed folder can be renamed or moved by the customer."
---

# CanRenameOrMove

The **CanRenameOrMove** element indicates whether a managed folder can be renamed or moved by the customer. 
  
```
<CanRenameOrMove/>
```

 **Boolean**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

None.
  
#### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[ManagedFolderInformation](managedfolderinformation.md) <br/> |Contains information about a managed folder.  <br/> |
   
## Text value

The text value represents a Boolean value. A value of **true** indicates that the folder can be renamed or moved; a value of **false** indicates that the folder cannot be renamed or moved. 
  
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema name  <br/> |Types schema  <br/> |
|Validation file  <br/> |Types.xsd  <br/> |
|Can be empty  <br/> |False  <br/> |
   
## See also

#### Concepts

[EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
