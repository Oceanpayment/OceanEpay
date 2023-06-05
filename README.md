Update Time:2022-08-30.
<h4>1.Added transaction response parameters:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>account</td>
    <td>Oceanpayment MID.</td>
  </tr>
  <tr>
    <td>terminal</td>
    <td>Oceanpayment TID.</td>
  </tr>
  <tr>
    <td>method</td>
    <td>Payment method<br>Output Alipay when getting Alipay<br>Output Alipay when getting Alipay_Offline<br>Output WeChatPay when getting WeChatPay<br>Output WeChatPay when getting WeChatPay_Offline</td>
  </tr>
  <tr>
    <td>batch_number</td>
    <td>Current batch number.</td>
  </tr>
  <tr>
    <td>bill_number</td>
    <td>Current order number.</td>
  </tr>
  <tr>
    <td>order_amount</td>
    <td>Amount of the transaction.</td>
  </tr>
  <tr>
    <td>order_currency</td>
    <td>Transaction currency<br>Adopt international standard ISO 4217.</td>
  </tr>
  <tr>
    <td>date_time</td>
    <td>Trading time, the format is as follows: 2018-10-15 11:05:26<br>When Sale is: transaction time<br>Void is for: void time<br>The details are the same as the Date Time printed on the receipt.</td>
  </tr>
</table>

<h4>2.Added response parameters for machine cleaning:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>account</td>
    <td>Oceanpayment MID.</td>
  </tr>
  <tr>
    <td>terminal</td>
    <td>Oceanpayment TID.</td>
  </tr>
  <tr>
    <td>uid</td>
    <td>UID when clearing the machine<br>The details are the same as the UID printed on the receipt</td>
  </tr>
  <tr>
    <td>batch_number</td>
    <td>Current batch number.</td>
  </tr>
  <tr>
    <td>date_time</td>
    <td>Clearing time, the format is: 2018-10-15 11:05:26<br>The details are the same as the Date Time printed on the receipt.</td>
  </tr>
</table>

<h4>3.Added response parameters for query:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>account</td>
    <td>Oceanpayment MID.</td>
  </tr>
  <tr>
    <td>terminal</td>
    <td>Oceanpayment TID.</td>
  </tr>
  <tr>
    <td>method</td>
    <td>Payment method<br>Output Alipay when getting Alipay<br>Output Alipay when getting Alipay_Offline<br>Output WeChatPay when getting WeChatPay<br>Output WeChatPay when getting WeChatPay_Offline</td>
  </tr>
  <tr>
    <td>batch_number</td>
    <td>Current batch number.</td>
  </tr>
  <tr>
    <td>bill_number</td>
    <td>Current order number.</td>
  </tr>
  <tr>
    <td>order_amount</td>
    <td>Amount of the transaction.</td>
  </tr>
  <tr>
    <td>order_currency</td>
    <td>Transaction currency<br>Adopt international standard ISO 4217.</td>
  </tr>
  <tr>
    <td>date_time</td>
    <td>Trading time, the format is as follows: 2018-10-15 11:05:26<br>When Sale is: transaction time<br>Void is for: void time.</td>
  </tr>
</table>
