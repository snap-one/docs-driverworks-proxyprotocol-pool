## SPA\_HEATMODES\_LIST\_CHANGED

This notification provides a way to override capabilities. It is sent to the proxy when the list of available spa heat modes has changed.


### Name

`SPA_HEATMODES_LIST_CHANGED ()`


| Parameter         | Description |
| ----------------- | ----------- |
| `SPA_HEATPMODES ` | XML.        |


### Returns

`None`


### Example

```xml
XML
<spa_heat_modes>
    <mode>
        <id>1</id>
        <text>Heater</text>
        <command>set_spa_heater</command>
    </mode>
</spa_heat_modes>
```
