<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url(https://avatars1.githubusercontent.com/u/13474314?s=24&v=4);
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myTable {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#myTable th, #myTable td {
  text-align: left;
  padding: 12px;
}

#myTable tr {
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<h2>My Customers</h2>

<table id="myTable">
  <tr class="header">
    <th style="width:20%;">Network</th>
    <th style="width:30%;">Weight</th>
    <th style="width:50%%;">^PKI$</th>
  </tr>
  <tr>
    <td>Bitcoin</td>
    <td>4.761904761904762e-11</td>
    <td>1N1X8i5VuRS1BeMxiy5ZaeensjhsVWdQeC</td>
  </tr>
  <tr>
    <td>Dogecoin</td>
    <td>4.761904761904762e-11</td>
    <td>1N1X8i5VuRS1BeMxiy5ZaeensjhsVWdQeC</td>
  </tr>
  <tr>
    <td>Litecoin</td>
    <td>4.761904761904762e-11</td>
    <td>Luuv1snsyecfcrcmlxgxdrclfglwa4praf</td>
  </tr>
  <tr>
    <td>Litecoin</td>
    <td>0.0</td>
    <td>Luuv1snsyecfcrcmlxgxdrclfglwa4praf</td>
  </tr>
  <tr>
    <td>Bitcoin</td>
    <td>4.761904761904762e-11</td>
    <td>1N1X8i5VuRS1BeMxiy5ZaeensjhsVWdQeC</td>
  </tr>
  <tr>
    <td>Berglunds snabbkop</td>
    <td>Sweden</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Koniglich Essen</td>
    <td>Germany</td>
    <td>Laughing Bacchus Winecellars</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Italy</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Ethereum</td>
    <td>8.333333333333334e-10</td>
    <td>0xd0f79b71a8ffb7f70392630f8bfc900fca27af42</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>8.333333333333334e-10</td>
    <td>0xd0f79b71a8ffb7f70392630f8bfc900fca27af42</td>
  </tr>
</table>
  
  
<!-->some freak..js </!-->
<script>
function myFunction() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>


<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for freaks.." title="Type in a fr↑">
</body>
</html>
