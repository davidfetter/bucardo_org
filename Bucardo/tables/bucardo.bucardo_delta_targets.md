---
title: Bucardo tables bucardo.bucardo delta targets
permalink: /Bucardo/tables/bucardo.bucardo_delta_targets/
---

[Category:Bucardo](/Category:Bucardo "wikilink") [Category:Bucardo_Schema](/Category:Bucardo_Schema "wikilink")

<h2>
Table: bucardo.bucardo_delta_targets

</h2>
<table border="1" cellpadding="3">
<tr>
<th>
Column

</th>
<th>
Type

</th>
<th>
Notes

</th>
</tr>
<tr>
<td>
<b>tablename</b>

</td>
<td>
OID

</td>
<td>
NOT NULL

</td>
</tr>
<tr>
<td>
<b>targetdb</b>

</td>
<td>
TEXT

</td>
<td>
NOT NULL

</td>
</tr>
<tr>
<td>
<b>cdate</b>

</td>
<td>
TIMESTAMPTZ

</td>
<td>
NOT NULL DEFAULT <b>now()</b>

</td>
</tr>
</table>
