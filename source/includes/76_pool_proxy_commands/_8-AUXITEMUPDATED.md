## UPDATE\_AUX\_ITEM

Received from the proxy when the auxiliary id is changed in Auxiliary Controls card. The command should be received only when [provides\_aux\_list][1] capability is set to true.


### Name

`AUX_ITEM_UPDATED ()`


| Parameter | Type | Description    |
| --------- | ---- | -------------- |
| `ID`      | STR  | Current aux ID |
| `NEW_ID`  | STR  | New aux ID     |


### Returns

`None`

[1]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#pool-capabilities