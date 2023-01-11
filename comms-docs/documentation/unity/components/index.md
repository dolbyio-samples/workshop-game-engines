## Components
### Dolby.io Manager

The `Dolby.io Manager` is a component required to let you access the functionnalities of the unity plugin. It will also provide some usefull parameters to configure the plugin.

<div style="text-align:left">
    <img style="padding:25px 0" src="~/images/components/dolbyiomanager.png" width="300px">
</div>

| Name | Type | Description  |
|---|:---|:---|
| **Auto Leave Conference** | Boolean | Allows the plugin to automatically leave the conference when the application is quitting. |
| **Auto Close Session** | Boolean | Allows the plugin to automatically close the session when the application is quitting. |
| **Position Duration** | Float (seconds) | The throttling time for setting the local player position. |
| **Position Source** | GameObject | A GameObject to get the local player position from. | 
| **Direction Duration** | Float (seconds) | The throttling time for setting the local player direction. |
| **Direction Source** | GameObject | A GameObject to get the local player direction from. |