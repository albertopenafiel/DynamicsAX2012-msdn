﻿---
title: ReleaseUpdateDB41_Basic.updateActivityNumberSequenceRef Upgrade Script
TOCTitle: ReleaseUpdateDB41_Basic.updateActivityNumberSequenceRef Upgrade Script
ms:assetid: 3494dd76-0c20-8f2d-206a-e590dd45fbe8
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685132(v=AX.60)
ms:contentKeyID: 49707584
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB41\_Basic.updateActivityNumberSequenceRef Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB41_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateActivityNumberSequenceRef</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Constructs a NumbersequenceTable record for each EDT by first creating a default scope.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Basic</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>NumberSequenceTable</p></td>
</tr>
</tbody>
</table>


## Remarks

The default scope is either a data area or a global scope.

  


