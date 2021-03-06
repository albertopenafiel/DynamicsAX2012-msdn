﻿---
title: ReleaseUpdateDB60_PurchReq.migrateVendReqJourandTrans Upgrade Script
TOCTitle: ReleaseUpdateDB60_PurchReq.migrateVendReqJourandTrans Upgrade Script
ms:assetid: 3cec6427-4050-13d3-5580-73c13c87c867
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685313(v=AX.60)
ms:contentKeyID: 49707765
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_PurchReq.migrateVendReqJourandTrans Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_PurchReq</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>migrateVendReqJourandTrans</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Moves data from the VendReqJour and VendReqTrans tables to the PurchReqTableHistory and PurchReqLineHistory tables, respectively. The PurchReqTableHistory and PurchReqLineHistory tables are new tables introduced in Microsoft Dynamics AX 2012.</p></td>
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
<td><p>SRM</p></td>
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
<td><p>PurchReqTableHistory</p></td>
</tr>
<tr class="even">
<td><p>PurchReqLineHistory</p></td>
</tr>
<tr class="odd">
<td><p>VendReqJour</p></td>
</tr>
<tr class="even">
<td><p>VendReqTrans</p></td>
</tr>
</tbody>
</table>


## Remarks

Moves data from the VendReqJour and VendReqTrans tables to the PurchReqTableHistory and PurchReqLineHistory tables, respectively. After the migration, history data for the purchase requisition would be available in the PurchReqTableHistory, PurchReqLineHistory, and other new tables.

## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PurchReqTableHistory</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>PurchReqLineHistory</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>VendReqJour</p></td>
<td><p>*</p></td>
</tr>
<tr class="even">
<td><p>VendReqTrans</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


