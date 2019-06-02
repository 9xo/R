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

<table id="myTable" cellspacing="0" cellpadding="3">
<caption>mast</caption>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Network</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Weight</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Named</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Pki</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Bitcoin</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">0E+00</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">null</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">1N</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Bitcoin BTC</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">5E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">nix</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">1N1X8i5VuRS1BeMxiy5ZaeensjhsVWdQeC</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Dogecoin DOGE</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">130E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">nixx</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">DFTEuCkJwX3Djh1EMT4XNK6a6NixxrMfhx</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Ethereum ETH</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">90E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">gg77</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">0xd0f79b71a8ffb7f70392630f8bfc900fca27af42</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Litecoin LTC</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">238E&#8722;12</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">&#321;uvi</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Luuv1snsyecfcrcmlxgxdrclfglwa4praf</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">everythingOS EOS</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">19E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">3r3333333333</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">EOS7eXFPV31bXFUSLisR9A9cv5tp9aVdPKWH1NWjWy3vCukKn3E3G</td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Tronix TRX</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">238E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">DMK</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">TVAqvjtirALp4NjUxsygx3Cf5oUwDMKmSf</td>
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
