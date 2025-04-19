Update Time: 2025-04-18.
<h4>Add field: pay_accountNumber</h4>
<p>Scan code payment authorization code, barcode or QR code information in user WeChat/Alipay
When type is Sale</p>
<ul>
  <li>When pay_accountNumber is empty, the App will be entered normally, login will be completed, and the camera will be turned on. The cashier needs to complete the scan code before making a payment request to complete the payment</li>
  <li>When pay_accountNumber is not empty, the App will be entered normally, login will be completed, but the camera will not be turned on. The App will directly use the pay_accountNumber field to make a payment request to complete the payment.</li>
<ul>
