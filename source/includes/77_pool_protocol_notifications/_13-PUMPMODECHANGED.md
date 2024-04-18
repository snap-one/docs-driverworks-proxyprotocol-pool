## PUMP\_MODE\_CHANGED

Sent to the proxy to indicate that the pump mode has changed.


### Name

`PUMP_MODE_CHANGED ()`


| Parameter  | Description | Description                       |
| ---------- | ----------- | --------------------------------- |
| `PUMPMODE` | BOOL        | From `<pool_pumpmodes>`True/False |


### Returns

`None`


### Example

`C4:SendToProxy(5001, "PUMP_MODE_CHANGED", {PUMPMODE = "True"})`
