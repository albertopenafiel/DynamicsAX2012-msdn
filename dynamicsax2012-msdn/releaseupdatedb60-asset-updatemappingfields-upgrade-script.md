﻿---
title: ReleaseUpdateDB60_Asset.updateMappingFields Upgrade Script
TOCTitle: ReleaseUpdateDB60_Asset.updateMappingFields Upgrade Script
ms:assetid: ad1a812c-d4b3-196b-d7b7-adb8e168857e
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686509(v=AX.60)
ms:contentKeyID: 49710463
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Asset.updateMappingFields Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Asset</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateMappingFields</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Add special field mapping for the AssetTable table.</p></td>
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
<td><p>Fixed Asset</p></td>
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
<td><p>AssetTable</p></td>
</tr>
</tbody>
</table>


## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: AssetTable</p></th>
<th><p>To Table: AssetTable</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AssetActivityCode_BR</p></td>
<td><p>AssetActivityCode</p></td>
</tr>
</tbody>
</table>

  


