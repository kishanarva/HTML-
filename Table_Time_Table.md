# Table.html – Simple Class Time Table

```html
<html>
<head>
<title>Time Table</title>
</head>
<body>

<h2 align="center">Time Table</h2>

<table border="1" align="center" cellpadding="10">

<thead bgcolor="skyblue">
<tr>
<th colspan="6">Class Time Table</th>
</tr>
<tr>
<th>Day</th>
<th>9-10</th>
<th>10-11</th>
<th>11-12</th>
<th>12-1</th>
<th>2-3</th>
</tr>
</thead>

<tbody>
<tr bgcolor="lightyellow">
<td>Monday</td>
<td>Java</td>
<td>DBMS</td>
<td>OS</td>
<td rowspan="5" bgcolor="orange">Lunch</td>
<td>Maths</td>
</tr>

<tr bgcolor="lightgreen">
<td>Tuesday</td>
<td>OS</td>
<td bgcolor="pink">Elective</td>
<td>Java</td>
<td>DBMS</td>
</tr>

<tr bgcolor="lightyellow">
<td>Wednesday</td>
<td colspan="2" bgcolor="lightgreen">Java Lab</td>
<td>Maths</td>
<td>OS</td>
</tr>

<tr bgcolor="lightgreen">
<td>Thursday</td>
<td>DBMS</td>
<td>Java</td>
<td bgcolor="pink">Elective</td>
<td>Maths</td>
</tr>

<tr bgcolor="lightyellow">
<td>Friday</td>
<td>Maths</td>
<td>OS</td>
<td>DBMS</td>
<td bgcolor="lightgreen">DBMS Lab</td>
</tr>
</tbody>

<tfoot bgcolor="skyblue">
<tr>
<td colspan="6">End of Time Table</td>
</tr>
</tfoot>

</table>
</body>
</html>
```

## Conditions satisfied

- **Title:** Time Table
- **Table header and footer:** `<thead>` and `<tfoot>`
- **Column span:** `colspan="6"` and `colspan="2"`
- **Row span:** `rowspan="5"`
- **Different cell colours:** Blue, pink, green and orange
- **Different row colours:** Light yellow and light green
- **Lab hours:** Green
- **Elective hours:** Pink

**How to run:** Save the HTML code as `Table.html` and open it in a web browser.
