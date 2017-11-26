Today I learned how to implement tables. They are a lot like list elements. In the simplist form you can start with <table> </table> as the surrounding element like you would use <ol> or <ul>. Within <table> you have <tr> </tr> which displays a row of content. The difference is you place <td> </td> within <tr> </tr> to create the cells of a row and fill them with content. When everything is put together, it will look like the example below...

<table>
  <tr>
    <td> Name</td>
    <td> Age </td>
    <td> Weight</td>
  </tr>
  <tr>
    <td> Johnny </td>
    <td> 34 </td>
    <td> 165 </td>
  </tr>
</table>

 

This will display a description of each cell name, weight, and age and fill in data the next row below them. I also learned you can use <th> </th> element to create table headers in bold font.
