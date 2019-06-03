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
<h2>xENNiE$ Blockchain Networks</h2>
<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for freaks..Type in a fr↑">


<table id="myTable" cellspacing="0" cellpadding="3">
<caption>master@9xO</caption>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Network</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Weight</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Pki</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Bitcoin</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">0E+00</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">1N</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Bitcoin BTC</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">5E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">1N1X8i5VuRS1BeMxiy5ZaeensjhsVWdQeC</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Dogecoin DOGE</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">130E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">DFTEuCkJwX3Djh1EMT4XNK6a6NixxrMfhx</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Ethereum ETH</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">90E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">0xd0f79b71a8ffb7f70392630f8bfc900fca27af42</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Litecoin LTC</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">238E&#8722;12</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Luuv1snsyecfcrcmlxgxdrclfglwa4praf</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">everything OS EOS</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">19E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">EOS7eXFPV31bXFUSLisR9A9cv5tp9aVdPKWH1NWjWy3vCukKn3E3G</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Tronix TRX</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">238E&#8722;09</td>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">TVAqvjtirALp4NjUxsygx3Cf5oUwDMKmSf TVAqvjtirALp4NjUxsygx3Cf5oUwDMKmSf</td>
<td  style=""></td>
</tr>
<tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Stellar Lumens XLM</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">3E&#8722;09</td>
<td colspan="2"  valign="bottom"  align="left"  style=" font-size:10pt;">GC6OHSRJ6SL6GP6F4LPF253AAODCGCYHILPICJ47E634GQOYY3FSOENR GDZ4XW3W3YUT3HQT4HC35QNJAVRFXSO666UYPJMXZFIHB5UY6YXQCOVN</td>
</tr><tr>
<td  valign="bottom"  align="left"  style=" font-size:10pt;">Ripple XRP</td>
<td  valign="bottom"  align="right"  style=" font-size:10pt;">3E&#8722;09</td>
<td colspan="2"  valign="bottom"  align="left"  style=" font-size:10pt;">rsZM5t2e9RiK8iq7BeFxSkUUvaupnAubLe rhPVa7YdW8Tfhr2SNH9Rx6SDfV998TGUYd</td>
</tr>
</table>

Thank you, if you contributed, too.🖤
  
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
<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for freaks..Type in a fr↑">


<hr>
<h3>Made with 💥 by ×3.</h3>
<h1>Who?<a href="https://gab.ai/a11">?</a>?</h1>
master x, zzpraf1n1x42af
</body>
</html>
