﻿---
title: ReleaseUpdateTransformDB50_FiscalCal.updateFiscalCalendarFields Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_FiscalCal.updateFiscalCalendarFields Upgrade Script
ms:assetid: ece97ec5-875f-b80b-097a-7802bd37101d
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719952(v=AX.60)
ms:contentKeyID: 49712024
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_FiscalCal.updateFiscalCalendarFields Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_FiscalCal</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateFiscalCalendarFields</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the CalendarID and Description fields in the FiscalCalendar table from the mapping that is defined in the Del_FiscalCalendarMapping table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Live</p>
<p>Preprocessing 60: Delta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX Source</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p>
<p>Microsoft Dynamics AX 2009</p></td>
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
<td><p>FiscalCalendar</p></td>
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
<th><p>From Table: Del_FiscalCalendarMapping</p></th>
<th><p>To Table: FiscalCalendar</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


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
<td><p>FiscalCalendar</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


