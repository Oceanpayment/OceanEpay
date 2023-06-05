2022-12-08
<h4>1.Added transaction and clearing fields:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>print</td>
    <td>Whether to print receipt<br>1: Yes<br>0: no<br>The priority of passing parameters in this field is higher than that of the background configuration. If this parameter is passed, it will decide whether to print</td>
  </tr>
</table>

<h4>2.Added reprint API.</h4>
<h5>Request parameters:</h5>
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>type</td>
    <td>type:<br>Sale: transaction<br>Void: void.</td>
  </tr>
  <tr>
    <td>app_id</td>
    <td>app_id assigned by Oceanpayment.</td>
  </tr>
  <tr>
    <td>timestamp</td>
    <td>current timestamp.</td>
  </tr>
  <tr>
    <td>version</td>
    <td>version number.</td>
  </tr>
  <tr>
    <td>order_number</td>
    <td>Order number, used when trading/cancelling.</td>
  </tr>
  <tr>
    <td>callback</td>
    <td>Call the app to accept the return result intent package name, json format string: {"packageName":"xxxx","className":"xxxx"}, two parameters, the first is the package name path, and the second is the callback The full path of the activity.</td>
  </tr>
  <tr>
    <td>sign</td>
    <td>Splice the request parameter names according to the dictionary and sign them with sha256.</td>
  </tr>  
</table>

<h5>Response parameters:</h5>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>type</td>
    <td>type:<br>Sale: transaction<br>Void: void.</td>
  </tr>
  <tr>
    <td>app_id</td>
    <td>app_id assigned by Oceanpayment.</td>
  </tr>
  <tr>
    <td>order_number</td>
    <td>Order number, used when trading/cancelling.</td>
  </tr>
  <tr>
    <td>status</td>
    <td>Reprinted result status<br>0: failed<br>1: success</td>
  </tr>
</table>
