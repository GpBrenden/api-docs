# 200 Response Schema
| Property Name | Description |
| :------------ | :---------- |
| **groupId**<br/>_integer_ | Deprecated. |
| **sensors**<br/>_object array_ |  |
| **&nbsp;&nbsp;&nbsp;&nbsp;cargoEmpty**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;boolean_ | Flag indicating whether the current cargo is empty or loaded. |
| **&nbsp;&nbsp;&nbsp;&nbsp;cargoStatusTime**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;string_ | The timestamp of reported cargo status, specified in RFC 3339 time. |
| **&nbsp;&nbsp;&nbsp;&nbsp;id**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;integer_ | ID of the sensor. |
| **&nbsp;&nbsp;&nbsp;&nbsp;name**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;string_ | Name of the sensor. |
| **&nbsp;&nbsp;&nbsp;&nbsp;trailerId**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;integer_ | ID of the trailer associated with the sensor for the data point. If no trailer is connected, this parameter will not be reported. |
| **&nbsp;&nbsp;&nbsp;&nbsp;vehicleId**<br/>_&nbsp;&nbsp;&nbsp;&nbsp;integer_ | ID of the vehicle associated with the sensor for the data point. If no vehicle is connected, this parameter will not be reported. |
