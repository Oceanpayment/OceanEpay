Update Time: 2022-07-20.
<h4>1.1.新增订单号字段,可自定义传值:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>order_number</td>
    <td>当 type 为 Sale 时，可传商户的订单号，长度为8-25位。
如果不传OceanPay会自动生成一个6位的订单号

当 type 为 Void 时，订单号必填且用于交易撤销 
1)如果此订单为商户传的订单号，原样传值
2)如果此订单为OceanPay的订单号，传值为：Bill No (交易响应参数返回)</td>
  </tr>  
</table>

<h4>1.2.若订单号为商户传值,则原样返回订单号:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>bill_number</td>
    <td>当前订单号（由OceanPay生成）</td>
  </tr>
  <tr>
    <td>order_number</td>
    <td>1)如果此订单为商户传的订单号，原样返回<br>
2)如果此订单为OceanPay的订单号，由批次号+订单号组成</td>
  </tr> 
</table>

<h4>2.1.查询功能:修改订单号字段,可自定义传值</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>order_number</td>
    <td>1)如果此订单为商户传的订单号，原样传值<br>
2)如果此订单为OceanPay的订单号，传值为：Bill No (交易响应参数返回)</td>
  </tr>  
</table>

<h4>2.2.查询返回：若订单号为商户传值,则原样返回订单号:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>bill_number</td>
    <td>当前订单号（由OceanPay生成）</td>
  </tr>
  <tr>
    <td>order_number</td>
    <td>1)如果此订单为商户传的订单号，原样返回<br>
2)如果此订单为OceanPay的订单号，由批次号+订单号组成</td>
  </tr>  
</table>

<h4>3.1.重新打印请求参数：修改订单号字段,可自定义传值</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>order_number</td>
    <td>1)如果此订单为商户传的订单号，原样传值<br>
2)如果此订单为OceanPay的订单号，传值为：Bill No (交易响应参数返回)</td>
  </tr>
</table>

<h4>3.2.重新打印返回：若订单号为商户传值,则原样返回订单号:</h4>
<table>
  <tr>
    <th>Nmae</th>
    <th>Description</th>  
  </tr>
  <tr>
    <td>order_number</td>
    <td>1)如果此订单为商户传的订单号，原样返回<br>
2)如果此订单为OceanPay的订单号，由批次号+订单号组成</td>
  </tr>  
</table>
