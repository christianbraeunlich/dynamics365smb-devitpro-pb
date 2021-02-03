---
title: "Report.IsReadOnly Method"
ms.author: solsen
ms.custom: na
ms.date: 11/23/2020
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# Report.IsReadOnly Method
> **Version**: _Available from runtime version 7.0._

Gets if the current report's data access intent is readonly.


## Syntax
```
DataAccessIntent :=   Report.IsReadOnly()
```
> [!NOTE]
> This method can be invoked using property access syntax.

## Parameters
*Report*
&emsp;Type: [Report](report-data-type.md)
An instance of the [Report](report-data-type.md) data type.

## Return Value
*DataAccessIntent*
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)
A value specifying the readonly data access intent.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[Report Data Type](report-data-type.md)
[Getting Started with AL](../devenv-get-started.md)
[Developing Extensions](../devenv-dev-overview.md)