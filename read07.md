# Tables
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

## `<table>`
The `<table>` element is used
to create a table. The contents
of the table are written out row
by row.
## <tr>
You indicate the start of each
row using the opening `<tr>` tag.
(The tr stands for table row.)
It is followed by one or more
`<td>` elements (one for each cell
in that row).
At the end of the row you use a
closing `</tr>` tag.
## `<td>`
Each cell of a table is
represented using a `<td>`
element. (The td stands for
table data.)

```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table
```
## Table Headings
## `<th>`
The `<th>` element is used just
like the `<td>` element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)

# Long Tables
## `<thead>`
The headings of the table should
sit inside the `<thead>` element.
## `<tbody>`
The body should sit inside the
`<tbody>` element.
## `<tfoot>`
The footer belongs inside the
`<tfoot>` element.