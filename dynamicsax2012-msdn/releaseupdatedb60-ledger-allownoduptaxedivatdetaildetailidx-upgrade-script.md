﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupTaxEdivatDetailDetailIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupTaxEdivatDetailDetailIdx Upgrade Script
ms:assetid: 53d2037f-1d2b-7502-1b34-aa385691a426
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736126(v=AX.60)
ms:contentKeyID: 49708302
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupTaxEdivatDetailDetailIdx Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupTaxEdivatDetailDetailIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the DetailIdx index in the TaxEdivatDetail table not to allow for duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>TaxEdivatDetail</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the TaxEdivatGeneral surrogate key field with the value of the RecId field of the TaxEdivatGeneral table, the DetailIdx index is reset not to allow for duplicate records.

  


