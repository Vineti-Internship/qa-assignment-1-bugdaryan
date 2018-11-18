<table >
  <tr>
    <th>Test Scenario</th>
    <th>Test Case</th>
    <th>Test Steps</th>
    <th>Test Data</th>
    <th>Expected Result</th>
    <th>Actual Result</th>
    <th>Status</th>
  </tr>
  <tr>
    <td rowspan="7">Checking shipping calculator</td>
    <td rowspan="4">Check Response on entering valid input</td> 
    <td rowspan="7">Select wherehouse country <br/> Select type of order <br/> Select method <br/> Select length width and heigth <br/> Select weight</td>
    <td>America<br/>Online shopping<br/>By air<br/>10kg</td> 
    <td>35000 AMD</td> 
    <td>35000 AMD</td> 
    <td>Pass</td> 
  </tr>
  <tr>
    <td>America<br/>Personal parcel<br/>By sea<br/>10x10x10 cm<br/>20kg</td> 
    <td>50 USD</td> 
    <td>50 USD</td> 
    <td>Pass</td> 
  </tr>
    <tr>
    <td>China<br/>Online shopping<br/>By air<br/>20kg</td> 
    <td>40000 AMD</td> 
    <td>40000 AMD</td> 
    <td>Pass</td> 
  </tr>
    </tr>
    <tr>
    <td>United Kingdom<br/>Online shopping<br/>By air<br/>17pound</td> 
    <td>30844 AMD</td> 
    <td>30844 AMD</td> 
    <td>Pass</td> 
  </tr>
  <tr>
    <td rowspan="2">Check Response on entering invalid input</td>
    <td>America<br/>Online shopping<br/>By air<br/>-1x-1x-1 cm<br>-10kg </td> 
    <td>Info about invalid input</td> 
    <td>400 AMD</td> 
    <td>Fail</td> 
  </tr>
    <tr>
    <td>America<br/>Online shopping<br/>By air<br/>10e+100kg </td> 
    <td>Info about overweight</td> 
    <td>6e+104 AMD</td> 
    <td>Fail</td> 
  </tr>
  <tr>
    <td>Let blank boxes (also there is a difference if you let it blank or write something and clear)</td>
    <td>America<br/>Online shopping<br/>By air<br/> </td> 
    <td>Info about blank input</td> 
    <td>0 OR 400 AMD</td> 
    <td>Fail</td> 
  </tr>
</table>

